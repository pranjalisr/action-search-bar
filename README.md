# 🔍 Action Search Bar

An **animated, action-driven search bar** built with **Next.js 14**, **React 18**, and **TypeScript**. Features smooth, fluid animations powered by **Framer Motion** and a command palette experience using `cmdk` — all styled with Tailwind CSS and shadcn/ui.

---

## 📁 Project Structure

```
action-search-bar/
├── app/               # Next.js App Router pages & layouts
├── components/        # Search bar & UI components
│   └── ui/            # shadcn/ui component library
├── hooks/             # Custom React hooks
├── lib/               # Utility functions (cn, clsx)
├── public/            # Static assets
├── styles/            # Global CSS styles
├── components.json    # shadcn/ui configuration
├── next.config.mjs    # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json      # TypeScript configuration
```

---

## 🛠️ Tech Stack

| Category        | Technology                             |
|-----------------|----------------------------------------|
| Framework       | Next.js 14.2.16                        |
| Language        | TypeScript 5                           |
| UI Library      | React 18                               |
| Animations      | **Framer Motion** (latest)             |
| Command Palette | `cmdk` 1.0.4                           |
| Component Kit   | shadcn/ui (Radix UI primitives)        |
| Styling         | Tailwind CSS 3 + tailwindcss-animate   |
| Icons           | Lucide React                           |
| Theming         | next-themes (dark / light mode)        |
| Forms           | React Hook Form + Zod                  |
| Charts          | Recharts 2.15.0                        |
| Package Manager | npm                                    |

---

## ✨ Key Features

- 🎬 **Framer Motion animations** — smooth enter/exit transitions, spring physics, and gesture-driven interactions on the search bar
- ⌨️ **Command palette UX** — powered by `cmdk` for keyboard-navigable action search
- 🌙 **Dark / Light mode** — via `next-themes`
- ♿ **Accessible** — built on Radix UI accessible primitives
- 📱 **Fully responsive** — works on all screen sizes
- ⚡ **App Router** — Next.js 14 file-based routing with RSC support

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/pranjalisr/action-search-bar.git
cd action-search-bar

# Install dependencies
npm install
```

### Running the Dev Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 Available Scripts

| Command          | Description                          |
|------------------|--------------------------------------|
| `npm run dev`    | Start the development server         |
| `npm run build`  | Build the app for production         |
| `npm run start`  | Start the production server          |
| `npm run lint`   | Run ESLint across the project        |

---

## 📦 Key Dependencies

| Package                   | Purpose                              |
|---------------------------|--------------------------------------|
| `framer-motion`           | Animations & motion interactions     |
| `@emotion/is-prop-valid`  | Framer Motion peer dependency        |
| `cmdk`                    | Command palette / action search UX   |
| `next`                    | React framework (App Router)         |
| `react` / `react-dom`     | UI rendering (v18)                   |
| `tailwindcss`             | Utility-first CSS                    |
| `@radix-ui/*`             | Accessible UI primitives             |
| `lucide-react`            | Icon library                         |
| `next-themes`             | Dark/light theme switching           |
| `react-hook-form` + `zod` | Form handling & validation           |
| `sonner`                  | Toast notifications                  |
| `clsx` + `tailwind-merge` | Conditional class utilities          |
| `vaul`                    | Drawer / bottom sheet                |
| `embla-carousel-react`    | Carousel component                   |
| `input-otp`               | OTP input fields                     |
| `date-fns`                | Date formatting utilities            |

---

## 🚢 Deployment

Deploy to [Vercel](https://vercel.com/) in one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/pranjalisr/action-search-bar)

---


## 📄 License

This project is open source and available under the [MIT License](LICENSE).
