🧠 caseMania
A full-stack case management system built with Next.js, Prisma, Tailwind CSS, and shadcn/ui. caseMania allows users to sign up, log in, and manage their personal cases with CRUD capabilities — all using a clean and modern UI.

🚀 Tech Stack
Layer	Stack/Library	Purpose
Frontend	Next.js (App Router)	React-based frontend framework
Styling	Tailwind CSS + shadcn/ui	Utility-first styling & components
Forms	react-hook-form + zod	Form state management + validation
Icons	lucide-react	Beautiful icon library
Backend	Next.js API routes	Serverless backend
ORM	Prisma	Type-safe database ORM
Database	PostgreSQL (via Prisma)	Relational database
Auth	Custom (username/email)	User authentication system

📁 Folder Structure
graphql
Copy
Edit
caseMania/
├── app/                  # Next.js App Directory
│   ├── api/              # API routes (CRUD for Case/User)
│   ├── dashboard/        # Protected user dashboard
│   ├── login/            # Login page and logic
│   ├── register/         # Register page and logic
│   └── layout.tsx        # Shared layout component
│
├── components/           # Reusable UI components
├── lib/                  # Server-side helpers (auth, Prisma client)
├── prisma/               # Prisma schema + seed files
├── styles/               # Tailwind CSS and global styles
├── .env.example          # Environment variable setup
├── package.json          # Dependencies and scripts
└── README.md             # You're here!
⚙️ Setup Instructions
Clone the repo

bash
Copy
Edit
git clone https://github.com/allan-osei/caseMania.git
cd caseMania
Install dependencies

bash
Copy
Edit
npm install
Set up environment variables

Create a .env file based on .env.example:

ini
Copy
Edit
DATABASE_URL=postgresql://your_postgres_url
Push schema to database

bash
Copy
Edit
npx prisma db push
Start development server

bash
Copy
Edit
npm run dev
🧪 Prisma Commands (Quick Reference)
Command	Purpose
npx prisma db push	Sync schema to DB without migration
npx prisma migrate dev --name init	Create and apply a migration
npx prisma studio	Launch Prisma GUI to inspect DB
npx prisma db seed	Seed the database
npx prisma generate	Regenerate Prisma client

🧰 UI/UX Features
🔐 Auth-protected routes

📄 Dashboard showing user-specific cases

➕ Add/Edit/Delete cases

🧼 Clean, componentized UI with shadcn/ui

✅ Form validation using zod and react-hook-form

🔮 Future Improvements
OAuth authentication (Google, GitHub)

Role-based access control

Tagging or categorizing cases

Search & filter functionality

Notifications or activity log

📸 Screenshots
![Screenshot (1)](https://github.com/user-attachments/assets/45691f3a-2c1e-4350-8f94-bf582e3fce66)



🧑‍💻 Author
Built by Allan Osei
