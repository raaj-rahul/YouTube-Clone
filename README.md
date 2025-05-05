# 📺 YouTube Clone – Full Stack Application

This is a full-stack YouTube clone project named **`rest-express`**, built using modern technologies including **Express**, **TypeScript**, **Vite**, **Tailwind CSS**, and **Drizzle ORM**.

---

## 📦 Project Structure

youtube/
├── client/ # Frontend (using React + Vite)

├── server/ # Backend (Express + TypeScript)

├── shared/ # Shared code between frontend & backend

├── attached_assets/ # Project-related media/assets

├── drizzle.config.ts # Drizzle ORM config

├── tailwind.config.ts # Tailwind CSS config

├── vite.config.ts # Vite config

├── postcss.config.js # PostCSS config

├── tsconfig.json # TypeScript config

├── theme.json # Design/theme file

├── package.json # Project metadata and scripts

└── .gitignore


---

## 🛠️ Tech Stack

- **Frontend**: React (assumed), Vite, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript
- **ORM**: Drizzle ORM
- **Build Tools**: Vite, esbuild
- **Styling**: Tailwind CSS, PostCSS

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v20.12.2 recommended)
- npm (v10+)
- Drizzle CLI (for DB operations)

---

## 📥 Installation

```bash
git clone https://github.com/your-username/youtube-clone.git
cd youtube
npm install
```
📌 Available Scripts
Command	Description
npm run dev	Starts development server

npm run build	Builds the app for production

npm run start	Runs the app in production mode

npm run check	Runs TypeScript type checks

npm run db:push	Pushes DB schema changes using Drizzle ORM

🌐 Running the App
Start the dev server:

t
npm run dev
Make sure your environment variables and DB are configured correctly.

⚙️ Environment Configuration
Create a .env file:

env

PORT=5000
DATABASE_URL=your_database_url
NODE_ENV=development
🧰 Database
Use the Drizzle CLI to push schema changes:


npm run db:push
📸 Assets
![image](https://github.com/user-attachments/assets/7a28c210-adfe-4e13-b440-895b234b2aae)

🧾 License
This project is licensed under the MIT License.

