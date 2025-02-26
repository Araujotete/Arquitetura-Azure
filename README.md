# Arquitetura Azure
## Resumo sobre aprendizado da arquitetura do Azure

Componentes de arquitetura do Azure

A arquitetura do Microsoft Azure é um framework robusto e flexível projetado para suportar uma ampla gama de serviços de computação em nuvem.
O Azure é baseado em uma infraestrutura global de data centers distribuídos em diversas regiões ao redor do mundo, o que permite baixa latência e alta disponibilidade. Sua arquitetura é dividida em camadas principais:
- Infraestrutura Física: Inclui os data centers, servidores, redes e sistemas de armazenamento. Esses recursos são gerenciados pela Microsoft e virtualizados para oferecer escalabilidade e resiliência.
1.	Camada de Virtualização: Usa tecnologias como o Hyper-V para criar máquinas virtuais (VMs) e contêineres, permitindo que os usuários rodem sistemas operacionais e aplicações de forma isolada e eficiente.
2.	Serviços de Plataforma: Aqui entram os serviços principais do Azure, organizados em categorias como:
o	Computação: Azure Virtual Machines, Azure Kubernetes Service (AKS) e Azure Functions para processamento serverless.
o	Armazenamento: Blob Storage, Disk Storage e Azure Files para dados estruturados e não estruturados.
o	Redes: Virtual Network (VNet), Load Balancer e Azure CDN para conectividade e distribuição.
o	Bancos de Dados: Azure SQL, Cosmos DB (multimodelo e globalmente distribuído) e outros serviços gerenciados.
o	IA e Análise: Ferramentas como Azure Machine Learning e Synapse Analytics para insights de dados.
3.	Gerenciamento e Segurança: Ferramentas como Azure Active Directory (para identidade e acesso), Azure Monitor (telemetria) e Azure Security Center garantem controle, visibilidade e proteção dos recursos.
4.	Modelo de Entrega: O Azure opera nos formatos IaaS (Infraestrutura como Serviço), PaaS (Plataforma como Serviço) e SaaS (Software como Serviço), permitindo desde o controle total de VMs até soluções prontas sem gerenciamento de infraestrutura.

A arquitetura é altamente modular, baseada em microsserviços, e suporta integração com ferramentas de DevOps (como CI/CD via Azure DevOps) e tecnologias de código aberto. Isso a torna ideal tanto para empresas que querem migrar sistemas legados quanto para quem desenvolve aplicações nativas na nuvem.


