# Portfolio_Ishaan

A modern, responsive portfolio website built with Next.js 15, TypeScript, and Tailwind CSS. This project showcases my skills, projects, and professional experience through an elegant and interactive user interface.

## 🚀 Features

- **Modern UI/UX**: Built with Radix UI components and Tailwind CSS for a polished, responsive design
- **Dark/Light Theme**: Seamless theme switching with next-themes
- **Interactive Elements**: Custom cursor, magnetic buttons, and smooth animations
- **Contact Form**: Functional contact form with email integration via Nodemailer
- **Performance Optimized**: Built with Next.js 15 for optimal performance and SEO
- **TypeScript**: Full type safety throughout the application
- **Component Library**: Reusable UI components with shadcn/ui

## 🛠️ Tech Stack

### Frontend
- **Next.js 15.5.6** - React framework with App Router
- **React 19.2.0** - UI library
- **TypeScript 5** - Type-safe JavaScript
- **Tailwind CSS 4.1.9** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Lucide React** - Icon library
- **Framer Motion** - Animation library (via tailwindcss-animate)

### Backend & APIs
- **Next.js API Routes** - Serverless API endpoints
- **Nodemailer** - Email functionality
- **Vercel Analytics** - Performance monitoring

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **pnpm** - Package manager

## 📁 Project Structure

```
Portfolio/
├── app/                    # Next.js App Router
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # Reusable components
│   ├── ui/               # shadcn/ui components
│   ├── sections/         # Page sections
│   ├── custom-cursor.tsx
│   ├── grain-overlay.tsx
│   ├── magnetic-button.tsx
│   └── theme-provider.tsx
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
├── styles/               # Additional styles
└── types/                # TypeScript type definitions
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm/yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Portfolio.git
cd Portfolio
```

2. Install dependencies:
```bash
pnpm install
```

3. Copy the environment variables:
```bash
cp .env.example .env.local
```

4. Set up your environment variables in `.env.local`:
```
# Email configuration (for contact form)
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password
EMAIL_FROM=your-email@gmail.com
```

### Development

Start the development server:
```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build & Deploy

Build for production:
```bash
pnpm build
```

Start the production server:
```bash
pnpm start
```

## 📧 Contact Form Configuration

The contact form uses Nodemailer to send emails. To set it up:

1. Enable 2-factor authentication on your Gmail account
2. Generate an App Password: [Google App Passwords](https://myaccount.google.com/apppasswords)
3. Add the credentials to your `.env.local` file

## 🎨 Customization

### Theme Colors
The theme colors are defined in `tailwind.config.js` and can be customized to match your brand.

### Components
All UI components are built with Radix UI and styled with Tailwind CSS. You can find them in the `components/ui` directory.

### Sections
The main sections are located in `components/sections/` and can be easily modified or rearranged.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Radix UI](https://www.radix-ui.com/) - Accessible component primitives
- [shadcn/ui](https://ui.shadcn.com/) - Beautifully designed components
- [Lucide](https://lucide.dev/) - Beautiful & consistent icon toolkit

---

Built with ❤️ by [Ishaan Sharma](https://your-portfolio-url.com)
