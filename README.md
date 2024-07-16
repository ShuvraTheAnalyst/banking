🚑Introduction


Built with Next.js, Horizon is a financial SaaS platform that connects to multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manages their finances altogether.


⚙️ Tech Stack
   
   Next.js
   
   TypeScript
   
   Appwrite
   
   Plaid
   
   Dwolla
   
   React Hook Form
   
   Zod
   
   TailwindCSS
   
   Chart.js
   
   ShadCN



   🔋 Features

   
👉 Authentication: An ultra-secure SSR authentication with proper validations and authorization

👉 Connect Banks: Integrates with Plaid for multiple bank account linking

👉 Home Page: Shows general overview of user account with total balance from all connected banks, recent transactions, money spent on different categories, etc

👉 My Banks: Check the complete list of all connected banks with respective balances, account details

👉 Transaction History: Includes pagination and filtering options for viewing transaction history of different banks

👉 Real-time Updates: Reflects changes across all relevant pages upon connecting new bank accounts.

👉 Funds Transfer: Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

👉 Responsiveness: Ensures the application adapts seamlessly to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.















This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
