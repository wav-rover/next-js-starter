# Next.js Starter

A modern Next.js starter template with a comprehensive set of features and tools pre-configured.

## Features

- 🎨 [Tailwind CSS](https://tailwindcss.com) for styling
- 🎯 [shadcn/ui](https://ui.shadcn.com/) components with New York style
- 🌙 Dark mode support with next-themes
- 🎭 Animation utilities with Framer Motion
- 🔒 Authentication ready with better-auth
- 💳 Stripe integration for payments
- 📝 Form handling with React Hook Form and Zod validation
- 🎉 Toast notifications with Sonner
- 📱 Mobile-first responsive design

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Key Dependencies

### UI and Styling
- Radix UI primitives for accessible components
- Tailwind CSS for styling
- Class Variance Authority for component variants
- Framer Motion for animations
- Embla Carousel for carousels
- React Day Picker for date inputs
- cmdk for command palettes

### Forms and Validation
- React Hook Form for form management
- Zod for schema validation
- Input OTP for one-time password inputs

### Data and State
- Recharts for charts and graphs
- React Resizable Panels for resizable layouts

### Payment Integration
- Stripe for payment processing

### Development Tools
- ESLint for code linting
- PostCSS for CSS processing

## Project Structure

```
├── app/              # Next.js app directory
├── components/       # React components
│   ├── ui/          # shadcn/ui components
│   └── utils/       # Utility components
├── hooks/           # Custom React hooks
├── lib/             # Utility functions
└── public/          # Static assets
```

## Learn More

To learn more about the tools used in this starter:

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [shadcn/ui Documentation](https://ui.shadcn.com)
- [Radix UI Documentation](https://www.radix-ui.com)
