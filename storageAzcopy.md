# Contas de Armazenamento no Azure

As contas de armazenamento do Azure permitem armazenar diferentes tipos de dados, como:
- **Blobs**
- **Files**
- **Filas (Queues)**
- **Tabelas (Tables)**

## Configuração da Conta de Armazenamento

Para criar uma conta de armazenamento, algumas configurações são necessárias:
- **Assinatura**: Definir a assinatura do Azure.
- **Grupo de recursos**: Selecionar ou criar um grupo de recursos.
- **Nome da conta de armazenamento**: Deve ser único, com 3 a 24 caracteres.

## Desempenho
Existem duas principais opções de desempenho:
- **Standard**: Recomendado para uso geral. O custo é baseado no uso.
- **Premium**: Recomendado para aplicações que exigem baixa latência, como bancos de dados. Mesmo sem uso ativo, ele gera custos por utilizar discos performáticos.

## Redundância
A redundância define como os dados são replicados para garantir alta disponibilidade:
- **LRS (Locally Redundant Storage)**: Mantém três cópias dos dados no mesmo datacenter. Não é indicado para ambientes produtivos.
- **GRS (Geo-Redundant Storage)**: Mantém uma cópia adicional em uma região secundária para maior resiliência.
- **ZRS (Zone-Redundant Storage)**: Armazena três cópias dos dados, cada uma em datacenters diferentes na mesma região.
- **GZRS (Geo-Zone-Redundant Storage)**: Combina a estratégia do GRS com o ZRS, replicando os dados entre zonas na origem e mantendo uma cópia adicional em outra região.

## Migração para Azure
A migração de servidores, bancos de dados e aplicativos web para o Azure pode ser feita utilizando ferramentas específicas como:
- **Ferramenta de avaliação**
- **Ferramenta de migração**

## AzCopy
A ferramenta **AzCopy** permite transferir dados de e para contas de armazenamento no Azure, funcionando em vários sistemas operacionais. Para utilizá-la, siga os seguintes passos:
1. Acesse a conta de armazenamento.
2. Configure containers.
3. Gere um token SAS (Shared Access Signature).
4. Defina permissões para o token.
5. Utilize a URL SAS do blob para realizar as transferências.

Mais informações podem ser encontradas na [documentação oficial](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10?tabs=dnf).

## Links úteis
- [Ferramentas de migração no Azure](https://azure.microsoft.com/pt-br/services/azure-migrate/)
- [Documentação sobre redundância no armazenamento](https://learn.microsoft.com/pt-br/azure/storage/common/storage-redundancy)

