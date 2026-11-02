# learn_nodejs

## Techstack: NodeJS, NextJS, PostgreSQL

## Setup
### Cài NodeJS (LTS)
```bash
Link: https://nodejs.org/en/download
```

### Khởi tạo file cấu hình
```bash
npm init -y
```

### Cài Express
```bash
npm install express dotenv
```

### Cài dependency
```bash
npm install -D tsx typescript @types/node @types/express nodemon
```

### Tạo cấu hình TS
```bash
npx tsc --init
```

### Cài Prisma
```bash
# devDependencies
npm install -D prisma@7

# runtime
npm install @prisma/client@7

npm install @prisma/adapter-pg pg

# Khởi tạo thư mục Prisma
npx prisma init --datasource-provider postgresql

# Chạy migration
npx prisma migrate dev --name init

# Tạo module trong db
npx prisma generate

# Cập nhật schema
npx prisma migrate

# Trực quan hóa dữ liệu
npx prisma studio
```

# Cài Zod (Validate dữ liệu)
```bash
npm install zod
```
