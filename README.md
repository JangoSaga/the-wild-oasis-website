# The Wild Oasis

A hotel web application built with Next.js, React, and Tailwind CSS. The Wild Oasis allows users to explore luxury cabins, make online reservations, manage their bookings, and securely sign in with Google. Enjoy a seamless, fast, and visually engaging experience for your next adventure.

![The Wild Oasis](https://github.com/user-attachments/assets/3982397a-6802-4434-b7b0-499c9e304c75)

## 🏞️ Live Demo

> _Demo Link: (https://the-wild-oasis-website-seven-alpha.vercel.app/)_

---

## 🌟 Features

- **Cabin Exploration**
  - Browse a selection of luxury cabins with detailed descriptions, photos, capacities, and pricing.
  - Filter cabins by capacity (small, medium, large).
  - Responsive, modern UI for easy navigation.

- **Seamless Reservations**
  - Real-time availability and booking for each cabin.
  - Secure, user-friendly reservation form.

- **User Account Management**
  - Google authentication via NextAuth for quick, secure sign-in.
  - Personal dashboard: view, manage, and delete your reservations.
  - Profile management: update email and guest details.

- **Session & State Management**
  - Persistent user sessions with session management handled via NextAuth.
  - Optimistic UI updates for booking and cancellation.
  - Private routes for authenticated users, ensuring data privacy.

- **Performance & Deployment**
  - Built with **Next.js App Router** and **Turbopack** for fast build times and blazing runtime performance.
  - Styled using **Tailwind CSS** for a modern, accessible look & feel.
  - Hosted and deployed on **Vercel** for instant global delivery.

- **Additional Highlights**
  - Custom theme with “Josefin Sans” Google font.
  - Informative “About” page sharing the Wild Oasis experience.
  - Accessible navigation and UI components.

---

## 🚀 Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router, Server Components, Suspense)
- **Frontend**: [React](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/)
- **Authentication**: [NextAuth.js](https://next-auth.js.org/) with Google provider
- **Build Tool**: [Turbopack](https://turbo.build/pack)
- **Deployment**: [Vercel](https://vercel.com/)
- **Database**: [Supabase](https://supabase.com/) (used in backend data services)

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/4573ff13-3d5c-4311-9b14-2a20b97c6891)
![image](https://github.com/user-attachments/assets/ba443909-a895-4225-b067-dc498111a0a9)
![image](https://github.com/user-attachments/assets/fb09d9e4-064d-4443-871a-2e5d4f0ac84a)
![image](https://github.com/user-attachments/assets/cc6f3259-3aeb-448f-8254-e6efd52899bb)

---

## 🧭 Project Structure

- `/app`  
  Main application code (pages, layouts, components)
- `/app/_components`  
  Reusable UI and logic components
- `/app/_lib`  
  Data fetching, authentication, and utility services
- `/public`  
  Static assets (images, background, icons)
- `/styles`  
  Global and component-level styles

---

## 🔒 Authentication

The Wild Oasis uses **NextAuth** for Google OAuth authentication. User data is protected and sessions are managed securely. Only authenticated users can make and manage reservations.

---

## 🛠️ Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/JangoSaga/the-wild-oasis-website.git
   cd the-wild-oasis-website
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file based on `.env.example` and fill in credentials for NextAuth, Supabase, etc.

   ```
   NEXTAUTH_URL=...
   NEXTAUTH_SECRET=...
   GOOGLE_CLIENT_ID=...
   GOOGLE_CLIENT_SECRET=...
   SUPABASE_URL=...
   SUPABASE_ANON_KEY=...
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Visit [http://localhost:3000](http://localhost:3000)

## Built with ❤️ by [JangoSaga](https://github.com/JangoSaga)
