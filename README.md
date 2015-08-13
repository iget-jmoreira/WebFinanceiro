# WebFinanceiro

### WebFinanceiro – Funcionalidades
- CRUD de usuários (users)
 - Empresas são usuários

- CRUD de produtos (products)
 - Cada produto gera uma movimentação
 - Cada movimentação será contabilizadade em payment ou receipt

- Contas a pagar (payment)
 - Toda movimentação que o usuário perde dinheiro

- Contas a receber (receipt)
 - Toda movimentação que o usuário ganha dinheiro

### WebFinanceiro – Funcionamento
- Todo usuário se comunica com sua contabilidade por meio de uma relação, no caso de uma empresa, todos da mesma empresa se comunicam com a mesma contabilidade.
- Cada relação será uma tabela que tem um id, um supervisor_id que no caso de uma empresa será o dono da empresa e conterá um text (nullable) com um array de ids, referente aos funcionarios, caso não seja empresa será null.
