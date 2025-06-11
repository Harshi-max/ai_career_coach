# 💼 Full Stack AI Career Coach

An AI-powered career assistant built with **Next.js**, **Neon DB**, **TailwindCSS**, **Prisma**, **Inngest**, and **Shadcn/UI**. Offers personalized job guidance, onboarding flow, and modern full-stack architecture.

---

## 🛠 Tech Stack

- **Frontend:** Next.js, TailwindCSS, Shadcn/UI
- **Backend:** Prisma, Neon DB, Inngest
- **Auth:** Clerk
- **Deploy:** Vercel

---

## 🚀 Getting Started

Follow these steps to get the app running locally.

---

### 📦 1. Clone the Repository

```bash
git clone https://github.com/Harshi-max/ai_career_coach.git
cd ai_career_coach


### Make sure to create a `.env` file with following variables -

# Database
DATABASE_URL=your_neon_db_url_here

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini AI Key
GEMINI_API_KEY=your_gemini_api_key

