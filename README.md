Backend (/server)
Navigate to the server directory: cd server

Install dependencies: npm install

Set up your .env file with your DATABASE_URL.

Run database migrations: npx prisma migrate dev

(Optional) Seed the database: npm run seed

Start the server: npm run dev

Frontend (/frontend)
Navigate to the frontend directory: cd frontend

Install dependencies: npm install

Set up your .env.local file with VITE_API_URL=http://localhost:5000/api.

Start the client: npm run dev

Test Credentials
Email: test@erino.io

Password: Test_1234