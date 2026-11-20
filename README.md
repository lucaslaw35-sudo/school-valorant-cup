# SCHOOL VALORANT CUP — Live Tournament Web App

Complete Vite + React + Tailwind CSS esports tournament website pre-wired for **Supabase** real-time persistence and authenticated Admin Dashboard controls.

## Quick Setup (3 Steps)

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Supabase
1. Run `supabase/schema.sql` in your Supabase **SQL Editor**.
2. Create an admin user in Supabase **Authentication → Users**.
3. Copy `.env.example` to `.env.local` and paste your Supabase URL and Publishable/Anon key:
```bash
cp .env.example .env.local
```

### 3. Run Locally or Deploy to Vercel
```bash
npm run dev
```
Push this folder to GitHub and import it into **Vercel** or **Netlify** (add the two `VITE_SUPABASE_*` variables in your host's Environment Variables settings).
