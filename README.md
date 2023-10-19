# CRUD-mysql-Prisma-
Basic Crud operation is performed using Prisma,mySQL,SWR,React,Express,Node.js,Tailwind CSS
## After clonning
### Both server and client run
```
npm i
```
## Connect to Mysql
### create .env file in server folder
```
APP_PORT=8000
DATABASE_URL="mysql://username:password@localhost:3306/crudprisma"
```
## Also setup tailwind
```
npm install -D tailwindcss
npx tailwindcss init
```
### In tailwind.config.js file
```
content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
```
