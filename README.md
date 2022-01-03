## COMANDOS

Clone o repositório ou faça Download

1. Clone o repositório com o script inicial

```bash
# SSH
git clone git@github.com:marcjulian/nestjs-prisma-workshop.git

ou

# HTTPS
git clone https://github.com/marcjulian/nestjs-prisma-workshop.git

```

2. Instale as dependências

```bash
cd nestjs-prisma-workshop
npm install

npm run start:dev
```

```bash
npm i -D prisma

npx prisma init --datasource-provider sqlite

npm install @prisma/client

npx prisma migrate dev --name product

npx prisma db seed --preview-feature
```

Adicione no package.json o script abaixo

"prisma": {
"seed": "ts-node prisma/seed.ts"
},

```bash
npx prisma db seed
```

```bash
npx prisma studio

http://localhost:5555/
```

```bash
nest generate module prisma
```

```bash
nest g s prisma
```

```bash
npm run start:dev

```

```bash
nest generate resource products
```
