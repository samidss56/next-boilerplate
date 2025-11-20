# Next.js Boilerplate

This project is a customized Next.js boilerplate built with the following stack:

* **Next.js** (App Router)
* **TypeScript**
* **Tailwind CSS**
* **shadcn/ui** component system
* **pnpm** as the package manager
* **Husky** + **lint-staged** for pre-commit formatting and linting

---

## 🚀 Getting Started

Install dependencies:

```bash
pnpm install
```

Run the development server:

```bash
pnpm dev
```

Open **[http://localhost:3000](http://localhost:3000)** in your browser to view the application.

You can start editing the UI by modifying files under the `app/` directory. The project supports hot-reloading out of the box.

---

## 🧩 Tech Stack Details

### **Next.js**

Modern React framework with server components support, file-based routing, and many optimizations by default.

### **Tailwind CSS**

Utility-first CSS framework. Tailwind CSS v4 uses a zero‑config setup by default with on-demand class scanning — no `tailwind.config.ts` file needed unless you opt into customization.

### **shadcn/ui**

A beautifully designed component library built on Radix UI + Tailwind. Components can be generated and extended locally.

### **pnpm**

Fast, disk-efficient package manager.

---

## 🛠️ Development Tools

### **Code Quality & Git Hooks**

* **ESLint** for linting
* **Prettier** for formatting
* **Husky** pre‑commit hooks
* **lint-staged** to run linters only on staged files

Pre-commit actions include automatic formatting and lint fixing.

---

## 📁 Project Structure

```
.
├── app/              # App Router pages & layouts
├── components/       # Reusable UI components (shadcn)
├── lib/              # Utilities & helper functions
├── styles/           # Global styles
├── public/           # Static assets
└── ...
```

---

## 📘 Useful Commands

| Command      | Description              |
| ------------ | ------------------------ |
| `pnpm dev`   | Start development server |
| `pnpm build` | Build for production     |
| `pnpm start` | Start production build   |
| `pnpm lint`  | Run ESLint               |

---

## 📦 Deployment

You can deploy this project on **Vercel**, the recommended platform for Next.js:

[https://vercel.com/new](https://vercel.com/new)

For more details, see Next.js deployment docs.

---

## 📚 Learn More

Here are some useful resources:

* Next.js Documentation — [https://nextjs.org/docs](https://nextjs.org/docs)
* Tailwind Docs — [https://tailwindcss.com/docs](https://tailwindcss.com/docs)
* shadcn/ui — [https://ui.shadcn.com](https://ui.shadcn.com)
* pnpm — [https://pnpm.io](https://pnpm.io)
