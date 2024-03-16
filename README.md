# To run this project

```npm install```

Step for this project 

1. npm install prisma --save dev 
2. npx prisma init
3. change .env DATABASE_URL to "file:./dev.db"
4. change provider to sqlite
5. run `npm i --save @nestjs/config` to enable access to env file
6. run `npx prisma migrate dev --name init` to make table for user
7. make prisma service, run `npm install @prisma/client`