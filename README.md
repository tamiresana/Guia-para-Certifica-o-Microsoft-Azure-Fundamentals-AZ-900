# Guia-para-Certifica-o-Microsoft-Azure-Fundamentals-AZ-900

Este repositório contém um guia com os principais tópicos, dicas e recursos para quem está se preparando para a certificação **Microsoft Azure Fundamentals (AZ-900)**. A prova AZ-900 é ideal para quem deseja aprender os conceitos básicos do Azure, independentemente de experiência técnica.

## 📘 O que é a certificação AZ-900?

A **certificação AZ-900** valida o conhecimento fundamental sobre serviços em nuvem e o Azure. Ela aborda:

- Conceitos de nuvem
- Serviços principais do Azure
- Segurança e conformidade no Azure
- Modelos de precificação e SLAs (Acordos de Nível de Serviço) do Azure

### Pré-requisitos:
Nenhum conhecimento prévio sobre o Azure é necessário, mas uma familiaridade básica com conceitos de TI pode ser útil.

## 🔖 Estrutura do Exame

O exame está dividido em quatro grandes áreas de conhecimento:

1. **Conceitos de Nuvem (15-20%)**
   - Benefícios e modelos de computação em nuvem (IaaS, PaaS, SaaS)
   - Principais conceitos como escalabilidade, elasticidade e alta disponibilidade

2. **Serviços Centrais do Azure (30-35%)**
   - Conhecimento sobre serviços como VMs, redes virtuais, armazenamento, Azure App Service e Azure Kubernetes Service (AKS)

3. **Segurança, Privacidade e Conformidade no Azure (25-30%)**
   - Proteção de dados, Azure Firewall, Azure Policy, RBAC (controle de acesso baseado em funções)

4. **Preços e SLAs (20-25%)**
   - Preços baseados em consumo, calculadoras de custo e serviços gratuitos do Azure

## 🛠️ Ferramentas e Recursos Recomendados

### Documentação Oficial

- [Microsoft Learn - AZ-900 Learning Path](https://learn.microsoft.com/en-us/certifications/exams/az-900): Guia oficial com módulos interativos.
- [Guia de Estudo da Certificação AZ-900](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/): Página oficial da certificação com informações sobre o exame.


## ☁️ Máquinas Virtuais (VMs) no Azure

As **Máquinas Virtuais (VMs)** no Azure oferecem:

- **Escalabilidade**: Aumente ou diminua o tamanho conforme a demanda.
- **Imagens Personalizadas**: Use imagens pré-configuradas ou crie as suas.
- **Gerenciamento Fácil**: Monitoramento, recuperação de desastres e atualizações automáticas.
- **Alta Disponibilidade**: Use *Availability Sets* e *Availability Zones* para garantir redundância e continuidade em caso de falhas.

[Documentação de VMs no Azure](https://learn.microsoft.com/en-us/azure/virtual-machines/)

---

## 📦 Armazenamento no Azure

O Azure oferece várias opções de armazenamento para diferentes cenários:

- **Blob Storage**: Ideal para grandes volumes de dados não estruturados (ex: imagens, vídeos).
- **Disk Storage**: Armazenamento de discos gerenciados, ideal para cargas de trabalho intensivas em IOPS.
- **File Storage**: Sistema de arquivos compartilhado acessível via protocolo SMB.
- **Queue Storage**: Comunicação assíncrona para processamento de mensagens.
- **Table Storage**: Armazenamento NoSQL para dados semi-estruturados.

### Benefícios:
- **Alta Disponibilidade e Durabilidade**: Replicação automática dos dados para garantir redundância.
- **Segurança**: Criptografia de dados em repouso e em trânsito.
- **Escalabilidade**: Ajuste automático conforme as necessidades de armazenamento.


## 💡 Dicas para Otimizar Custos no Azure

1. **Uso de Níveis Gratuitos**: Aproveite os serviços no Azure que oferecem camadas gratuitas (ex: VMs e armazenamento).

2. **Reserva de Instâncias**: Economize até 72% com instâncias reservadas para VMs e outros serviços de longo prazo.

3. **Autoescala**: Configure a autoescala para ajustar automaticamente os recursos com base na demanda, evitando sobrecarga desnecessária.

4. **Uso de Calculadoras de Custo**: Utilize a [Calculadora de Preços do Azure](https://azure.microsoft.com/en-us/pricing/calculator/) para estimar custos e ajustar recursos.

5. **Monitoramento com Azure Cost Management**: Monitore e controle o consumo de recursos e orçamento com o [Azure Cost Management](https://azure.microsoft.com/en-us/services/cost-management/).

6. **Desligamento Automático de VMs**: Programe o desligamento de VMs quando não estiverem em uso, como fora do horário comercial.

   

## 🔒 Gerenciando Políticas de Acesso no Azure

1. **Azure Policy**: Use para criar, atribuir e gerenciar políticas que garantem a conformidade de recursos com regras definidas.

2. **Controle de Acesso Baseado em Função (RBAC)**: Gerencie permissões detalhadas de usuários e grupos, atribuindo papéis específicos para limitar o acesso a recursos.

3. **Políticas de Bloqueio**: Implemente bloqueios de leitura ou exclusão para proteger recursos críticos contra alterações acidentais.

4. **Identidade Gerenciada**: Simplifique a autenticação e acesso aos serviços Azure sem gerenciar credenciais.

5. **Azure Active Directory (AAD)**: Centralize a autenticação e gerencie identidades para usuários e aplicativos de forma segura.

6. **Monitoramento de Acesso**: Utilize o Azure Monitor e o Azure Security Center para rastrear e revisar atividades de acesso.



## 🚀 Ferramentas de Implantação na Azure

1. **Azure DevOps**: Plataforma completa para CI/CD (Integração Contínua e Entrega Contínua) que facilita a automação de pipelines de build, teste e implantação.

2. **GitHub Actions**: Automatize fluxos de trabalho diretamente no GitHub para implantar aplicações no Azure de forma integrada.

3. **Azure Resource Manager (ARM)**: Use templates JSON para definir e implantar recursos na Azure de maneira consistente e automatizada.

4. **Terraform**: Ferramenta de código aberto para infraestrutura como código (IaC) que permite implantar e gerenciar recursos Azure.

5. **Azure CLI**: Interface de linha de comando para automatizar a criação, gerenciamento e implantação de recursos na Azure.

6. **Azure PowerShell**: Ferramenta baseada em scripts para gerenciar e implantar serviços Azure diretamente no PowerShell.

   

## 📊 Monitoramento Inteligente com Azure

1. **Azure Monitor**: Centralize o monitoramento de desempenho e integridade dos recursos Azure, coletando métricas e logs.

2. **Application Insights**: Monitore aplicações em tempo real, analisando desempenho, falhas e uso, permitindo uma resposta rápida a problemas.

3. **Log Analytics**: Analise e visualize dados de logs com consultas personalizadas, facilitando a identificação de tendências e problemas.

4. **Alerts e Notificações**: Configure alertas para eventos e condições específicas, garantindo que as equipes sejam notificadas imediatamente sobre problemas críticos.

5. **Azure Security Center**: Monitore e gerencie a segurança dos recursos Azure, identificando vulnerabilidades e recomendações de conformidade.

6. **Workbooks**: Crie relatórios personalizados e dashboards para visualizar e compartilhar insights de monitoramento de forma interativa.



## 📎 Links Úteis
- [Microsoft Learn - AZ-900 Learning Path](https://learn.microsoft.com/en-us/certifications/exams/az-900)
- [Simulados Whizlabs AZ-900](https://www.whizlabs.com/microsoft-azure-certification/az-900/)
- [Exame de Certificação AZ-900](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)
- [Documentação de Armazenamento no Azure](https://learn.microsoft.com/en-us/azure/storage/)
- [Guia Oficial para Redução de Custos no Azure](https://learn.microsoft.com/en-us/azure/cost-management-billing/)
- [Documentação Oficial de Gerenciamento de Políticas no Azure](https://learn.microsoft.com/en-us/azure/governance/policy/)
- [Documentação Oficial de Ferramentas de Implantação no Azure](https://learn.microsoft.com/en-us/azure/devops/?view=azure-devops)
- [Documentação Oficial sobre Monitoramento no Azure](https://learn.microsoft.com/en-us/azure/monitoring/)
