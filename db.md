# Formas de acessar o Banco de Dados

- SQL - Forma mais básica -- Mais complexa
  select \* from cidade

- Query Builder
  knex('cidade').select('\*')
  knex('cidade').insert({nome: 'Caxias'})

- ORM
