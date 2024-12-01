STAR THE REPO IF YOURE COOL

jStack - an opinionated stack to ship high-performance, low-cost Next.js apps inspired by the T3 stack.

This is an early-stage stack so probably dont use in production yet. If you're wild enough to do so despite this warning, let me know your website URL so I can feature you lol

documentation coming soon, for now just clone this repo, fill out the .env.example :))

# Set up

1. Fill .env

2. Set up Prisma

生成 prisma 客户端库

`npx prisma generate`

内省数据

`npx prisma db pull`

连接数据库

`npx prisma migrate dev --name init` - 方便版本控制

or

`npx prisma db push` - 直接覆盖，适合早期设计

[Learn in Prisma Doc](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases/install-prisma-client-typescript-postgresql)
