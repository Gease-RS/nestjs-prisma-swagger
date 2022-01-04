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
http://localhost:3000
http://localhost:3000/api
```

3. Instale o Prisma

```bash
npm i -D prisma

npx prisma init --datasource-provider sqlite

npm install @prisma/client

```

4. Rode a Migrate

```bash
npx prisma migrate dev --name product
```

5. Configure o package.json o script abaixo e rode a Seed

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

6. Use o generator do Nest para gerar um module

```bash
nest generate module prisma
```

7. Use o generator do Nest para gerar um service

```bash
nest g s prisma
```

8. Use o generator do Nest para gerar um resource

```bash
nest generate resource products
```
