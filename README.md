# projeto-gestao-producao

## Banco de dados

O banco SQLite está em `database/producao_db.sqlite`. Ele contém a tabela
`producao`, com as colunas:

| Coluna | Tipo | Descrição |
| --- | --- | --- |
| `id` | INTEGER | Chave primária autoincrementada |
| `setor` | TEXT | Setor de produção |
| `pecas_produzidas` | INTEGER | Quantidade de peças produzidas |
| `pecas_rejeitadas` | INTEGER | Quantidade de peças rejeitadas |
| `custo_unitario` | REAL | Custo unitário |