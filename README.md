# Honest Online Learning

Online learning platform for discovering courses, instructors, and learning content, with authenticated user and dashboard flows.

[Live site](https://honestonlinelearning.vercel.app/) · [Code of Conduct](CODE_OF_CONDUCT.md) · [MIT License](LICENSE)

## Overview

Honest Online Learning is a full-stack learning platform built with Next.js. The application includes a public course experience alongside account, profile, dashboard, and payment-related workflows.

The home experience includes featured courses, instructors, learner reviews, and contact information. The application also contains dedicated course, login, signup, profile, dashboard, and top-up routes.

## Main Features

- Course discovery and learning content
- Instructor presentation
- User registration and authentication
- User profile and dashboard flows
- Reviews and contact sections
- Payment and top-up integration work
- Administrative and API-backed application features

## Tech Stack

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Ant Design
- MongoDB / Mongoose
- NextAuth
- Firebase
- Stripe
- SWR / Axios

## Run Locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000` in your browser.

## Production Build

```bash
npm run build
npm start
```

## Project Structure

```text
src/
  app/           Next.js application routes and API routes
  components/    Shared UI and page sections
  config/        Application configuration
  contexts/      React contexts
  db/            Database setup
  hooks/         Shared hooks
  layouts/       Layout components
  middlewares/   Request/application middleware
  models/        Data models
  providers/     Application providers
  repositories/  Data-access layer
  services/      Application services
  styles/        Shared styling
  types/         TypeScript types
  utils/         Utility functions
```

## Code of Conduct

Participation in this repository is covered by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

Licensed under the [MIT License](LICENSE).
