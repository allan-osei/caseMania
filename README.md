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

🧪 Prisma Commands (Quick Reference)
Command	Purpose
| Command                              | Purpose                             |
| ------------------------------------ | ----------------------------------- |
| `npx prisma db push`                 | Sync schema to DB without migration |
| `npx prisma migrate dev --name init` | Create and apply a migration        |
| `npx prisma studio`                  | Launch Prisma GUI to inspect DB     |
| `npx prisma db seed`                 | Seed the database                   |
| `npx prisma generate`                | Regenerate Prisma client            |


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
![Screenshot (12)](https://github.com/user-attachments/assets/5063f23c-da67-480f-8b44-1b0d82bf5ca0)
![Screenshot (11)](https://github.com/user-attachments/assets/bc79843e-db73-4e4e-b61e-b178dd732a5e)
![Screenshot (10)](https://github.com/user-attachments/assets/fa9a1c04-6ddc-4977-b823-927a2713df42)
![Screenshot (9)](https://github.com/user-attachments/assets/6cde000c-4f44-46c2-a09d-62b6795d0af9)
![Screenshot (8)](https://github.com/user-attachments/assets/091377dd-7d00-4254-bbf2-a9103bb0eaec)
![Screenshot (7)](https://github.com/user-attachments/assets/b39bed54-ae8c-402a-a26c-021b7b5d5fad)
![Screenshot (6)](https://github.com/user-attachments/assets/7b1c2f00-dfd3-4bc8-90d6-a1dffc033904)
![Screenshot (5)](https://github.com/user-attachments/assets/6f7921ec-5d15-445a-8aa2-87ff8f9084e2)
![Screenshot (4)](https://github.com/user-attachments/assets/54e243a7-8e18-4766-8470-b15533b3b061)
![Screenshot (2)](https://github.com/user-attachments/assets/05275fdf-3280-4d9b-b398-d66ca1b88337)



🧑‍💻 Author
Built by Allan Osei
