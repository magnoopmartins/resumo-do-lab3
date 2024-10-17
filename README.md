# resumo-do-lab3
Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
1. Escolha do Tipo de Máquina Virtual:

    A Azure oferece uma ampla gama de tipos de VMs, cada um projetado para diferentes workloads, como processadores otimizados, uso de memória, armazenamento ou VMs de propósito geral.
   A importância de escolher corretamente o tipo de VM para evitar super ou subalocação de recursos.

2. Dimensionamento Vertical (Scaling Up/Down):

    O dimensionamento vertical envolve aumentar ou reduzir os recursos (CPU, memória, etc.) alocados a uma máquina virtual existente. Isso é feito escolhendo um tamanho maior ou menor de VM conforme as necessidades de processamento aumentam ou diminuem.

3. Dimensionamento Horizontal (Scaling Out/In):

    O dimensionamento horizontal implica adicionar ou remover instâncias de máquinas virtuais para distribuir a carga de trabalho. A configuração do AutoScale na Azure permite gerenciar automaticamente esse processo com base em critérios como uso de CPU ou tráfego de rede.

4. Alocação de Armazenamento:

    É essencial configurar corretamente os discos de armazenamento para VMs, como discos gerenciados (SSD ou HDD) que oferecem alta performance e são adequados para diferentes workloads. A Azure permite a escolha de discos de acordo com a necessidade de IOPS (operações de entrada/saída por segundo).

5. Balanceamento de Custos e Desempenho:

    Um ponto crucial destacado por Valéria Baptista seria o balanço entre custo e desempenho. Escolher a VM correta impacta diretamente no custo da operação. Dimensionar corretamente evita custos excessivos com recursos não utilizados.

6. Tamanho e Região da Máquina Virtual:

    É importante considerar a localização geográfica das VMs para otimizar a latência e atender a requisitos regulatórios. A Azure oferece VMs em várias regiões globais, e cada região pode ter preços e capacidades diferentes.

7. Redundância e Backup:

    A configuração de alta disponibilidade e recuperação de desastres é fundamental ao dimensionar VMs, utilizando zonas de disponibilidade ou replicação entre diferentes regiões da Azure.

A correta configuração e dimensionamento de VMs garante um uso eficiente da infraestrutura, alinhando desempenho e controle de custos.
