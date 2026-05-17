# Flownix

### A powerful no-code automation platform that effortlessly automates and streamlines your business workflows.

## To run the development server:

```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## To create the database:

Local Database (runs Postgres locally in your terminal):
```bash
npx prisma dev 
```

Cloud (creates a free Prisma Postgres database):
```bash
npx create-db
```

## To create the database tables and generate Prisma Client:

```bash
npx prisma migrate dev --name init
```

## To Open Prisma Studio

```bash
npx prisma studio
```
Open [http://localhost:5555](http://localhost:5555) with your browser to see the result.




