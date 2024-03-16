# To run this project

```npm install```

# Step for this project 

1. `npm i -g @nestjs/cli`
2. `nest new auth-nest`
3. npm install prisma --save dev 
4. npx prisma init
5. change .env DATABASE_URL to `file:./dev.db`
6. change provider to sqlite
7. run `npm i --save @nestjs/config` to enable access to env file
8. run `npx prisma migrate dev --name init` to make table for user
9. make prisma service, run `npm install @prisma/client`
10. run `nest g mo user`, `nest g s user` and `nest g co user` to create complete module
11. making dto we need install `npm i @nestjs/mapped-types`, `npm i class-validator` and `npm i class-transformer` 
12. hashing password `npm i bcrypt`
13. to generate jwt token `npm i @nestjs/jwt`

# Good to know 
`npx prisma studio` to view the collection