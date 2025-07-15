# SaaS IDE Platform – CodeCraft
[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=flat-square&logo=vercel)](https://codecraft.liuyuelin.dev/)
[![Stars](https://img.shields.io/github/stars/liuyuelintop/code-craft?style=social)](https://github.com/liuyuelintop/code-craft/stargazers)

---

**CodeCraft** is a modern SaaS IDE platform inspired by VS Code, built with [Next.js](https://nextjs.org), [Convex](https://convex.dev), and [Clerk](https://clerk.com). It offers real-time collaborative code editing, secure payments, and a rich snippet sharing system—all wrapped in a beautiful, customizable interface.

## 🚀 Features

- ⚡ **Real-time code editing with multiplayer support**
- 🔒 **Secure payment gateway integration** (Lemon Squeezy)
- 📤 **Code snippet sharing system**
- 🎨 **VS Code-like interface customization**
- 🌐 **Authentication & user management** (Clerk)
- 💾 **Persistent storage & instant sync** (Convex)
- 💬 **Commenting and starring on snippets**
- 🖥️ **Multiple language support & Monaco editor themes**
- 🏆 **Profile stats, favorites, and more**

## 🖼️ Preview

![CodeCraft Screenshot](https://raw.githubusercontent.com/liuyuelintop/code-craft/main/public/next-code-craft.webp)

## ✨ Live Demo

👉 [Try CodeCraft now!](https://codecraft.liuyuelin.dev/)

## 🛠️ Tech Stack

- **Main:** Next.js, Convex, Clerk, Webhooks
- **Payments:** Lemon Squeezy
- **Other:** SaaS, Tailwind CSS, Monaco Editor, Framer Motion

## 📦 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/liuyuelin/code-craft.git
cd code-craft
npm install
```

Create a `.env.local` file with your credentials (see example in the repo):

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
CONVEX_DEPLOYMENT=...
NEXT_PUBLIC_CONVEX_URL=...
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

## 🧩 Project Structure

- `src/app/` – Next.js app directory (pages, layouts, components)
- `convex/` – Convex backend functions (queries, mutations, webhooks)
- `public/` – Static assets (images, logos)
- `src/store/` – Zustand store for editor state
- `src/types/` – TypeScript types

## 📝 Customization

- **Themes:** Easily switch between Monaco editor themes.
- **Languages:** Supports multiple programming languages out of the box.
- **Payments:** Lemon Squeezy integration for Pro upgrades.

## 🛡️ Security

- All authentication is handled via Clerk.
- Webhooks are verified for both Clerk and Lemon Squeezy.
- User data is securely stored and managed with Convex.

## 💡 Inspiration

Inspired by the best features of VS Code and modern online IDEs, CodeCraft aims to make collaborative coding and sharing as seamless as possible.

## 🙏 Support & Contributing

If you like this project, **please give it a star!**  
Pull requests and issues are welcome.

## 📄 License

MIT

---

## 🙏 Acknowledgements

This project is heavily inspired by [burakorkmez/code-craft](https://github.com/burakorkmez/code-craft) and follows the excellent tutorial by [Burak Orkmez on YouTube](https://www.youtube.com/watch?v=fGkRQgf6Scw&t=2666s).  
Most of the core code and architecture are contributed by the original author.  
Special thanks for sharing such a great learning resource!