## Banco de Dados SQL no Azure Portal 
Ao criar um banco de dados SQL no Azure, é necessário criar um servidor SQL simbólico, é simbólico porque ele não representa um servidor físico único ou dedicado, mas sim uma instância lógica que agrupa e gerencia os bancos de dados SQL. 
O servidor é a "casa" onde o banco de dados vai residir, fornecendo a configuração necessária para conectividade, autenticação e gerenciamento.

## Por que criar o servidor simbólico?
O servidor simbólico é necessário para gerenciar configurações de conexão (como endereço IP e portas), autenticação de usuários e outras opções administrativas, como backup, segurança e replicação. 
Mesmo que o banco de dados seja o foco, o servidor é onde essas configurações são feitas e aplicadas.
Ele também é importante para gerenciar várias bases de dados em um único ponto de administração, já que um servidor SQL no Azure pode hospedar mais de um banco de dados ao mesmo tempo.

## Autenticação SQL:
A autenticação SQL permite que você acesse o banco de dados usando um usuário e uma senha definidos durante a criação do servidor. Essa autenticação é independente do Active Directory, o que é útil para cenários onde o controle de acesso precisa ser mais restrito ou separado do ambiente de trabalho usual.
Ao usar a autenticação SQL, você pode definir usuários específicos do banco de dados com permissões específicas, aumentando a segurança.

## Modelo de Redundância e SLA:
O Azure oferece diferentes níveis de redundância geográfica e de zona para proteger seus dados contra falhas. 
Dependendo do nível de redundância escolhido, o SLA (Acordo de Nível de Serviço) pode garantir até 99,99% de disponibilidade, o que significa que seu banco de dados terá pouquíssimas interrupções.

Quando você opta por modelos mais gerenciados de IaaS, como o SQL Server em Máquinas Virtuais (VMs), você tem maior controle sobre o sistema operacional, as configurações do servidor, e outras partes da infraestrutura. No entanto, isso exige mais gerenciamento e atenção, como manutenção de atualizações, backups, e gerenciamento do ambiente.

O Azure SQL Database segue o modelo SaaS, onde a plataforma gerencia a maioria dos aspectos operacionais, como backups automáticos, atualizações de software, escalabilidade e segurança. Isso significa que o usuário se concentra apenas no banco de dados e nas aplicações, sem precisar se preocupar com a infraestrutura subjacente, oferecendo menos dor de cabeça em termos de gerenciamento.
