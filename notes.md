# Notes

> notes taken during the course


```bash
npm install -g @nestjs/cli
nest new project-name
```

```bash
npm run start:dev
```

http://localhost:3000/

```bash
nest g resource
events
REST API
Y
```

## Docker

```bash
docker compose up
```

```bash
docker compose exec db bash
mysql -uroot -proot
show databases;
```

## Prisma

```bash
npx prisma init
```

Afer creating and configuring the `schema.prisma`, and `.env` files:

```bash
npx prisma migrate dev
```

Verify table on db container:
```bash
use nest;
show tables;
describe Event;
```

Generate Prisma module:
```bash
nest g module prisma
```

Generate Prisma service:
```bash
nest g service prisma
```

