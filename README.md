# Soluna

## 🌟 Overview

Soluna is a cutting-edge technical interview platform designed to streamline the hiring process by facilitating seamless interviews. Equipped with an integrated coding panel supporting multiple programming languages, Soluna provides real-time collaboration and tools tailored for an exceptional interview experience for both hiring teams and candidates.

## 🚀 Features

- **Real-Time Collaboration**: Enable interviewers and candidates to work together with live coding sessions.
- **Multi-Language Support**: Supports a wide range of programming languages to accommodate diverse technical needs.
- **Intuitive Interface**: A user-friendly design ensures both interviewers and candidates can focus on the assessment.
- **Integrated Interview Tools**: Includes features such as question banks, code review, and scoring.
- **Scalable Architecture**: Designed for small startups to large enterprises with varying hiring needs.
- **Responsive Design**: Optimized for desktop and mobile devices for convenience.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React with Next.js.
- **Styling**: Tailwind CSS for a modern, responsive design.
- **Type Safety**: TypeScript for robust and maintainable code.

### Backend
- **Platform**: Convex for serverless backend operations.
- **Authentication**: Clerk for secure user management.

### Tooling
- **Package Manager**: npm.
- **Build Tools**: Next.js and Vercel for CI/CD.
- **Version Control**: Git.

## 📁 Folder Structure

```
Soluna/
├── public/                  # Static assets
├── src/                     # Source files
│   ├── app/                 # Application pages and layouts
│   │   ├── (admin)/         # Admin views
│   │   ├── (root)/          # User-facing views
│   │   └── fonts/           # Custom fonts
│   ├── components/          # Reusable UI components
│   ├── hooks/               # Custom React hooks
│   ├── lib/                 # Utility functions
│   ├── actions/             # Application actions
│   ├── constants/           # Static constants
├── convex/                  # Backend logic
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
├── next.config.mjs          # Next.js configuration
└── package.json             # Dependencies and scripts
```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- **Node.js**: v16 or later
- **npm**: v7 or later

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/soluna.git
   cd soluna
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Environment Setup**:
   Create a `.env.local` file at the root of the project and add necessary environment variables. Refer to `.env.example` if provided.

4. **Start Development Server**:
   ```bash
   npm run dev
   ```
   Access the app at `http://localhost:3000`.

### Production Build

To create an optimized production build:
```bash
npm run build
npm run start
```

## 📜 Scripts

| Script           | Description                          |
|------------------|--------------------------------------|
| `npm run dev`    | Start the development server.        |
| `npm run build`  | Build the project for production.    |
| `npm run start`  | Serve the production build locally.  |
| `npm run lint`   | Lint the codebase for errors.        |

## 🤝 Contributing

We welcome contributions! Here's how you can get involved:

1. **Fork the Repository**: Click the fork button on the GitHub repository page.
2. **Create a Branch**: Branch off `main` with a descriptive name (`feature/add-new-feature`).
3. **Make Changes**: Commit your changes following conventional commit messages.
4. **Submit a PR**: Open a pull request with details of your changes.

## 📄 License

This project is licensed under the MIT License. For more details, see the `LICENSE` file in the repository.

## 📢 Acknowledgments

- **Frameworks**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Backend**: [Convex](https://convex.dev/)
- **Authentication**: [Clerk](https://clerk.dev/)

---

For additional queries, feel free to open an issue or reach out.

