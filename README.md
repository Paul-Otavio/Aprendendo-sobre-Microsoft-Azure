# Aprendendo sobre Microsoft Azure
Minha pasta de estudos contendo o conhecimento obtido durante o curso Microsoft Azure Essentials na DIO, é um compilado de tudo que aprendi sobre os serviços básicos da Azure

# Microsoft Azure 
Microsoft Azure é uma plataforma de computação em nuvem oferecida pela Microsoft, que fornece uma ampla gama de serviços para ajudar empresas e desenvolvedores a construir, gerenciar e implantar aplicativos em uma rede global de data centers. Com Azure, você pode acessar recursos de computação, armazenamento, banco de dados, inteligência artificial, machine learning, IoT, DevOps e muito mais, tudo sob demanda e com escalabilidade flexível.

## Principais Categorias de Serviços

### Analytics (Análise)

- Big Data: Azure Synapse Analytics, HDInsight.
- Data Lakes: Azure Data Lake Storage.
- Streaming: Azure Stream Analytics.

###  Compute (Computação)
- Máquinas Virtuais: VM, VM Scale Sets.
- Contêineres: Azure Kubernetes Service (AKS), Azure Container Instances (ACI).
- Computação sem Servidor: Azure Functions, Azure Logic Apps.

### Databases (Bancos de Dados)
- SQL: Oferece diversas opções de bancos de dados relacionais
     - SQL do Azure: Banco de dados relacional totalmente gerenciado.
     - Azure SQL Database: Banco de dados relacional como serviço.
       
- NoSQL: Oferece opções de bancos de dados não relacionais para alta escalabilidade e flexibilidade
    - Cosmos DB: Banco de dados multi-modelo para grandes volumes de dados.
    - MongoDB no Azure: Banco de dados NoSQL document-oriented.
- Big Data: Permite armazenar e processar grandes volumes de dados
    - Azure Synapse Analytics: Plataforma unificada para dados entre data warehousing e big data analytics.
    - Azure Databricks: Plataforma baseada em Apache Spark para big data analytics.

### Networking (Rede)

- Virtual Networks: Permite criar redes privadas virtuais na nuvem.
    - Azure Virtual Network: Rede virtual isolada para seus recursos.
- Load Balancers: Distribui o tráfego entre várias instâncias de uma aplicação.
    - Azure Load Balancer: Distribui o tráfego de entrada e saída.
- VPN: Permite conectar sua rede local à nuvem.
    - Azure VPN Gateway: Conecta suas redes locais à nuvem.

### Storage (Armazenamento)
- Armazenamento de Blobs: Armazena grandes volumes de dados não estruturados, como imagens, vídeos e arquivos.
- Files: Armazenamento de arquivos compartilhados.
- Discos: Discos gerenciados para VMs.
- Azure Table Storage: Tabelas NoSQL para armazenar grandes volumes de dados.

### AI + Machine Learning (Inteligência Artificial e Aprendizado de Máquina)
- Serviços de IA: Azure Cognitive Services.
- Machine Learning: Azure Machine Learning.

### DevOps
- Integração e Entrega Contínuas: Azure DevOps, GitHub Actions.
- Monitoramento: Azure Monitor, Application Insights.

### Segurança
- Gerenciamento de Identidades: Azure Active Directory (AAD).
- Proteção: Azure Security Center, Azure Key Vault.
- Azure Active Directory (Azure AD): Um serviço de diretório multilocatente baseado em nuvem que conecta seus usuários a recursos locais e em nuvem.

# Maquinas Virtuais na Azure
Máquinas Virtuais do Azure são como computadores virtuais na nuvem. Elas oferecem flexibilidade para criar e gerenciar ambientes de computação personalizados, sem a necessidade de hardware físico. Você pode escalar os recursos conforme necessário e pagar apenas pelo que usar. Ideal para desenvolvimento, testes, hospedagem de sites e muito mais.

## Passo a Passo para Criar uma Máquina Virtual no Azure

### Passo 1: Acessar o Portal do Azure
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar uma Máquina Virtual
2 - __Pesquisar por Máquinas Virtuais:__ No menu de navegação à esquerda, clique em “Máquinas Virtuais” ou digite “Máquinas Virtuais” na barra de pesquisa e selecione a opção.

3 - __Criar uma nova Máquina Virtual:__ Na página de Máquinas Virtuais, clique em “Criar” e depois em “Máquina Virtual do Azure”.

### Passo 3: Configurar a Máquina Virtual

4 - __Configurações Básicas:__

- __Assinatura: Selecione__ a assinatura do Azure que você deseja usar.
- __Grupo de Recursos:__ Escolha um grupo de recursos existente ou crie um novo.
- __Nome da Máquina Virtual:__ Dê um nome à sua máquina virtual.
- __Região:__ Selecione a região onde você deseja que a VM seja hospedada.
- __Imagem:__ Escolha o sistema operacional que você deseja instalar (por exemplo, Windows Server 2019).
- __Tamanho:__ Selecione o tamanho da VM com base nas suas necessidades de CPU e memória.

5 - __Configurações de Administração:__

- __Nome de Usuário:__ Crie um nome de usuário para acessar a VM.
- __Senha:__ Defina uma senha forte para o usuário.

6 - Configurações de Disco:
- __Tipo de Disco do SO:__ Escolha entre SSD ou HDD, dependendo do desempenho desejado.

7 - __Configurações de Rede:__

- __Rede Virtual:__ Selecione uma rede virtual existente ou crie uma nova.
- __Sub-rede:__ Escolha uma sub-rede para a VM.
- __Endereço IP Público:__ Configure um endereço IP público se necessário.

8 - __Configurações de Gerenciamento:__

- __Monitoramento:__ Ative ou desative o monitoramento e diagnósticos conforme necessário.

### Passo 4: Revisar e Criar

9 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a implantação da VM.

### Passo 5: Conectar à Máquina Virtual

10 - __Conectar-se à VM:__ Após a criação, vá para a página da máquina virtual e clique em “Conectar”. Siga as instruções para se conectar via RDP (para Windows) ou SSH (para Linux).

# Instância de Banco de Dados no Azure

Instâncias de banco de dados no Azure são como servidores de banco de dados na nuvem. Elas oferecem um ambiente seguro e escalável para armazenar e gerenciar seus dados. Você pode escolher entre diversos tipos de bancos de dados, como SQL Server e PostgreSQL, e ajustar os recursos conforme a necessidade. O Azure cuida de muitas tarefas de administração, como backups e atualizações, para que você possa se concentrar no seu aplicativo.

## Passo a Passo para Configurar uma Instância de Banco de Dados no Azure

### Passo 1: Acessar o Portal do Azure
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar um Banco de Dados SQL
2 - __Pesquisar por SQL Databases:__ No menu de navegação à esquerda, clique em “SQL Databases” ou digite “SQL Databases” na barra de pesquisa e selecione a opção.

3 - __Criar um novo Banco de Dados:__ Na página de SQL Databases, clique em “Criar” e depois em “Banco de Dados SQL do Azure”.

### Passo 3: Configurar o Banco de Dados

4 - __Configurações Básicas:__
   - **Assinatura:** Selecione a assinatura do Azure que você deseja usar.
   - **Grupo de Recursos:** Escolha um grupo de recursos existente ou crie um novo.
   - **Nome do Banco de Dados:** Dê um nome ao seu banco de dados.
   - **Servidor:** Crie um novo servidor ou selecione um servidor existente. Para criar um novo servidor, forneça um nome de servidor, um nome de administrador e uma senha.
   - **Localização:** Selecione a localização do servidor.
   - 

5 - __Configurações de Elastic Pool (opcional):__
   - **Elastic Pool:** Se você deseja usar um pool elástico, selecione “Sim” e configure o pool. Caso contrário, selecione “Não”.

6 - __Configurações de Computação e Armazenamento:__
   - **Nível de Serviço:** Escolha entre as opções disponíveis (por exemplo, Básico, Standard, Premium) com base nas suas necessidades de desempenho e custo.
   - **Tamanho do Computador:** Selecione o tamanho do computador e a quantidade de armazenamento.


### Passo 4: Configurações Adicionais

7 - __Configurações de Rede:__
   - **Rede Virtual:** Configure a rede virtual se necessário.
   - **Regras de Firewall:** Adicione regras de firewall para permitir o acesso ao banco de dados de endereços IP específicos.

8 - __Configurações de Segurança:__
   - **Autenticação:** Configure a autenticação do banco de dados (por exemplo, autenticação do SQL ou do Azure AD).
   - **Auditoria e Segurança Avançada:** Ative ou desative as opções de auditoria e segurança avançada conforme necessário.

### Passo 5: Revisar e Criar

9 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a implantação do banco de dados.

### Passo 6: Conectar ao Banco de Dados

10 - __Conectar-se ao Banco de Dados:__ Após a criação, vá para a página do banco de dados e clique em “Conectar”. Siga as instruções para se conectar usando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio.


# infraestrutura global azure

## 1. Rede Global
- **Regiões do Azure**: O Azure está disponível em mais de 60 regiões ao redor do mundo, permitindo que você implante serviços próximos aos seus usuários para reduzir a latência.
- **Pontos de Presença (PoPs)**: Mais de 185 PoPs globais garantem conectividade rápida e confiável.
- **Fibra Óptica e Cabos Submarinos**: A infraestrutura inclui 165 mil milhas de fibra óptica e cabos submarinos, proporcionando uma rede resiliente e de alta capacidade.

## 2. Data Centers
- **Data Centers**: O Azure possui mais de 200 data centers, organizados em regiões e interligados por uma das maiores redes do planeta.
- **Segurança e Conformidade**: Os data centers do Azure são projetados com segurança em mente, incluindo medidas físicas e lógicas para proteger os dados.

## 3. Conectividade
- **Azure ExpressRoute**: Oferece conectividade privada e de alta velocidade entre seus data centers locais e o Azure, com velocidades de até 100 Gbps.
- **Latência Baixa**: A rede do Azure é otimizada para oferecer latência ultrabaixa, especialmente em áreas metropolitanas densamente povoadas.

## 4. Segurança e Gerenciamento
- **Segurança Inteligente**: A infraestrutura do Azure inclui uma pilha de rede definida por software que prevê, emula e responde rapidamente a problemas e anomalias.
- **Monitoramento e Atualizações**: A rede do Azure é monitorada continuamente e atualizações são implantadas de forma confiável em poucas horas.

## 5. Inovação e Desempenho
- **SONiC**: A rede do Azure utiliza a plataforma SONiC (Software para Rede Aberta na Nuvem), um sistema operacional de comutador de código aberto desenvolvido para atender aos requisitos de uma plataforma de larga escala.
- **Azure Edge Zones**: Permitem a implantação de aplicativos e funções virtualizadas de rede (VNFs) para fornecer serviços de baixa latência em zonas metropolitanas.

## Mapa da infraestrutura global azure: https://datacenters.microsoft.com/globe/explore/

# Zonas de disponibilidade

Várias regiões do Azure fornecem zonas de disponibilidade, que são grupos separados de datacenters em uma região. As zonas de disponibilidade estão próximas o suficiente para terem conexões de baixa latência com outras zonas de disponibilidade. Elas são conectadas por uma rede de alto desempenho com uma latência de viagem de ida e volta de menos de 2 ms. No entanto, as zonas de disponibilidade estão suficientemente afastadas para reduzir a probabilidade de que mais de uma seja afetada por interrupções locais ou condições meteorológicas. As zonas de disponibilidade têm infraestruturas independentes de energia, resfriamento e rede. Elas são projetadas para que, se uma zona sofrer uma interrupção, os serviços regionais, a capacidade e a alta disponibilidade sejam suportados pelas zonas restantes. Eles ajudam seus dados a permanecerem sincronizados e acessíveis quando as coisas dão errado.

## Replicação entre regiões do Azure

Embora as regiões do Azure sejam concebidas para oferecer proteção contra desastres locais com zonas de disponibilidade, também podem fornecer proteção contra desastres geográficos regionais ou de grande dimensão com recuperação de desastres, utilizando outra região secundária que utiliza replicação entre regiões. Ambas as regiões primária e secundária juntas formam um par de regiões.

A replicação entre regiões é um dos vários pilares importantes na estratégia de continuidade dos negócios e recuperação de desastres do Azure. A replicação entre regiões se baseia na replicação síncrona de seus aplicativos e dados que existem usando zonas de disponibilidade em sua região primária do Azure para alta disponibilidade. A replicação entre regiões replica de modo assíncrono os mesmos aplicativos e dados em outras regiões do Azure para proteção de recuperação de desastre.

## Grupo de recursos

Um grupo de recursos é um contêiner que mantém os recursos relacionados a uma solução do Azure. O grupo de recursos pode incluir todos os recursos para a solução ou apenas os recursos que você deseja gerenciar como um grupo. Você decide como deseja alocar recursos para grupos de recursos com base no que faz mais sentido para sua organização. Em geral, adicione recursos que compartilham o mesmo ciclo de vida no mesmo grupo de recursos, para que você possa implantar, atualizar e excluí-los como um grupo facilmente.


## Passo a Passo para Criar um Grupo de Recursos no Azure

### Passo 1: Acessar o Portal do Azure
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar um Grupo de Recursos
2 - __Pesquisar por Grupos de Recursos:__ No menu de navegação à esquerda, clique em “Grupos de Recursos” ou digite “Grupos de Recursos” na barra de pesquisa e selecione a opção.

3 - __Criar um novo Grupo de Recursos:__ Na página de Grupos de Recursos, clique em “Criar”.

### Passo 3: Configurar o Grupo de Recursos

4 - __Configurações Básicas:__
   - **Assinatura:** Selecione a assinatura do Azure que você deseja usar.
   - **Nome do Grupo de Recursos:** Insira um nome para o novo grupo de recursos.
   - **Região:** Selecione uma localização do Azure, como Brasil Sul.

### Passo 4: Revisar e Criar

5 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a criação do grupo de recursos.

### Passo 5: Verificar o Grupo de Recursos

6 - __Verificar o Grupo de Recursos:__ Leva alguns segundos para criar um grupo de recursos. Selecione “Atualizar” no menu superior para atualizar a lista de grupos de recursos e, em seguida, selecione o grupo de recursos recém-criado para abri-lo. Ou selecione “Notificação” (o ícone de sino) na parte superior e, em seguida, selecione “Ir para o grupo de recursos” para abrir o grupo de recursos recém-criado.

# infraestrutura global azure

## 1. Rede Global
- **Regiões do Azure**: O Azure está disponível em mais de 60 regiões ao redor do mundo, permitindo que você implante serviços próximos aos seus usuários para reduzir a latência.
- **Pontos de Presença (PoPs)**: Mais de 185 PoPs globais garantem conectividade rápida e confiável.
- **Fibra Óptica e Cabos Submarinos**: A infraestrutura inclui 165 mil milhas de fibra óptica e cabos submarinos, proporcionando uma rede resiliente e de alta capacidade.

## 2. Data Centers
- **Data Centers**: O Azure possui mais de 200 data centers, organizados em regiões e interligados por uma das maiores redes do planeta.
- **Segurança e Conformidade**: Os data centers do Azure são projetados com segurança em mente, incluindo medidas físicas e lógicas para proteger os dados.

## 3. Conectividade
- **Azure ExpressRoute**: Oferece conectividade privada e de alta velocidade entre seus data centers locais e o Azure, com velocidades de até 100 Gbps.
- **Latência Baixa**: A rede do Azure é otimizada para oferecer latência ultrabaixa, especialmente em áreas metropolitanas densamente povoadas.

## 4. Segurança e Gerenciamento
- **Segurança Inteligente**: A infraestrutura do Azure inclui uma pilha de rede definida por software que prevê, emula e responde rapidamente a problemas e anomalias.
- **Monitoramento e Atualizações**: A rede do Azure é monitorada continuamente e atualizações são implantadas de forma confiável em poucas horas.

## 5. Inovação e Desempenho
- **SONiC**: A rede do Azure utiliza a plataforma SONiC (Software para Rede Aberta na Nuvem), um sistema operacional de comutador de código aberto desenvolvido para atender aos requisitos de uma plataforma de larga escala.
- **Azure Edge Zones**: Permitem a implantação de aplicativos e funções virtualizadas de rede (VNFs) para fornecer serviços de baixa latência em zonas metropolitanas.

## Mapa da infraestrutura global azure: https://datacenters.microsoft.com/globe/explore/

# O que é um grupo de recursos?

Um grupo de recursos é um contêiner que mantém os recursos relacionados a uma solução do Azure. O grupo de recursos pode incluir todos os recursos para a solução ou apenas os recursos que você deseja gerenciar como um grupo. Você decide como deseja alocar recursos para grupos de recursos com base no que faz mais sentido para sua organização. Em geral, adicione recursos que compartilham o mesmo ciclo de vida no mesmo grupo de recursos, para que você possa implantar, atualizar e excluí-los como um grupo facilmente.

## Passo a Passo para Criar um Grupo de Recursos no Azure

### Passo 1: Acessar o Portal do Azure
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar um Grupo de Recursos
2 - __Pesquisar por Grupos de Recursos:__ No menu de navegação à esquerda, clique em “Grupos de Recursos” ou digite “Grupos de Recursos” na barra de pesquisa e selecione a opção.

3 - __Criar um novo Grupo de Recursos:__ Na página de Grupos de Recursos, clique em “Criar”.

### Passo 3: Configurar o Grupo de Recursos

4 - __Configurações Básicas:__
   - **Assinatura:** Selecione a assinatura do Azure que você deseja usar.
   - **Nome do Grupo de Recursos:** Insira um nome para o novo grupo de recursos.
   - **Região:** Selecione uma localização do Azure, como Brasil Sul.

### Passo 4: Revisar e Criar

5 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a criação do grupo de recursos.

### Passo 5: Verificar o Grupo de Recursos

6 - __Verificar o Grupo de Recursos:__ Leva alguns segundos para criar um grupo de recursos. Selecione “Atualizar” no menu superior para atualizar a lista de grupos de recursos e, em seguida, selecione o grupo de recursos recém-criado para abri-lo. Ou selecione “Notificação” (o ícone de sino) na parte superior e, em seguida, selecione “Ir para o grupo de recursos” para abrir o grupo de recursos recém-criado.

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais no Azure
Passo a Passo para Configurar Recursos e Dimensionamentos em Máquinas Virtuais no Azure

### Passo 1: Acessar o Portal do Azure
1 - **Acesse o portal do Azure:** Vá para portal.azure.com e faça login com sua conta Microsoft.

### Passo 2: Criar uma Máquina Virtual
2 - __Pesquisar por Máquinas Virtuais:__ No menu de navegação à esquerda, clique em “Máquinas Virtuais” ou digite “Máquinas Virtuais” na barra de pesquisa e selecione a opção.

![CriandoVM](https://github.com/user-attachments/assets/47656f13-9e31-4d43-b4b6-3a9f5302b420)

3 - __Criar uma nova Máquina Virtual:__ Na página de Máquinas Virtuais, clique em “Criar” e depois em “Máquina Virtual do Azure”.

![CriandoVM01](https://github.com/user-attachments/assets/d9e6080d-fa3b-4021-865b-81881648b784)

### Passo 3: Configurar a Máquina Virtual

4 - __Configurações Básicas:__
   - **Assinatura:** Selecione a assinatura do Azure que você deseja usar.
   - **Grupo de Recursos:** Escolha um grupo de recursos existente ou crie um novo.
   - **Nome da Máquina Virtual:** Dê um nome à sua máquina virtual.
   - **Região:** Selecione a região onde você deseja que a VM seja hospedada.
   - **Imagem:** Escolha o sistema operacional que você deseja instalar (por exemplo, Windows Server 2019).
   - **Tamanho:** Selecione o tamanho da VM com base nas suas necessidades de CPU e memória.

![CriandoVM02](https://github.com/user-attachments/assets/7e6b6fd5-1eed-41a1-b6ca-3c2ca618eb0f)

![CriandoVM03](https://github.com/user-attachments/assets/32133228-afd7-4fb8-8a15-0455f769dacc)

![CriandoVM04](https://github.com/user-attachments/assets/360e3c53-a320-41b6-9899-2a4fcbc74d00)

5 - __Configurações de Administração:__
   - **Nome de Usuário:** Crie um nome de usuário para acessar a VM.
   - **Senha:** Defina uma senha forte para o usuário.

6 - __Configurações de Disco:__
  - As VMs do Azure têm um disco de sistema operacional e um disco temporário para armazenamento de curto prazo. É possível anexar mais discos de dados. O tamanho da VM determina o tipo de armazenamento que pode ser usado e o número de discos de dados permitidos.
   - **Tipo de Disco do SO:** Escolha entre SSD ou HDD, dependendo do desempenho desejado.

## Tipos de Armazenamento no Azure

### Armazenamento com Redundância Local
Os dados são replicados em um único datacenter.

  -  __SSD Premium:__ Melhor para cargas de trabalho confidenciais de produção e desempenho.

 - __SSD Standard:__ Melhor para servidores Web, aplicativos empresariais e desenvolvimento/teste pouco usados.

 - __HDD Standard:__ Melhor para acesso de backup, não crítico e não frequente.

### Armazenamento com Redundância de Zona
 Os dados são replicados para três zonas.

- __SSD Premium:__ Melhor para as cargas de trabalho de produção que precisam de resiliência de armazenamento contra falhas de zona.

- SSD __Standard:__ Melhor para servidores Web, aplicativos empresariais pouco usados e desenvolvimento/teste que precisam de resiliência de armazenamento contra falhas de zona.

     
![image](https://github.com/user-attachments/assets/7eed2fb6-a349-405d-bbdd-5a9040a098a4)

7 - __Configurações de Rede:__
   - **Rede Virtual:** Selecione uma rede virtual existente ou crie uma nova.
   - **Sub-rede:** Escolha uma sub-rede para a VM.
   - **Endereço IP Público:** Configure um endereço IP público se necessário.
     
8 - __Configurações de Gerenciamento:__

 - **Microsoft Defender para Nuvem:** Habilite o plano básico gratuitamente para proteção avançada contra ameaças.
   - **Identidade:** Habilite a identidade gerenciada atribuída pelo sistema.
   - **Microsoft Entra ID:** Configure o login com o Microsoft Entra ID.
   - **Desligamento Automático:** Habilite o desligamento automático se necessário.
   - **Backup:** Habilite o backup para proteger seus dados.
   - **Atualizações do SO Convidado:** Configure as opções de orquestração de patch conforme necessário.
     
![image](https://github.com/user-attachments/assets/248f1cf6-8b85-42cf-a272-53e0c540aba7)

9 - __Monitoramento:__
   - **Monitoramento:** Ative ou desative o monitoramento e diagnósticos conforme necessário.
     
![image](https://github.com/user-attachments/assets/e346d2bf-622d-459d-a65e-9b58c552c6fe)

### Passo 4: Dimensionar a Máquina Virtual

10 - __Dimensionar a VM:__
   - **Dimensionamento Vertical:** Para aumentar ou diminuir os recursos de CPU e memória da VM, vá para a página da máquina virtual, clique em "Tamanho" no menu lateral e selecione uma nova configuração de tamanho que atenda às suas necessidades[^1^][6].
   - **Dimensionamento Horizontal:** Para adicionar mais instâncias da VM, você pode configurar um Conjunto de Dimensionamento de Máquinas Virtuais (VMSS). No portal do Azure, pesquise por "Conjunto de Dimensionamento de Máquinas Virtuais" e siga as instruções para criar e configurar o conjunto.

### Passo 5: Revisar e Criar

11 - __Revisar e Criar:__ Revise todas as configurações e clique em “Revisar e Criar”. Após a validação, clique em “Criar” para iniciar a implantação da VM.

### Passo 6: Conectar à Máquina Virtual

12 - __Conectar-se à VM:__ Após a criação, vá para a página da máquina virtual e clique em “Conectar”. Siga as instruções para se conectar via RDP (para Windows) ou SSH (para Linux).

# Identidade, acesso e segurança na Azure

## Microsoft Entra ID

O Microsoft Entra ID é o serviço de gerencimento de identidades e acesso baseado em nuvem, que seus funcionários podem usar para acessarem recursos externos. Os recursos de exemplo incluem o Microsoft 365, o portal do Azure e milhares de outros aplicativos SaaS.

O Microsoft Entra ID também ajuda a acessar os recursos internos, como aplicativos na intranet corporativa e com os aplicativos de nuvem desenvolvidos para sua própria organização. 

## Responsabilidade do Microsoft Entra
- Autenticação (os funcionários entram para acessar os recursos).
- Logon único (SSO).
- Gerenciamento de aplicativos.
- Negócios para Negócios (b2b).
- Gerenciamentode dispositivos.

## logon único (SSO) da ID do Microsoft

O logon único é um método de autenticação que permite aos usuários entrar usando um conjunto de credenciais para vários sistemas de software independentes. Com o uso do SSO, o usuário não precisa se conectar em cada aplicativo que usa. Com o SSO, os usuários podem acessar todos os aplicativos necessários sem precisar autenticar novamente usando outras credenciais. 

##  Microsoft Entra Domain Services
O Microsoft Entra Domain Services fornece serviços de domínio gerenciado, como ingresso no domínio, política de grupo, protocolo LDAP e autenticação Kerberos/NTLM. Você pode usar esses serviços de domínio sem a necessidade de implantar, gerenciar e aplicar um patch em DCs (controladores de domínio) na nuvem.


| Categoria | Descrição |
|---|---|
|Gerenciamento de aplicativos| Gerencie seus aplicativos de nuvem e locais usando o Proxy de Aplicativo, o logon único, o portal Meus aplicativos e aplicativos SaaS (software como serviço).|
|Autenticação |	Gerencie a redefinição de senha self-service do Microsoft Entra, a autenticação multifator, a lista de senhas proibidas personalizadas e o bloqueio inteligente|
|Microsoft Entra ID para desenvolvedores|	Crie aplicativos que aceitam todas as identidades da Microsoft, obtenha tokens para chamar o Microsoft Graph, outras APIs da Microsoft ou APIs personalizadas.|
|B2B (Entre empresas)|	Gerencie usuários convidados e parceiros externos enquanto mantém o controle sobre seus próprios dados corporativos.|
|B2C (Entre empresa e consumidor)|	Personalize e controle como os usuários se inscrevem, entram e gerenciam seus perfis ao usar os aplicativos. |
|Acesso Condicional	|Gerencie o acesso a seus aplicativos de nuvem.|
|Gerenciamento de dispositivo |	Gerencie como os dispositivos de nuvem ou locais acessam seus dados corporativos. |
|Serviços do domínio|	Adicione máquinas virtuais do Azure a um domínio sem usar controladores de domínio.|
|Usuários corporativos|	Gerencie as atribuições de licenças e o acesso a aplicativos e configure representantes usando grupos e funções de administrador. |
|Identidade híbrida	|Use o Microsoft Entra Connect e o Connect Health para fornecer uma identidade de usuário única para autenticação e autorização de todos os recursos, independentemente da localização (nuvem ou local).|
|Governança de identidade |	O P2 do Microsoft Entra ID inclui recursos básicos para PIM (Privileged Identity Management), revisões de acesso e gerenciamento de direitos. Os clientes do Microsoft Entra ID Governance podem gerenciar as identidades e o acesso de sua organização por meio de controles abrangentes de funcionários, parceiros de negócios, fornecedor, serviço e aplicativo. |
|Identity Protection|	Detecte possíveis vulnerabilidades que afetam as identidades da organização, configure políticas para responder a ações suspeitas e tome as devidas providências para resolvê-las.|
|Identidades gerenciadas dos recursos do Azure|	Forneça aos seus serviços do Azure uma identidade gerenciada automaticamente na ID do Microsoft Entra que possa autenticar qualquer serviço de autenticação suportado pelo Microsoft Entra, incluindo o Key Vault. |
|PIM (Privileged Identity Management)|	Gerencie, controle e monitore o acesso em sua organização. Esse recurso inclui o acesso aos recursos no Microsoft Entra ID e no Azure e outros Serviços do Microsoft Online, como o Microsoft 365 ou o Intune. |
|Monitoramento e integridade |	Obtenha insights sobre padrões de uso e segurança em seu ambiente. |
|Identidades de carga de trabalho |	Dê uma identidade para sua carga de trabalho de software (como um aplicativo, serviço, script ou contêiner) para autenticar e acessar outros serviços e recursos. |

## Comparação entre autenticação e a autorização

### Autenticação
- Identifica a pessoa ou serviço buscando acesso a um recurso.
- Solicita credenciais de acesso legítimo.
- Base para criar principios de identidade e controle de acesso seguros

### Autorização
- Determina o nivel de acesso de uma pessoa ou serviço autenticado.
- Define quais dados eles podem acessar e o que podem fazer com eles.

## Autenticação multifator  (MFA) 

A autenticação multifator é um processo no qual os usuários são solicitados, durante o processo de entrada, a fornecer uma forma adicional de identificação, como um código no celular ou uma verificação de impressão digital.

Se você usar apenas uma senha para autenticar um usuário, isso deixará um vetor inseguro para ataque. Se a senha for fraca ou tiver sido exposta em outro lugar, um invasor poderá usá-la para obter acesso indevido. Quando você exige uma segunda forma de autenticação, a segurança é aprimorada porque esse fator adicional não é algo fácil de ser obtido ou duplicado por um invasor.


A autenticação multifator do Microsoft Entra funciona exigindo dois ou mais dos seguintes métodos de autenticação:

- Algo que você sabe, normalmente, uma senha.
- Algo que você tem, como um dispositivo confiável que não seja facilmente duplicado, como um telefone ou uma chave de hardware.
- Algo que você é: uma biometria, como uma impressão digital ou uma verificação facial.

| Termo ou Conceito | Descrição |
|---|---|
| Identidade | Qualquer entidade que possa ser autenticada, como um usuário (com nome de usuário e senha), um aplicativo ou um servidor (com certificados ou chaves secretas). |
| Conta | Uma identidade com dados associados a ela. É impossível ter uma conta sem uma identidade. |
| Conta do Microsoft Entra | Uma identidade criada no Microsoft Entra ID ou em outros serviços da Microsoft (como o Microsoft 365). É armazenada no Microsoft Entra ID e pode ser acessada pelas assinaturas do serviço de nuvem da organização. |
| Administrador de Conta | Função clássica que concede acesso total à cobrança de uma assinatura. Permite gerenciar todas as assinaturas de uma conta. |
| Administrador de Serviços | Função clássica que concede acesso total aos recursos do Azure, incluindo o acesso. Equivalente à função de Proprietário no RBAC. |
| Proprietário | Função do RBAC que permite gerenciar todos os recursos do Azure, incluindo o acesso. Parte de um sistema de autorização mais recente e refinado. |
| Administrador Global do Microsoft Entra | Função atribuída ao criador do locatário. Permite atribuir funções de administrador a outros usuários. |
| Assinatura do Azure | Mecanismo de pagamento pelos serviços do Azure. Uma organização pode ter múltiplas assinaturas, cada uma vinculada a um cartão de crédito. |
| Locatário | Instância dedicada e confiável do Microsoft Entra ID. Representa uma única organização e é usada para gerenciar funcionários, aplicativos e outros recursos internos (configuração de locatário de força de trabalho) ou para soluções de gerenciamento de acesso e identidade do cliente (configuração externa). |
| Locatário único | Locatários do Azure que acessam outros serviços em um ambiente dedicado, são considerados locatários únicos. |
| Multilocatário | Locatários do Azure que acessam outros serviços em um ambiente compartilhado, em várias organizações, são considerados multilocatários. |
| Diretório do Microsoft Entra | Cada locatário do Azure tem um diretório do Microsoft Entra dedicado e confiável. O diretório do Microsoft Entra inclui usuários, grupos e aplicativos do locatário e é usado para executar as funções de identidade e gerenciamento de acesso aos recursos de locatário. |
| Domínio personalizado | Todo diretório novo do Microsoft Entra vem com um nome de domínio inicial. Além desse nome inicial, você também pode adicionar os nomes de domínio da sua organização. |
| Conta da Microsoft (MSA) | Contas pessoais que fornecem acesso aos produtos e serviços de nuvem da Microsoft orientados ao consumidor. |


## B2B do Microsoft Entra External ID
A ID externa do Microsoft Entra inclui recursos de colaboração que permitem que sua força de trabalho trabalhe com segurança com parceiros de negócios e convidados. No locatário da força de trabalho, use a colaboração B2B para compartilhar os aplicativos e serviços da sua empresa com convidados, mantendo o controle sobre seus próprios dados corporativos. Trabalhe com segurança com parceiros externos, mesmo que eles não tenham o Microsoft Entra ID ou um departamento de TI.

## B2C do Identidades Externas do Azure AD 

A ID externa do Microsoft Entra combina soluções avançadas para trabalhar com pessoas de fora da sua organização. Com recursos de ID externa, você pode permitir que identidades externas acessem com segurança seus aplicativos e recursos. Se você estiver trabalhando com parceiros, consumidores ou clientes comerciais externos, os usuários podem trazer suas próprias identidades. Essas identidades podem variar de contas corporativas ou emitidas pelo governo a provedores de identidade social, como Google ou Facebook.

## Acesso Condicional

O perímetro de segurança moderno se estende além do perímetro de rede de uma organização para incluir a identidade do usuário e do dispositivo. As organizações agora usam esses sinais de identidade como parte de suas decisões de controle de acesso. O acesso condicional do Microsoft Entra reúne sinais para tomar decisões e impor políticas organizacionais. 

- Associação de usuário ou grupo
- Local do IP
- dispositivo
- Aplicativo
- Detecção de risco

## Controle de acesso baseado em função (RBAC)

O gerenciamento de acesso para recursos de nuvem é uma função crítica para qualquer organização que esteja usando a nuvem. O RBAC do Azure (controle de acesso baseado em funções do Azure) ajuda a gerenciar quem tem acesso aos recursos do Azure, o que pode fazer com esses recursos e a quais áreas tem acesso.

O RBAC do Azure é um sistema de autorização baseado no Azure Resource Manager que fornece gerenciamento de acesso refinado para recursos do Azure.

- Gerenciamento de acesso de granularidade fina.
- Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuários precisam para trabalhar.
- Habilite o acesso ao portal do Azure e o controle de acesso aos recursos.

## Segurança de Confiança Zero

Confiança Zero é um novo modelo de segurança que pressupõe uma violação e verifica cada solicitação como se ela tivesse sido originada de uma rede não controlada.

### Princípios orientadores da Confiança Zero

- __Verificar de modo explícito__ – sempre autentique e autorize com base em todos os pontos de dados disponíveis.
- __Usar o acesso com o mínimo de privilégios__ – limite o acesso do usuário com JIT/JEA (Just-In-Time e Just-Enough-Access), políticas adaptáveis baseadas em risco e proteção de dados.
- __Pressupor a violação__ – minimize o raio de alcance e segmente o acesso. Verifique a criptografia de ponta a ponta e use a análise para obter visibilidade, promover a detecção de ameaças e melhorar as defesas.

## Proteção completa

- Uma adordagem em camadas para proteger sistemas de computador
- Fornece vários níveis de proteção
- Ataques contra uma camada são isolados das camdas subsequentes.

## Microsoft Defender para Nuvem

O Microsoft Defender para Nuvem é uma plataforma de CNAPP (proteção de aplicativo nativo de nuvem) composta de medidas e práticas de segurança projetadas para proteger os aplicativos baseados em nuvem contra várias ameaças e vulnerabilidades cibernéticas. O Defender para Nuvem combina os recursos de:

- Uma solução de operações de segurança de desenvolvimento (DevSecOps) que unifica o gerenciamento de segurança no nível do código em ambientes multinuvem e de vários pipelines

- Uma solução de CSPM (gerenciamento da postura de segurança na nuvem) que apresenta ações que você pode executar para evitar violações

- Uma CWPP (plataforma de proteção de carga de trabalho de nuvem) com proteções específicas para servidores, contêineres, armazenamento, bancos de dados e outras cargas de trabalho

- Fornece recomendações de segurança.

- Detectar e bloquear malware

- Analisar e identificar ataques potenciais.

- Controle de acesso just-in-time para portas.


## Governança e conformidade

 - Blueprints, políticas e bloqueios de recursos
 - Portal de confiança do Serviço

 ## Azure Policy

O Azure Policy ajuda a impor padrões organizacionais e a avaliar a conformidade em escala. Por meio do painel de conformidade, ele fornece uma exibição agregada para avaliar o estado geral do ambiente, com a capacidade de drill down para a granularidade por recurso, por política. Ele também ajuda a deixar seus recursos em conformidade por meio da correção em massa de recursos existentes e da correção automática para novos recursos.
 
 Ele fornece Governança e consistência de recursos com conformidade regulatória, segurança, custo e gerencimento.


- Gerenciar bloqueios na assinatura, grupo de recursos ou níveis de recursos individuais dentro do Portal do Azure.

- Avaliar e identifica os recursos do Azure que não atendem às suas políticas.

- Fornecce definições de polìticas e iniciativas integredas, em categorias como armazenamento, rede, computação, central de segurança e monitoramento.

 ## Algumas ações úteis de governança que você pode impor com o Azure Policy incluem:

- Garantir que a equipe implante recursos do Azure apenas em regiões permitidas
- Impor a aplicação consistente de marcas taxonômicas
- Exigir que os recursos enviem logs de diagnóstico a um workspace do Log Analytics

## Bloqueios de recursos

Como administrador, você pode bloquear uma assinatura do Azure, um grupo de recursos ou um recurso para protegê-los contra exclusões e modificações acidentais do usuário. O bloqueio substitui todas as permissões que o usuário tenha.

No portal, os bloqueios são chamados de __Excluir__ e __Somente leitura__. Na linha de comando, esses bloqueios são chamados de __CanNotDelete__ e __ReadOnly__.

- __CanNotDelete__ significa que os usuários autorizados ainda poderão ler e modificar um recurso, mas não poderão excluí-lo.
- __ReadOnly__ significa que os usuários autorizados poderão ler um recurso, mas não poderão excluir ou atualizá-lo. Aplicar esse bloqueio é semelhante a restringir todos os usuários autorizados para as permissões concedidas pela função Leitor.

| Tipos de bloqueio | Ler  | Atualizar | Excluir |
|-------------------|----- |-----------|---------|
| Excluir           | Sim  | Sim       | Não     |
| ReadOnly          | Sim  | Não       | Não     |

## Herança de bloqueio

Quando você aplica um bloqueio a um escopo pai, todos os recursos filho herdam o mesmo bloqueio. Até mesmo os recursos que você herda posteriormente herdam o bloqueio do pai. O bloqueio mais restritivo na herança terá precedência.

## Portal de Confiança do Serviço

O Microsoft Service Trust Portal fornece uma variedade de conteúdo, ferramentas e outros recursos sobre como os serviços de nuvem da Microsoft protegem seus dados e como você pode gerenciar a segurança e a conformidade de dados de nuvem para sua organização.

## Microsoft Purview

O Microsoft Purview é um conjunto abrangente de soluções que podem ajudar sua organização a controlar, proteger e gerenciar dados, onde quer que eles estejam. As soluções do Microsoft Purview fornecem cobertura integrada e ajudam a resolver a fragmentação de dados entre organizações, a falta de visibilidade que dificulta a proteção e a governança de dados e a permeabilidade de funções tradicionais de gerenciamento de TI.

O Microsoft Purview é uma família de soluções de __governança, risco e conformidade de dados__ que ajuda você a obter uma única exibição unificada em seus dados.

O Microsoft Purview reúne insights sobre seus dados locais, multinuvem e de software como serviço.

O Microsoft Purview combina os antigos serviços e soluções do Azure Purview e de conformidade do Microsoft 365 em uma plataforma unificada para ajudar sua organização:

- Obtenha visibilidade de dados em toda a sua organização
- Proteja e gerencie dados confidenciais em todo o ciclo de vida, onde quer que eles estejam
- Governe os dados perfeitamente de maneiras novas e abrangentes
- Gerencie os riscos de dados críticos e requisitos regulatórios.

[![purview-areas](https://github.com/user-attachments/assets/e0d2b2f7-1dcd-4aaf-9616-0383146e844f)](https://private-user-images.githubusercontent.com/106889378/367611906-e0d2b2f7-1dcd-4aaf-9616-0383146e844f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjg0MjQxODAsIm5iZiI6MTcyODQyMzg4MCwicGF0aCI6Ii8xMDY4ODkzNzgvMzY3NjExOTA2LWUwZDJiMmY3LTFkY2QtNGFhZi05NjE2LTAzODMxNDZlODQ0Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMDA4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTAwOFQyMTQ0NDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wYWJmMDYzZWQzNDk0MGU0ZmI2ZDlhOGJmOTU2ZmVjODE0ODE2MDRlOTY0ZGNlZTYwZmJlZTA5OWQ0ZDIyMjlhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.XI75hc2wFH-s9A5czzruVMWT7eL1wbdcB-UmiTh-E7I)

# Projeto Dio Otimizando Custos no Azure
Este repositório contém o resumo das lições aprendidas sobre Otimizando Custos no Azure 

 ## Gerenciamento e Governança
 
 Fatores que afetam os custos:

 1 - __Tipo de recurso:__ 

 Os custos são específicos do recurso, portanto, o uso que um medidor rastreia e o número  de medidores associados a um recurso, dependendo do tipo de recurso.

 2 - __Consumo:__

 Com um modelo pago conforme o uso, o consumo é um dos maiores geradoresde custos.

 3 - __Manutenção:__

 Monitorar seu volume do Azure e manter seu ambiente pode ajudá-lo a identificar e reduzir os custos que não são necessários, como ao desligar a máquinas virtuais e subutilizadas.

 4 - __Área geográfica:_

 o mesmo tipo de recurso pode custar valores diferentes dependendo da área geográfica. o que afeta os custos do Azure.

 5 - __Tráfego de rede:__

 Embora algumas transfências de dados de entrada sejam gratuitas, o custo para dados de saída ou dados entre recursos do Azure é afetado por zonas de cobrança.

 6 - __Assinatura:__

 O tipo e a configuração da assinatura também podem afetar o custo, por exemplo, a avaliação gratuita permite explorar alguns recursos do Azure gratuitamente. 

## Quais fatores influenciam o custo de um serviço no Azure?

- __Poder de computação__ - O poder de computação refere-se à quantidade de CPU e memória atribuída a um recurso. Quanto mais poder computacional alocado a um recurso, maior será o custo. Muitos serviços do Azure incluem a capacidade de dimensionar elasticamente, permitindo que você aumente a capacidade de computação quando a demanda é alta, mas reduza e economize dinheiro quando a demanda é baixa.

- __Quantidade de armazenamento__ - A maioria dos serviços de armazenamento é cobrada com base na quantidade de dados que você deseja armazenar.

- __Hardware de armazenamento__ - Alguns serviços de armazenamento fornecem opções sobre o tipo de hardware em que seus dados serão armazenados. Dependendo do tipo de dados que você está armazenando, talvez você queira uma opção de armazenamento mais de longo prazo com velocidades de leitura e gravação mais lentas ou pode estar disposto a pagar por leitura e gravação de baixa latência para operações altamente transacionais.

- __Largura de banda__ - A maioria dos serviços fatura entrada e saída separadamente. Ingresso é a quantidade de largura de banda necessária para lidar com solicitações de entrada. Saída é a quantidade de largura de banda necessária para lidar com dados de saída que satisfazem essas solicitações.

- __Por uso__ - Alguns serviços faturam com base no número de vezes que o serviço é usado ou uma contagem do número de solicitações que são tratadas ou o número de alguma entidade (como contas de usuário do Microsoft Entra) que foram configuradas.

- __Por serviço__ - Alguns serviços simplesmente cobram uma mensalidade direta.

- __Região__ - Às vezes, os serviços têm preços diferentes dependendo da região (data center) onde estão hospedados.

## Calculadora de preços do Azure

A maioria das soluções do Azure envolve vários serviços do Azure, tornando desafiador determinar o custo de uma solução antecipadamente. Por esse motivo, o Azure fornece a Calculadora de Preços do Azure para ajudar a estimar quanto custará uma solução.

<a href="https://azure.microsoft.com/pt-br/pricing/calculator/" style="display: inline-block; padding: 10px 20px; font-size: 16px; color: white; background-color: blue; text-align: center; text-decoration: none; border-radius: 5px;">Clique Aqui</a>

### Calculadora de custo total de propriedade (TCO)

- Uma ferramente para estimar a enconomia de custos possível ao migrar para Azure.

- Um relatório compara os custos das infraestruturas locais com os custos de uso do produtos e serviços do Azure na nuvem.

<a href="https://azure.microsoft.com/pt-br/pricing/calculator/](https://azure.microsoft.com/pt-br/pricing/tco/calculator/)" style="display: inline-block; padding: 10px 20px; font-size: 16px; color: white; background-color: blue; text-align: center; text-decoration: none; border-radius: 5px;">Clique Aqui</a>

## Gerenciamento de Custos da Microsoft

o Gerenciamento de Custos da Microsoft é uma solução de gerenciamento de custos que ajuda você a usar e gerenciar o Azure e outros recursos de nuvem de forma eficaz. Colete dados de uso de nuvem e de cobrança por meio de APIs (interfaces de programas aplicativos) do Azure, Amazon Web Services e Google Cloud Platform. Com os dados, obtenha visibilidade total do consumo de recursos e dos custos nas plataformas de nuvem em uma exibição única e simplificada. Monitorar de maneira contínua o consumo e as tendências de custos da nuvem. Acompanhe os gastos reais com a nuvem usando o seu orçamento como base para evitar gastos excessivos. Detecte anomalias nos gastos e ineficiências no uso. Use dados históricos para melhorar a precisão das previsões para o uso e as despesas da nuvem.

## Azure Marketplace

O Azure Marketplace é uma loja online destinada a profissionais de TI e desenvolvedores, oferecendo soluções criadas ou adaptadas para o Azure. Os compradores podem acessar o Azure Marketplace tanto pelo portal do Azure quanto pela loja online na Web. A loja inclui listagens para serviços de consultoria e gerenciados. Os serviços de consultoria do Azure Marketplace são ofertas de serviços profissionais que ajudam os clientes a começar a usar o Azure ou a aprender a utilizá-lo mais rapidamente.

Além disso, o Azure Marketplace permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos e serviços de centenas de provedores líderes, todos certificados para execução no Azure.

## Marcas (tags) no Azure

- Fornecem metadados aos recursos do Azure.

- Organizam os recursos em uma taxonomia de maneira logica.

- Consistem em um par nome-valor.

- Muito úties para reunir informações de cobrança

- Não são obrigatórias e não herdáveis.

# Ferramentas de Gerenciamento e Implantação

- Portal do Azure, Azure PowerShell, Azure Cloud Shell, Interface de linha de Comando (CLI) e outras

- Azure Arc e Azure Resource Manager

![FerramentoAzure](https://github.com/user-attachments/assets/abb5e3b8-9200-45ce-91fa-05d5667c3e84)

 ## Azure Arc

Azure ArcO Azure Arc é uma ponte que estende a plataforma Azure para ajudá-lo a criar aplicativos e serviços com flexibilidade para execução em datacenters, na borda e em ambientes multinuvem. 

O Azure Arc simplifica a governança e o gerenciamento ao fornecer uma plataforma de gerenciamento local consistente e de várias nuvens.

O Azure Arc fornece uma forma centralizada e unificada para:

- Gerenciar todo o seu ambiente projetando os recursos existentes que não são do Azure e/ou locais no Azure Resource Manager.

- Gerencie máquinas virtuais, clusters do Kubernetes e bancos de dados como se eles estivessem em execução no Azure.

- Use as funcionalidades familiares de gerenciamento e serviços do Azure, independentemente de onde eles estejam hospedados.

- Continuar usando a ITOps tradicional, introduzindo práticas de DevOps para dar suporte a novos padrões nativos de nuvem no seu ambiente.

- Configurar localizações personalizadas como uma camada de abstração no cluster de Kubernetes habilitado para Azure Arc e nas extensões de cluster.

![azure-arc-control-plane](https://github.com/user-attachments/assets/f9f628a5-6811-4abd-9e2a-73f340ec5c2a)

## Azure Resource Manager

O ARM (Azure Resource Manager) fornece uma camada de gerencimento que permite criar, atualizar e excluir recursos na assinatura do Azure.

OS modelos do ARM são arquivos __JSON__(JavaScript Object Notation) que podem ser usados para cirar e implantar a infraestrutura do Azure sem a necessidade de escrever comandos de programação.

### Modelos do ARM (Azure Resource Manager)

- __Sintaxe declarativa:__ Os modelos ARM usam uma linguagem declarativa para definir a infraestrutura e a configuração do Azure. Você descreve o que deseja implantar sem precisar escrever a lógica de programação para criar os recursos.

- __Resultados repetíveis:__ Com os modelos ARM, você pode garantir que as implantações sejam consistentes e repetíveis. Isso significa que você pode implantar a mesma infraestrutura várias vezes com os mesmos resultados.

- __Orquestração:__ Os modelos ARM permitem orquestrar a criação de recursos, garantindo que eles sejam implantados na ordem correta e com as dependências apropriadas.

- __Arquivos modulares:__ Você pode dividir seus modelos ARM em arquivos menores e modulares, facilitando a gestão e a reutilização de componentes de infraestrutura.

- __Validação integrada:__ Antes de implantar um modelo ARM, você pode validá-lo para garantir que não haja erros de sintaxe ou configuração. Isso ajuda a evitar falhas durante a implantação.

- __Código exportável:__ Você pode exportar a configuração atual de seus recursos no Azure como um modelo ARM, permitindo que você capture o estado atual da infraestrutura e o reutilize ou modifique conforme necessário.

### Camada de gerenciamento consistente

Quando você envia uma solicitação por meio de qualquer uma das APIs, das ferramentas ou dos SDKs do Azure, o Resource Manager recebe a solicitação. Ele autentica e autoriza a solicitação antes de encaminhá-la para o serviço apropriado do Azure. Como todas as solicitações são manipuladas por meio da mesma API, você verá funcionalidades e resultados uniformes em todas as diferentes ferramentas.

A imagem a seguir mostra o papel que o Azure Resource Manager desempenha na manipulação de solicitações do Azure.


![consistent-management-layer](https://github.com/user-attachments/assets/58a47ed1-c9ea-4c76-8790-dd3670c14e3e)

### Infraestrutura como Código

- Garanta consistência implantação em todo o ecossistema de nuvem.

- Gerencie a configuração em escala


## Bicep

O Bicep é uma linguagem específica de domínio (DSL) que usa sintaxe declarativa para implantar recursos do Azure. Em um arquivo Bicep, você define a infraestrutura que deseja implantar no Azure e, em seguida, usa esse arquivo durante todo o ciclo de vida de desenvolvimento para implantar repetidamente a sua infraestrutura. Os seus recursos são implantados de maneira consistente.

O Bicep fornece sintaxe concisa, segurança de tipos confiável e suporte para reutilização de código. O Bicep uma experiência de criação de alto nível para suas soluções de infraestrutura como código no Azure.

# Monitoramento Inteligente com o Azure
Meu repositório criado para o projeto dio Monitoramento Inteligente com o Azure

## Ferramentas de Monitoramento

- Assistente do Azure
- Integridade do Serviço do Azure
-  Azure Monitor

## Assistente do Azure

O Assistente do Azure analisa recursos implatados do Azure e faz recomendações com base nas práticas recomendadas para otimizar as implantações do Azure.

Ele analisa sua configuração de recursos e telemetria de uso e, em seguida, recomenda soluções que podem ajudar você a melhorar a relação custo-benefício, o desempenho, a confiabilidade e a segurança de seus recursos do Azure.

O painel do Assistente exibe recomendações personalizadas para todas as suas assinaturas. As recomendações são divididas em cinco categorias:

- __Confiabilidade:__ Para garantir e melhorar a continuidade de seus aplicativos críticos de negócios.

- __Segurança:__ Para detectar ameaças e vulnerabilidades que podem levar a violações de segurança.

- __Performance:__ Para melhorar a velocidade dos seus aplicativos. 

- __Custo:__ Para otimizar e reduzir seus gastos gerais com o Azure. 

- __Excelência operacional:__ para ajudar você a atingir eficiência de processo e fluxo de trabalho, capacidade de gerenciamento de recursos e melhores práticas de implantação.

## Integridade do Serviço do Azure

A Integridade do Serviço do Azure é uma coleção de serviços que mantêm você informando sobre o status geral do Azure, status do serviços que podem afetar você e o status do recurso específico que esta afetando você.

O Azure oferece um conjunto de experiências para mantê-lo informado sobre a saúde dos seus recursos de nuvem. Essas informações incluem problemas atuais e futuros, como eventos de impacto de serviço, manutenção planejada e outras alterações que podem afetar sua disponibilidade.

### O Azure Service Health é uma combinação de três serviços menores separados.

O __status do Azure__ informa você sobre interrupções de serviço no Azure na página Status do Azure . A página é uma visão global da integridade de todos os serviços do Azure em todas as regiões do Azure. A página de status é uma boa referência para incidentes com impacto generalizado, mas recomendamos fortemente que os usuários atuais do Azure aproveitem a integridade do serviço do Azure para se manterem informados sobre incidentes e manutenção do Azure.

O __Service Health__ fornece uma visão personalizada do health dos serviços e regiões do Azure que você está usando. Este é o melhor lugar para procurar comunicações que impactam o serviço sobre interrupções, atividades de manutenção planejadas e outros avisos de health porque a experiência autenticada do Service Health sabe quais serviços e recursos você usa atualmente. A melhor maneira de usar o Service Health é configurar alertas do Service Health para notificá-lo por meio de seus canais de comunicação preferidos quando problemas de serviço, manutenção planejada ou outras alterações podem afetar os serviços e regiões do Azure que você usa.

A __integridade do recurso__ fornece informações sobre a integridade dos seus recursos de nuvem individuais, como uma instância de máquina virtual específica. Usando o Azure Monitor, você também pode configurar alertas para notificá-lo sobre alterações de disponibilidade nos seus recursos de nuvem. A integridade do recurso, juntamente com as notificações do Azure Monitor, ajudará você a se manter melhor informado sobre a disponibilidade dos seus recursos minuto a minuto e avaliar rapidamente se um problema é devido a um problema do seu lado ou relacionado a um evento da plataforma Azure.


## Azure Monitor

O Azure Monitor é uma solução de monitoramento abrangente para coletar, analisar e responder a dados de monitoramento de seus ambientes de nuvem e locais. Você pode usar o Azure Monitor para maximizar a disponibilidade e o desempenho de seus aplicativos e serviços. Ele ajuda você a entender como seus aplicativos estão se saindo e permite que você responda manual e programaticamente a eventos do sistema.

![367622370-6e6225fe-3e51-4007-98a6-598a0ee81324](https://github.com/user-attachments/assets/86c04087-0f45-4e15-b77d-6f9875f3c021)

# Conta de Armazenamento na Azure

O Armazenamento do Azure é um serviço gerenciado pela Microsoft que oferece armazenamento em nuvem altamente disponível, seguro, durável, escalonável e redundante. O Armazenamento do Azure inclui Blobs do Azure (objetos), Arquivos do Azure, Filas do Azure, Tabelas do Azure e o Azure Data Lake Storage Gen2. O custo da sua conta de armazenamento depende do uso e das opções escolhidas 

## Nome da conta de armazenamento

- Os nomes da conta de armazenamento devem ter entre 3 e 24 caracteres e podem conter apenas números e letras minúsculas.
- O nome da sua conta de armazenamento deve ser exclusivo no Azure. Duas contas de armazenamento não podem ter o mesmo nome.

## Redundância  de armazenamento 
| Configuração de redundância | Implantação | Durabilidade |
|-----------------------------|-------------|--------------|
| LRS (armazenamento com redundância local) | Datacenter individual na região primária | 11 nines |
| ZRS (armazenamento com redundância de zona) | Três zonas de disponibilidade na região primária | 12 nines |
| GZRS (armazenamento com redundância de zona geográfica) | Três zonas de disponibilidade na região primária e um único datacenter na região secundária | 16 nines |
| RA-GZRS (armazenamento com redundância de zona geográfica acessível para leitura) | Três zonas no primário e um único datacenter no secundário | 16 nines |

### Escolhendo entre LRS e ZRS

A escolha entre LRS (Local Redundant Storage) e ZRS (Zone Redundant Storage) depende das suas necessidades específicas de durabilidade, disponibilidade e custo. Aqui estão alguns pontos para ajudar na decisão:

#### **LRS (Local Redundant Storage)**
- **Implantação**: Armazena três cópias dos seus dados dentro de um único datacenter na região primária.
- **Durabilidade**: 11 nines (99.999999999%) de durabilidade.
- **Uso Ideal**: 
  - Quando os dados não precisam de alta disponibilidade.
  - Para aplicações que podem tolerar a perda de dados em caso de falha do datacenter.
  - Geralmente mais econômico.

#### **ZRS (Zone Redundant Storage)**
- **Implantação**: Armazena três cópias dos seus dados em diferentes zonas de disponibilidade dentro da mesma região.
- **Durabilidade**: 12 nines (99.9999999999%) de durabilidade.
- **Uso Ideal**: 
  - Quando é necessário alta disponibilidade e resiliência a falhas de zona.
  - Para aplicações críticas que não podem tolerar a perda de dados.
  - Pode ser mais caro que LRS, mas oferece maior proteção contra falhas.

#### **Considerações Adicionais**
- **Custo**: LRS é geralmente mais barato que ZRS.
- **Resiliência**: ZRS oferece maior resiliência a falhas de zona, enquanto LRS é suficiente para cenários onde a perda de um datacenter é aceitável.
- **Latência**: LRS pode ter menor latência, pois todas as cópias estão no mesmo datacenter.

### Armazenamento de Blobs do Azure
O Armazenamento de Blobs do Azure é uma solução de armazenamento de objetos da Microsoft para a nuvem. O Armazenamento de Blobs é otimizado para armazenar grandes quantidades de dados não estruturados. Dados não estruturados são dados que não estão de acordo com uma definição ou um modelo de dados específico, como texto ou dados binários.

### Disco do Azure
Os discos gerenciados do Azure são volumes de armazenamento em nível de bloco gerenciados pelo Azure e usados com as Máquinas Virtuais do Azure. Os discos gerenciados são como um disco físico em um servidor local, mas virtualizados. Com discos gerenciados, tudo o que você precisa fazer é especificar o tamanho do disco, o tipo de disco e provisionar o disco. Depois de provisionar o disco, o Azure lida com o resto.

Os tipos de discos disponíveis são ultra discos, unidades de estado sólido (SSD) premium, SSDs padrão e unidades de disco rígido padrão (HDD).

### Armazenamento de Filas do Azure

O armazenamento de Filas do Azure é um serviço usado para armazenar grandes quantidades de mensagens. Você acessa as mensagens em qualquer lugar do mundo por meio de chamadas autenticadas usando HTTP ou HTTPS. Uma mensagem da fila pode ter até 64 KB. Uma fila pode conter milhões de mensagens, até o limite da capacidade total de uma conta de armazenamento.

### Arquivos do Azure
Os Arquivos do Azure oferecem compartilhamentos de arquivos totalmente gerenciados na nuvem que são acessíveis por meio do protocolo SMB, do protocolo NFS (Network File System) e da API REST dos Arquivos do Azure padrão do setor. Os compartilhamentos de arquivos do Azure podem ser montados de maneira simultânea por implantações locais ou na nuvem. É possível acessar os compartilhamentos de Arquivos do Azure do protocolo SMB em clientes Windows, Linux e macOS. 


### Tabela do Azure

O armazenamento de Tabelas do Azure é um serviço que armazena dados estruturados não relacionais (também conhecidos como dados NoSQL estruturados) na nuvem, fornecendo um repositório de chave/atributo com um design sem esquema. Como o armazenamento de Tabelas não tem um esquema, é fácil adaptar seus dados à medida que as necessidades de seu aplicativo evoluem. O acesso aos dados do Armazenamento de Tabelas é rápido e econômico para muitos tipos de aplicativos e normalmente tem um custo mais baixo que o SQL tradicional para volumes de dados semelhantes.

### Pontos de extremidade públicos do serviço de armazamento

| Serviço de armazenamento | Ponto de extremidade público |
|--------------------------|------------------------------|
| Armazenamento de Blobs   | https://storage-account-name.blob.core.windows.net |
| Arquivos do Azure Storage | https://storage-account-name.file.core.windows.net |
| Data Lake Storage Gen2   | https://storage-account-name.dfs.core.windows.net  |
| Armazenamento de Tabelas | https://storage-account-name.table.core.windows.net |

### Camadas de acesso de armazanemnto do Azure

| Frequente | Esporádico | Frio | Arquivo Morto |
|-----------|------------|------|---------------|
| Otimizada para dados acessados com alta frequência. | Otimizada para dados acessados com pouca frequência menos 30 dias. | Otimizado para o armazenamento de dados acessados com pouca frequência menos 90 dias. | Otimizada para dados acessados raramente por pelo menos 180 dias com requisitos de latência flexíveis. |

### Migrações para Azure

As Migrações para Azure fornecem um serviço simplificado de migração, modernização e otimização para o Azure. Todas as etapas de pré-migração, como descoberta, avaliações e dimensionamento correto de recursos locais, estão incluídas em infraestrutura, dados e aplicativos. A estrutura extensível das Migrações para Azure permite a integração de ferramentas de terceiros, expandindo assim o escopo de casos de uso com suporte. Elas fornecem o seguinte:

 - __Plataforma de migração unificada:__ Um único portal para iniciar, executar e acompanhar sua migração para o Azure.
- __Variedade de ferramentas:__ Uma variedade de ferramentas para avaliação e migração. As ferramentas de migrações para Azure incluem as Migrações para Azure: descoberta e avaliação e a Migração e modernização. As Migrações para Azure também integram-se a outros serviços do Azure e a outras ferramentas, bem como com ofertas de ISVs (fornecedores independentes de software).
- __Avaliação, migração e modernização:__ no hub das Migrações para Azure, você pode avaliar, migrar e modernizar:
- __Servidores, bancos de dados e aplicativos Web:__ avaliar servidores locais, incluindo aplicativos web e instâncias do SQL Server e migrá-los para o Azure.
- __Bancos de dados:__ avalie bancos de dados e instâncias locais do SQL Server para migrá-los para um SQL Server em uma VM do Azure ou uma Instância Gerenciada de SQL do Azure ou para um banco de dados SQL do Azure.
- __Aplicativos Web:__ avalie aplicativos Web locais e migre-os para o Serviço de Aplicativo do Azure e para o Serviço de Kubernetes do Azure.
- __Áreas de trabalho virtuais:__ avalie a VDI (Infraestrutura de área de trabalho virtual) local e migre-a para a Área de Trabalho Virtual do Azure.
- __Dados:__ Migre grandes quantidades de dados para o Azure de maneira rápida e econômica usando os produtos Azure Data Box.

### Azure Data Box

O Azure Data Box é uma solução da Microsoft que facilita a transferência de grandes volumes de dados entre seu ambiente local e a nuvem Azure de forma rápida e segura.

#### Como funciona:

1. **Solicitação**: Você solicita um dispositivo Data Box pelo portal do Azure, especificando a quantidade de dados que precisa transferir.
2. **Entrega**: O dispositivo, com capacidade de até 80 TB, é entregue em seu local em uma caixa reforçada.
3. **Configuração**: A configuração é simples e pode ser feita através de uma interface web.
4. **Transferência**: Você copia os dados para o dispositivo ou vice-versa, usando protocolos padrão.
5. **Retorno**: O dispositivo é enviado de volta à Microsoft.
6. **Carregamento na nuvem**: Os dados são carregados automaticamente para o Azure.

#### Benefícios:

- **Velocidade**: Transferências de dados mais rápidas do que métodos tradicionais.
- **Segurança**: Dispositivo com proteção física e criptografia para garantir a segurança dos dados durante o transporte.
- **Facilidade de uso**: Configuração simples e acompanhamento do processo pelo portal do Azure.
- **Custo-benefício**: Uma opção mais econômica para grandes volumes de dados.

__Em resumo__, o Azure Data Box é uma solução ideal para empresas que precisam transferir grandes quantidades de dados para a nuvem Azure de forma eficiente e segura, sem a necessidade de alta largura de banda de internet.

### AzCopy

AzCopy é um utilitário de linha de comando que você pode usar para copiar blobs ou arquivos de ou para uma conta de armazenamento. Este artigo ajuda você a baixar o AzCopy, conectar-se à sua conta de armazenamento e, em seguida, transferir os dados

### Gerenciador de Armazenamento

O Gerenciador de Armazenamento do Microsoft Azure é um aplicativo autônomo que facilita o trabalho com dados do Armazenamento do Azure no Windows, macOS e Linux. Esta ferramenta poderosa permite que você faça upload, download e gerencie blobs, arquivos, filas e tabelas do Armazenamento do Azure, bem como entidades do Azure Data Lake Storage e discos gerenciados do Azure.

#### __Principais Funcionalidades:__
- __Interface Gráfica Intuitiva:__ Oferece uma GUI acessível e rica em recursos para o gerenciamento completo dos recursos de armazenamento em nuvem1.
- __Segurança:__ Acesso seguro aos dados usando o Microsoft Entra ID (anteriormente Azure Active Directory) e permissões de ACL ajustadas1.
- __Extensibilidade:__ Adicione novos recursos e funcionalidades com extensões para atender às suas necessidades específicas de gerenciamento de armazenamento1.
- __Trabalho Offline:__ Permite trabalhar desconectado da nuvem ou offline com emuladores locais, como o Azurite.


## Links Ùteis

Descubra Como Criar Sua Máquina Virtual no Microsoft Azure em Minutos!
https://youtu.be/5axC77gggJI?si=nbnjK9EtwsdgJ1QT

Criar uma máquina virtual do Windows no Azure: https://learn.microsoft.com/pt-br/training/modules/create-windows-virtual-machine-in-azure/ 

Início Rápido: Criar uma máquina virtual do Windows no portal do Azure: https://learn.microsoft.com/pt-pt/azure/virtual-machines/windows/quick-create-portal

Implantar e configurar servidores, instâncias e bancos de dados para o SQL Azure:https://learn.microsoft.com/pt-br/training/modules/azure-sql-deploy-configure/

Como criar banco de dados Azure SQL: https://youtu.be/CIzs7KY3Jl4?si=9v7tsQ5AxVAA7XL4

Gerenciar grupos de recursos do Azure usando o portal do Azure: https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal

Use o Azure Resource Manager: https://learn.microsoft.com/pt-br/training/modules/use-azure-resource-manager/?source=recommendations

O que são zonas de disponibilidade?: https://learn.microsoft.com/pt-br/azure/reliability/availability-zones-overview?tabs=azure-cli

Gerenciar grupos de recursos do Azure usando o portal do Azure: https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal

Use o Azure Resource Manager: https://learn.microsoft.com/pt-br/training/modules/use-azure-resource-manager/?source=recommendations

O que são zonas de disponibilidade?: https://learn.microsoft.com/pt-br/azure/reliability/availability-zones-overview?tabs=azure-cli

Crie uma conta de armazenamento do Azure: https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-create?tabs=azure-portal
Introdução ao Armazenamento de Blobs do Azure: https://learn.microsoft.com/pt-br/azure/storage/blobs/storage-blobs-introduction
Sobre as Migrações para Azure: https://learn.microsoft.com/pt-br/azure/migrate/migrate-services-overview
O que é o Armazenamento de Tabelas do Azure?: https://learn.microsoft.com/pt-br/azure/storage/tables/table-storage-overview
