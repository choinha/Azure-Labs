# Microsoft Entra ID e Defender for Cloud

## Microsoft Entra ID

O **Microsoft Entra ID** (antigo Azure Active Directory - AD) é responsável pela gestão de identidades e controle de acesso a recursos, tanto on-premise quanto na nuvem. Ele oferece funcionalidades de autenticação para ambientes híbridos e permite gerenciar permissões de usuários.

### Principais Funcionalidades:
- **Regras e permissões**: Você pode definir o que cada usuário pode fazer em relação a outras contas.
- **Gerenciamento de usuários**: A aba de usuários permite visualizar aqueles que estão em sincronia com o ambiente on-premise e os que não estão.
  - **Aba de Logs**: Permite monitorar atividades, como tentativas de login, localização de login (país), e se o acesso foi feito via portal ou aplicação.
  - **Recuperação de contas**: Usuários excluídos podem ser restaurados em até 30 dias por questões de segurança.
- **SSPR (Self-Service Password Reset)**: Permite configurar um sistema para que os próprios usuários possam recuperar suas senhas sem a intervenção do administrador.
- **Criação e convite de usuários**: É possível criar novos usuários ou convidar usuários existentes para integrarem a conta.
- **Domínios personalizados**: Adicione **custom domain names** para personalizar os e-mails e a identidade dos seus usuários.
- **Download de usuários**: Crie relatórios em formato CSV e faça o download de dados dos seus usuários, facilitando a gestão em grupo.

### SLA e Monitoramento de Saúde
- **Health (SLA)**: O painel de saúde do Entra ID oferece uma visão sobre o nível de serviço, garantindo que os acordos de SLA sejam atendidos.

### Controle de Acesso
- **Access Control (IAM)**: O controle de acesso baseado em funções (RBAC) permite que as permissões sejam herdadas por grupos, facilitando a administração em larga escala.

## Defender for Cloud

O **Microsoft Defender for Cloud** é uma ferramenta que fornece recomendações de segurança para ambientes multicloud e híbridos. Ele permite a conexão com provedores de nuvem diferentes, além do Azure, e oferece insights sobre a postura de segurança de máquinas virtuais, serviços, e muito mais.

### Principais Funcionalidades:
- **Análise de segurança**: Oferece recomendações baseadas em avaliações da segurança do seu ambiente, atribuindo uma pontuação (Security Score).
- **Aplicação Nativa de Nuvem**: Para todas as contas configuradas no ambiente de nuvem, o Defender for Cloud fornece recomendações automaticamente.
- **Multicloud e Híbrido**: Suporta a gestão de segurança em múltiplos provedores de nuvem.
- **Integração com DevOps**: Possui o **DevOps Security**, onde você pode conectar suas contas do GitHub, GitLab, ou Azure DevOps. Ele fornece alertas e recomendações de melhorias para o código e pipelines.
- **Alertas e Notificações**: Configuração de alertas via e-mail, Microsoft Teams, ou Slack, para notificações em tempo real sobre vulnerabilidades ou incidentes.
- **Monitoramento de Máquinas**: Valida o estado de segurança das máquinas virtuais, identificando possíveis vulnerabilidades e garantindo que as melhores práticas sejam seguidas.
  
### Planos e Custos:
- **Foundation CSPM**: O único nível gratuito do Defender for Cloud, que oferece monitoramento básico e recomendações de segurança. Outros recursos avançados são pagos.

### Ferramentas de Segurança Complementares:
- **Validador de Segurança**: Fornece uma visão completa da postura de segurança e possíveis melhorias.
- **Relatórios e Painéis**: Mostra o estado da segurança em um painel unificado, permitindo uma visão clara de pontos de melhoria.

## Links úteis
- [Documentação do Microsoft Entra ID](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-whatis)
- [Documentação do Microsoft Defender for Cloud](https://learn.microsoft.com/pt-br/azure/defender-for-cloud/defender-for-cloud-introduction)

