# PulsePanda - Fullstack Event Monitoring SaaS

PulsePanda is a modern full-stack event monitoring SaaS application built with Next.js, Postgres, TypeScript, Tailwind, and Clerk. It provides real-time event notifications, secure payments, and a user-friendly event management dashboard. The application also includes a beautiful landing page, real-time messaging via Discord, and integrates Stripe for payments.

![Project Image](https://github.com/mahmadmanzoor/pulsepanda/blob/main/public/thumbnail.png)

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Licensing](#license)

## Features

- 🛠️ **Complete SaaS built in modern Next.js**: Utilize the latest features and improvements of Next.js for efficient server-side rendering, API routes, and much more.
- 💻 **Beautiful landing page included**: Designed with modern UX principles, including custom illustrations made by a professional artist.
- 🎨 **Custom artworks**: Professionally designed graphics and UI elements for a polished, cohesive experience.
- ✉️ **Real-time event messages via Discord**: Keep users updated with important events using Discord's messaging features.
- 🖥️ **Clean & intuitive event monitoring dashboard**: A user-friendly interface for managing events, with the ability to track, monitor, and manage events effectively.
- 💳 **Secure payments using Stripe**: Integration with Stripe for handling customer payments and subscriptions in a secure and streamlined manner.
- 🛍️ **Customers can purchase your PRO plan**: Create and manage subscription plans, including payment processing and user authentication.
- 🌟 **Clean, modern UI on top of shadcn-ui**: Enjoy a beautiful UI built with ShadCN components for a smooth, modern user experience.
- 🔑 **Authentication using Clerk**: User authentication is handled with Clerk for a secure, scalable, and straightforward sign-in process.
- ⌨️ **100% written in TypeScript**: Ensure robust, type-safe development with full TypeScript support across the application.
- 🎁 **Much more**: Additional features for performance, user experience, and functionality.

## Getting Started

To get started with this project, clone the repository and follow the steps below.

### Prerequisites

Before you begin, ensure that you have the following installed:

- Node.js (>= 18.0.0)
- PostgreSQL (For local development)
- Clerk account for authentication
- Stripe account for payment processing

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mahmadmanzoor/pulsepanda.git
   ```

2. Navigate to the project folder:

   ```bash
   cd pulsepanda
   ```

3. Install the necessary dependencies:

   ```bash
   npm install
   ```

4. Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

### Configuration

In the `.env` file, fill in the required configuration values for:

- **Postgres**: Database connection string
- **Clerk**: Your Clerk API keys for authentication
- **Stripe**: Your Stripe API keys for payment processing
- **Discord**: Configuration for real-time event messages

Make sure to set all environment variables to ensure the application runs correctly.

### Usage

1. Start the development server:

   ```bash
   npm run dev
   ```

2. Navigate to `http://localhost:3000` in your browser to see the app in action.

3. To access the event monitoring dashboard, sign in using Clerk. Once authenticated, you can manage events, view real-time messages, and interact with the UI.

4. Users can purchase a PRO plan, enabling premium features through Stripe's payment system.

### Testing

To ensure the application works as expected, you can run the tests:

```bash
npm run test
```

This will run all the unit and integration tests for the application.

### License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.

## Roadmap

- [ ] Add more event category management features.
- [ ] Enhance the UI with additional themes and customizations.
- [ ] Add multi-tenancy support to allow multiple organizations.
- [ ] Improve performance with caching and other optimizations.
- [ ] Implement advanced error handling and monitoring.

Feel free to contribute and open issues if you find any bugs or want to suggest new features.
