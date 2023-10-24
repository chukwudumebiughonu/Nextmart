Create application with : npx create-next-app@latest

Follow the instructions: here

Ok to proceed? (y) y
✔ What is your project named? … nextmart
✔ Would you like to use TypeScript? … No / Yes
✔ Would you like to use ESLint? … No / Yes
✔ Would you like to use Tailwind CSS? … No / Yes
✔ Would you like to use `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to customize the default import alias (@/*)? … No / Yes

Install the following dependencies and packages with: npm i daisyui prisma @prisma/client next-auth @auth/prisma-adapter prettier eslint-config-prettier prettier-plugin-tailwindcss

Install zod with: npm i zod  

Setup mogodb atlas

Initialize prisma with: npx prisma init

setup this command in the .env file: DATABASE_URL="mongodb+srv://chukwudumebi:sURI0Ad9ctTBBIaq@cluster0.bmtirwt.mongodb.net/nextmart?retryWrites=true&w=majority"

Change the name of the datasource provider in the prisma schmema to mongodb if it is used

Use the command to generate schema with the prisma: npx prisma db pull a

After editing the prisma schema run the following command: npx prisma db push

After  that run dthe following command: npx prisma generate

Configure prisma in the lib/db/prisma.ts file path   