# Surface - Next.js Production Boilerplate

A modern, full-stack web application boilerplate based on [Next.js Subscription Payments](https://github.com/vercel/nextjs-subscription-payments) with additional features and improvements.

## Features

- **Next.js 15** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Supabase** for authentication and database
- **Stripe** integration for payments
- **PostHog** for analytics
- **Radix UI** components for accessible UI
- **Real-time** capabilities with Supabase

## Prerequisites

- [Node.js](https://nodejs.org/en/download) (Latest LTS version recommended)
- [Git](https://git-scm.com/downloads)
- [Stripe CLI](https://stripe.com/docs/stripe-cli) (for payment integration)
- [Supabase CLI](https://supabase.com/docs/guides/cli) (for database management)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/devtodollars/startup-boilerplate.git YOUR_APP_NAME
cd YOUR_APP_NAME
```

2. Set up environment variables:
```bash
cp .env.example .env
```
Update the `.env` file with your configuration values.

3. Install dependencies:
```bash
npm install
```

4. Start Supabase services:
```bash
npm run supabase:start
```

5. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

## Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run linting
- `npm run prettier-fix` - Fix code formatting

### Supabase Commands
- `supabase:start` - Start Supabase services
- `supabase:stop` - Stop Supabase services
- `supabase:status` - Check services status
- `supabase:generate-types` - Generate TypeScript types
- `supabase:push` - Push local changes to Supabase
- `supabase:pull` - Pull remote changes from Supabase

### Stripe Commands
- `stripe:listen` - Start Stripe webhook listener
- `stripe:fixtures` - Load Stripe test fixtures

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
