# Gerenciamento e Governança no Azure

## Azure Policy

### Definição
O **Azure Policy** é uma ferramenta essencial para impor padrões e garantir a conformidade dos recursos em sua organização. Ele permite a aplicação de regras que se sobrepõem a permissões individuais, criando uma governança robusta. 

### Exemplo
Imagine que sua empresa está adotando recursos na nuvem e os colaboradores estão se acostumando. Um novo projeto surge, e um técnico avalia a região e a família de máquinas apropriadas. Porém, a política da empresa exige que uma região específica seja bloqueada. Neste caso, o **Azure Policy** impede que recursos sejam criados fora das regiões permitidas, aplicando o padrão organizacional independentemente de quem esteja criando os recursos.

### Benefícios
- **Conformidade**: A política aplicada garante que todos os recursos sigam os padrões estabelecidos pela organização.
- **Governança**: Ajuda na governança, pois impede que alguém passe por cima das regras impostas.
- **Condições Flexíveis**: As políticas podem ser criadas e deixadas desativadas, sendo ativadas quando necessário.

## Bloqueios de Recursos

### Definição
Os bloqueios de recursos no Azure são usados para garantir que determinados recursos ou grupos de recursos não sejam alterados ou excluídos inadvertidamente. Isso é crucial para proteger recursos críticos da organização.

### Exemplos de Bloqueios
- **Bloqueios a Nível de Grupo de Recursos**: Ao aplicar um bloqueio em um grupo de recursos, todos os recursos contidos nele herdam o bloqueio.
- **Leitura-Only**: O bloqueio de leitura apenas permite visualização dos recursos, prevenindo alterações.

### Benefícios
- **Proteção de Recursos**: Evita alterações acidentais ou exclusão de recursos importantes.
- **Conformidade**: Reforça a conformidade ao garantir que todas as aplicações estão protegidas.

## Microsoft Purview

### Definição
O **Microsoft Purview** é uma ferramenta mais recente no portfólio do Azure, voltada para a governança, gerenciamento de risco e conformidade de dados. Ele oferece uma visão integrada e abrangente sobre a gestão de dados, ajudando as empresas a manterem-se em conformidade com leis e regulamentos, como a LGPD no Brasil.

### Benefícios
- **Gerenciamento de Governança**: Ajuda a identificar e gerenciar dados sensíveis e regulamentados.
- **Compliance e Risco**: Fornece insights sobre a conformidade da organização, ajudando a identificar áreas que não estão de acordo com as regulamentações.
- **Integração**: Atua como uma switch de aplicações para governança de dados.

## Portal de Confiança do Serviço

### Definição
O **Portal de Confiança da Microsoft** (Service Trust Portal) é onde se encontram documentos aplicáveis à conformidade e regulamentos da Microsoft, ajudando a auditar e assegurar que os serviços em nuvem seguem as leis vigentes.

### Acesso
Acesse o portal em: [servicetrust.microsoft.com](https://servicetrust.microsoft.com/).

---

Essa política e as ferramentas de governança como o **Microsoft Purview** e os bloqueios de recursos garantem que sua organização siga as melhores práticas de conformidade e proteção de dados.
