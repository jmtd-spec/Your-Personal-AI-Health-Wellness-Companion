# WellnessAI Coach - Your Personal AI Health & Wellness Companion

## Project Overview

WellnessAI Coach is a Progressive Web App (PWA) designed to be a hyper-personalized health and wellness companion. It leverages artificial intelligence to provide users with customized workout plans, meal suggestions, and mental wellness exercises. The app adapts to user progress, preferences, and aims to integrate with wearable devices to deliver a comprehensive wellness experience. Built with a focus on user engagement and a freemium monetization model, WellnessAI Coach is designed for easy distribution on major app stores.

## Features

- **AI-Powered Personalization**: Generates tailored workout plans, meal suggestions, and wellness guidance based on individual user profiles and goals.
- **User Onboarding**: An intuitive onboarding process to collect essential user data (age, gender, height, weight, fitness level, primary goals, time available for workouts).
- **Interactive Dashboard**: Provides a quick overview of daily plans, progress, and AI-driven insights.
- **Workout Library**: Curated workout routines with details on duration, difficulty, and exercises.
- **Nutrition Tracking**: Offers meal suggestions and tracks macronutrient intake with progress visualization.
- **Progress Tracking**: Visualizes fitness journey over time with charts and highlights weekly achievements.
- **Responsive Design**: Optimized for seamless experience across various devices (mobile, tablet, desktop).
- **Progressive Web App (PWA)**: Offers native-like app experience, offline capabilities, and can be installed on home screens.
- **Monetization Strategy**: Implements a freemium model with tiered subscriptions for advanced features and content.

## Technologies Used

### Frontend
- **React 18+**: A JavaScript library for building user interfaces.
- **TypeScript**: For type safety and enhanced developer experience.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Shadcn/UI**: A collection of re-usable components built with Radix UI and Tailwind CSS.
- **Lucide React**: A beautiful collection of open-source icons.
- **Recharts**: A composable charting library built on React components.
- **Vite**: A fast frontend build tool.

### AI Integration (Simulated)
- **OpenAI API**: (Conceptual) For generating personalized recommendations and content.

### Data Storage (Local)
- **Local Storage**: For persisting user profile data and settings within the browser.

## Setup and Installation

To get a local copy of the project up and running, follow these simple steps.

### Prerequisites

Ensure you have Node.js (version 18 or higher) and pnpm (or npm/yarn) installed on your machine.

- **Node.js**: [Download & Install Node.js](https://nodejs.org/en/download/)
- **pnpm**: `npm install -g pnpm` (if you prefer pnpm)

### Installation Steps

1.  **Clone the repository** (or extract the `wellness-ai-coach-source.zip` file):
    ```bash
    git clone <repository-url>
    cd wellness-ai-coach
    ```
    If you received a zip file, extract it and navigate into the `wellness-ai-coach` directory.

2.  **Install dependencies**:
    ```bash
    pnpm install
    # or npm install
    # or yarn install
    ```

## Running the Application

To run the application in development mode:

```bash
pnpm run dev
# or npm run dev
# or yarn dev
```

This will start the development server, usually at `http://localhost:5173`. The app will automatically reload if you make changes to the source code.

## Deployment

WellnessAI Coach is built as a Progressive Web App (PWA), making it highly deployable to various platforms.

### Building for Production

To create a production-ready build of the application:

```bash
pnpm run build
# or npm run build
# or yarn build
```

This command bundles the React app into static files in the `dist/` directory, ready for deployment.

### Deploying to Static Hosting (e.g., GitHub Pages, Vercel, Netlify)

1.  **Build the project**: Run `pnpm run build` (or `npm run build`).
2.  **Upload `dist` folder**: The contents of the `dist` folder can be uploaded to any static hosting service.

    **For GitHub Pages:**
    - Ensure your `package.json` includes a `homepage` field: `

## Contributing

Contributions are welcome! Please feel free to fork the repository, create a new branch, and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

For any questions or inquiries, please contact jm.djoukang@gmail.com.
