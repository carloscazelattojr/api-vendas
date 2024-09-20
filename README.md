# api-vendas

Api de vendas desenvolvido em NodeJS

Comando para entrar no psql

```
psql --host=localhost --username=postgres --port=5432 apivendas
```

Comando para criar migrations:

```
npm run typeorm -- migration:create -n CreateTableProducts
```

Comando para rodar migrations:

```
npm run typeorm migration:run
```
