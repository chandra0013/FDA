# Blue_Query

Blue_Query is an AI-powered conversational interface for ARGO Ocean Data Discovery and Visualization. This application allows users to interact with oceanographic data through natural language, generate visualizations, and gain insights from complex datasets. It's built with Next.js, TypeScript, Genkit for AI functionalities, and ShadCN for the user interface.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed on your system:
*   [Node.js](https://nodejs.org/en) (Version 20.x or later is recommended)
*   A package manager such as `npm`, `yarn`, or `pnpm`. This project uses `npm` by default.

### 1. Installation

First, clone the repository to your local machine and navigate into the project directory:

```bash
git clone https://github.com/chandra0013/FDA.git
cd FDA
```

Next, install the project dependencies using your package manager. For example, with `npm`:

```bash
npm install
```

### 2. Environment Variables

This project requires API keys for Google Maps and Google's Generative AI (Gemini).

1.  Create a new file named `.env` in the root of your project directory.
2.  Copy the contents of the `.env.example` file (if it exists) or add the following lines to your new `.env` file:

    ```
    # Get this from the Google Cloud Console for Maps JavaScript API
    NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=YOUR_GOOGLE_MAPS_API_KEY

    # Get this from Google AI Studio
    GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    ```

3.  Replace `YOUR_GOOGLE_MAPS_API_KEY` and `YOUR_GEMINI_API_KEY` with your actual API keys.

### 3. Running the Development Server

Once the dependencies are installed and the environment variables are set, you can run the local development server:

```bash
npm run dev
```

This command starts the Next.js development server. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to see the application running.

The landing page and all other pages should now be accessible. Any changes you make to the code will be automatically reflected in the browser.

## Available Scripts

*   `npm run dev`: Starts the application in development mode.
*   `npm run build`: Creates a production-ready build of the application.
*   `npm run start`: Starts the production server (requires a build to be run first).
*   `npm run lint`: Lints the project files for code quality issues.
 
