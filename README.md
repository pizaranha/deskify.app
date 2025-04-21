# 📎 Deskify

**Deskify** is a customizable homepage designed for schools, teachers, students, and families. It works like a virtual desktop in your browser — providing quick access to essential tools, educational apps, important dates, and institution-specific content.

## 🌟 Features

- 🖥️ Personal homepage with a dashboard feel
- 🌐 Quick access to approved websites and educational tools
- 🌙 Built-in dark mode
- 📱 Installable as a Progressive Web App (PWA)
- 🧩 Chrome and Firefox browser extension support
- 🗂️ Multiple desktop layouts (by subject or day)
- 📅 Display of upcoming events and announcements
- 🧠 AI tools and search engine shortcuts
- 🖼️ Background customization using image APIs
- 🔒 Secure login and persistent user data (Firebase)
- 📊 Usage analytics for institutions
- 🔁 Realtime updates with no page reload

## 🚀 Tech Stack

- **Frontend**: Next.js (App Router), React, Tailwind CSS, shadcn/ui
- **Auth & DB**: Firebase Authentication & Firestore
- **State & Cache**: React Context / Zustand
- **Deployment**: Vercel / Firebase Hosting
- **Browser Extension**: Plasmo or Vite + Manifest V3

## 📦 Getting Started

```bash
git clone https://github.com/your-username/deskify.app.git
cd deskify.app
npm install
npm run dev

---

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
