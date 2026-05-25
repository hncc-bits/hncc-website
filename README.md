# HNCC Website

The official website for the **Hackathon and Coding Club (HNCC)** at BIT Sindri.

Built with **Next.js**, **Tailwind CSS**, and **React**.

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (v12)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v3)
- **Animations/Effects**: `tsparticles`
- **Linting & Formatting**: ESLint, Prettier, Husky

## Getting Started

### Prerequisites

Ensure you have Node.js (version 18 or above) and `yarn` (or `npm`) installed on your local machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hncc-bits/hncc-website.git
   cd hncc-website
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

3. Run the development server:
   ```bash
   yarn dev
   # or
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the site running locally.

## Scripts & Code Quality

We use Husky, ESLint, and Prettier to maintain code quality. Please make sure your code is formatted before committing.

- `yarn dev`: Starts the Next.js development server.
- `yarn build`: Builds the app for production.
- `yarn start`: Starts the production server.
- `yarn style:all`: Runs both linting and formatting checks.
- `yarn make-pretty`: Formats the entire codebase using Prettier.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`). *Note: Husky will run a pre-commit hook to ensure code quality.*
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request targeting the `dev` branch.

## CI/CD and Deployment

- Pushes and Pull Requests to the `dev` branch automatically trigger a preview deployment on **Vercel** via our GitHub Actions workflow.
- Pushes to `main` are automatically deployed to our production environment on Vercel.
