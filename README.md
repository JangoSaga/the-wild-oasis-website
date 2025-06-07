
# The Wild Oasis

**A hotel reservation web application built with Next.js, React, and Tailwind CSS.**
The Wild Oasis enables users to explore premium cabins, check real-time availability, make secure online bookings, and manage their reservations effortlessly — all wrapped in a visually engaging, responsive experience.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3982397a-6802-4434-b7b0-499c9e304c75" alt="The Wild Oasis Banner" width="100%"/>
</p>

---

## 🌐 Live Demo

**🔗 [View the Application](https://the-wild-oasis-website-seven-alpha.vercel.app/)**

---

## ✨ Key Features

### 🏡 Cabin Exploration

* Browse a curated list of luxury cabins with high-quality images, capacities, and pricing.
* Filter options based on capacity (small, medium, large).
* Fully responsive and interactive interface.

### 📆 Seamless Booking

* Real-time cabin availability.
* Secure, intuitive booking process.
* Optimistic UI updates ensure fast feedback after interactions.

### 👤 User Management

* Secure Google OAuth authentication using NextAuth.
* Personalized dashboard to view, modify, or cancel reservations.
* Profile settings: update guest info, email, and more.

### 🔐 Secure Session Handling

* Persistent sessions powered by **NextAuth**.
* Role-based private routes ensure user-specific data access.

### ⚡ Performance & Scalability

* Built with **Next.js App Router** and **Turbopack** for blazing-fast performance.
* Optimized with **Tailwind CSS** for design consistency and accessibility.
* Automatically deployed on **Vercel** for global CDN distribution.

### 🎨 Design & Accessibility

* Unique UI theme with **Josefin Sans** Google font.
* Clean layout and accessible components throughout.
* Informative “About” page highlighting the experience.

---

## 🛠️ Tech Stack

| Layer          | Technologies Used                                                     |
| -------------- | --------------------------------------------------------------------- |
| **Framework**  | [Next.js](https://nextjs.org/) (App Router, Server Components)        |
| **Frontend**   | [React](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/) |
| **Auth**       | [NextAuth.js](https://next-auth.js.org/) (Google Provider)            |
| **Database**   | [Supabase](https://supabase.com/)                                     |
| **Build Tool** | [Turbopack](https://turbo.build/pack)                                 |
| **Deployment** | [Vercel](https://vercel.com/)                                         |

---

## 🖼️ Screenshots

<p float="left">
  <img src="https://github.com/user-attachments/assets/4573ff13-3d5c-4311-9b14-2a20b97c6891" width="48%" />
  <img src="https://github.com/user-attachments/assets/ba443909-a895-4225-b067-dc498111a0a9" width="48%" />
</p>
<p float="left">
  <img src="https://github.com/user-attachments/assets/fb09d9e4-064d-4443-871a-2e5d4f0ac84a" width="48%" />
  <img src="https://github.com/user-attachments/assets/cc6f3259-3aeb-448f-8254-e6efd52899bb" width="48%" />
</p>

---

## 🧩 Project Structure

```
/app
├── _components       → Reusable UI and functional components
├── _lib              → Data fetching, session handling, and utilities
├── page.tsx          → Page routes and layouts (App Router)
│
/public               → Static assets (images, icons, etc.)
/styles               → Tailwind and global CSS
```

---

## 🔐 Authentication

The Wild Oasis integrates **Google OAuth via NextAuth** to ensure secure and reliable login functionality.
All user-specific routes and data access are protected through server-side session validation.

---

## ⚙️ Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/JangoSaga/the-wild-oasis-website.git
   cd the-wild-oasis-website
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**

   Create a `.env.local` file based on `.env.example` and populate it with the following credentials:

   ```env
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_SECRET=your_nextauth_secret
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   SUPABASE_URL=your_supabase_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Start the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Navigate to **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 👨‍💻 Author

Made with ❤️ by [**JangoSaga**](https://github.com/JangoSaga)

---
