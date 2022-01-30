## O processo de modelagem de dados:
1. Levantamento de requisitos
2. Modelagem de Dados Conceituais
3. Modelagem de Dados Lógicos

## Recurso importante do RDBMS:
**Atomicidade** - Toda a transação ou nada é processado
**Consistência** - Somente transações que obedecem a restrições e regras são gravadas no banco de dados
**Isolamento** - As transações ocorrem de forma independente e segura
**Durabilidade** - Depois que as transações são confirmadas, elas permanecem confirmadas

## Quando usar Banco de Dados Relacional?
### Vantagens de usar um banco de dados relacional
* Flexibilidade para escrever em consultas SQL: Com SQL sendo a linguagem de consulta de banco de dados mais comum.
* Modelando os dados não modelando consultas
* Capacidade de fazer JOINS
* Capacidade de fazer agregações e análises
* Índices secundários disponíveis: Você tem a vantagem de poder adicionar outro índice para ajudar na busca rápida.
* Volumes de dados menores: Se você tiver um volume de dados menor (e não big data), poderá usar um banco de dados relacional por sua simplicidade.
* Transações ACID: Permite atender a um conjunto de propriedades de transações de banco de dados destinadas a garantir a validade mesmo em caso de erros, falhas de energia e, assim, manter a integridade dos dados.
* Mais fácil de mudar para os requisitos de negócios

## Quando usar o banco de dados NoSQL?
### Vantagens de usar um banco de dados NoSQL
* Necessidade de armazenar diferentes formatos de tipos de dados: NoSQL também foi criado para lidar com diferentes configurações de dados: dados estruturados, semiestruturados e não estruturados. Documentos JSON e XML podem ser manipulados facilmente com NoSQL.
* Grandes quantidades de dados: Bancos de dados relacionais não são bancos de dados distribuídos e por isso eles só podem escalar verticalmente adicionando mais armazenamento na própria máquina. Os bancos de dados NoSQL foram criados para serem escaláveis ​​horizontalmente. Quanto mais servidores/sistemas você adicionar ao banco de dados, mais dados poderão ser hospedados com alta disponibilidade e baixa latência (leituras e gravações rápidas).
* Precisa de escalabilidade horizontal: A escalabilidade horizontal é a capacidade de adicionar mais máquinas ou nós a um sistema para aumentar o desempenho e o espaço para dados
* Precisa de alta taxa de transferência: Embora as transações ACID tragam benefícios, elas também retardam o processo de leitura e gravação de dados. Se você precisar de leituras e gravações muito rápidas, o uso de um banco de dados relacional pode não atender às suas necessidades.
* Precisa de um esquema flexível: O esquema flexível pode permitir a adição de colunas que não precisam ser usadas por todas as linhas, economizando espaço em disco.
* Precisa de alta disponibilidade: bancos de dados relacionais têm um único ponto de falha. Quando esse banco de dados fica inativo, um failover para um sistema de backup deve ocorrer e leva tempo.
