# Ishwarya R - Portfolio

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS. Features smooth animations, glass-morphism design, and backend email functionality.

## 🚀 Live Demo

[View Portfolio](https://ishwarya-portfolio-site.vercel.app/)

## ✨ Features

- **Responsive Design** - Fully optimized for mobile, tablet, and desktop
- **Modern UI/UX** - Glass-morphism cards, smooth animations, and dark theme
- **Interactive Projects** - Click-to-expand project modals with live demos and source code links
- **Journey Timeline** - Visual progression from education to internships
- **Contact Form** - Real email functionality powered by Resend API
- **Tech Stack Showcase** - Visual display of technologies and tools
- **Achievements & Certificates** - Display of certifications with links

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Animations
- **Lucide Icons** - Icon library
- **Shadcn/ui** - UI components

### Backend
- **Cloud** - Backend infrastructure
- **Edge Functions** - Serverless functions for email
- **Resend** - Email delivery service

## 📁 Project Structure

```
src/
├── components/
│   ├── About.tsx          # About section with journey timeline
│   ├── Achievements.tsx   # Achievements and certificates
│   ├── Contact.tsx        # Contact form with email integration
│   ├── Experience.tsx     # Work experience section
│   ├── Footer.tsx         # Footer component
│   ├── Hero.tsx           # Hero section with intro
│   ├── Navbar.tsx         # Navigation bar
│   ├── Projects.tsx       # Projects showcase with modals
│   ├── Resume.tsx         # Resume download section
│   ├── TechStack.tsx      # Technologies display
│   └── ui/                # Reusable UI components
├── hooks/
│   ├── useScrollAnimation.tsx  # Scroll-triggered animations
│   └── use-mobile.tsx          # Mobile detection hook
├── pages/
│   ├── Index.tsx          # Main page
│   └── NotFound.tsx       # 404 page
└── integrations/
    └── supabase/          # Backend client configuration
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/ishwarya-18/portfolio.git
cd portfolio
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 📧 Contact Form Setup

The contact form uses Resend for email delivery. To configure:

1. Create a [Resend](https://resend.com) account
2. Get your API key
3. Add the `RESEND_API_KEY` secret in Lovable Cloud settings

## 👤 Author

**Ishwarya R**

- GitHub: [@ishwarya-18](https://github.com/ishwarya-18)
- LinkedIn: [Ishwarya R](https://www.linkedin.com/in/ishwarya-01i08s05h/)
- LeetCode: [ishwarya_18](https://leetcode.com/ishwarya_18)
- Email: ishwaryarajendran77@gmail.com

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---