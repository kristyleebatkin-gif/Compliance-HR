# Supabase App

A full-stack application built with **Node.js** and **Supabase**, featuring a dashboard and intake centre.

## Features

- Dashboard — overview and analytics
- Intake Centre — manage incoming entries and data
- Supabase backend — authentication, database, and storage

## Tech Stack

- **Runtime:** Node.js
- **Backend-as-a-Service:** Supabase (PostgreSQL, Auth, Storage)
- **Database:** PostgreSQL (via Supabase)

## Prerequisites

- Node.js >= 18
- A [Supabase](https://supabase.com) project

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure environment variables**

   Copy `.env.example` to `.env` and fill in your Supabase credentials:

   ```bash
   cp .env.example .env
   ```

   ```env
   SUPABASE_URL=https://your-project.supabase.co
   SUPABASE_ANON_KEY=your-anon-key
   SUPABASE_SERVICE_ROLE_KEY=your-service-role-key
   ```

4. **Run the app**

   ```bash
   npm start
   ```

   For development with hot reload:

   ```bash
   npm run dev
   ```

## Project Structure

```
├── dashboard/          # Dashboard module
├── intake centre/      # Intake centre module
├── .env.example        # Environment variable template
├── .gitignore
└── package.json
```

## Environment Variables

| Variable                   | Description                        |
| -------------------------- | ---------------------------------- |
| `SUPABASE_URL`             | Your Supabase project URL          |
| `SUPABASE_ANON_KEY`        | Public anon key                    |
| `SUPABASE_SERVICE_ROLE_KEY`| Service role key (keep secret)     |

## License

MIT
