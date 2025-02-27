# Valentine's Day Card Creator 💝

A delightful web application that lets users create personalized Valentine's Day cards with custom questions, GIFs, and interactive elements to share with their loved ones.

![Valentine's Day Card Creator](https://i.giphy.com/XxEy4h6YxKE2H5TZ1x.webp)

## 🌟 Features

- **Custom Card Creation**: Design personalized Valentine's Day cards with your own questions and messages
- **Interactive Questions**: Create a sequence of questions with "Yes" and "No" options
- **GIF Integration**: Search and add GIFs from GIPHY to make your cards more expressive
- **Playful Interactions**: "No" button gets harder to click as questions progress
- **Celebration Effects**: Confetti animation when your valentine accepts
- **Easy Sharing**: Generate unique links to share your cards with loved ones

## 🛠️ Technology Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS with shadcn/ui components
- **Animation**: Anime.js for heart animations, react-dom-confetti for celebration effects
- **Form Handling**: React Hook Form with Zod validation
- **Media**: GIPHY API integration for GIF selection
- **Database**: Supabase for storing card data
- **Deployment**: Vercel

## 🚀 Implementation Highlights

- **App Router Architecture**: Built with Next.js App Router for efficient page routing and server components
- **Responsive Design**: Fully responsive UI that works on all device sizes
- **Type Safety**: Comprehensive TypeScript implementation throughout the codebase
- **Modern React Patterns**: Leverages React hooks, context, and functional components
- **Performance Optimized**: Implements debouncing for search inputs and optimized animations
- **SEO Friendly**: Proper metadata configuration for better search engine visibility

## 🏗️ Project Structure

The application follows a clean, modular architecture:

- **Page Components**: Organized by feature (create, card viewing)
- **UI Components**: Reusable components with consistent styling
- **API Routes**: Server endpoints for card creation and retrieval
- **Utilities**: Helper functions for database access and type definitions

## 💡 Learning Outcomes

This project demonstrates proficiency in:

- Building interactive web applications with modern React and Next.js
- Implementing complex form validation and multi-step processes
- Creating engaging user experiences with animations and interactive elements
- Working with external APIs (GIPHY) for media integration
- Database design and implementation with Supabase
- Deployment and optimization for production environments

## 🔍 Future Enhancements

- Additional card templates and themes
- More customization options for animations and effects
- Social media integration for wider sharing capabilities
- Analytics to track card views and interactions

---

_This project was created with love and code. Feel free to use it to express your feelings to someone special!_

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
