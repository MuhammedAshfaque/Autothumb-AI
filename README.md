# AutoThumb - AI 

AutoThumb is a web application that automatically creates visually appealing thumbnails using generative AI based on minimal user prompts. The platform integrates Google Gemini GenAI API for prompt-based content creation, offering a seamless and creative experience.

## Features

- **AI-Powered Thumbnail Generation:** Integrated with Google Gemini GenAI API to generate high-quality thumbnails based on minimal text prompts.
- **Session-based Authentication:** Secure user management and session maintenance using Express sessions, Connect-Mongo, and MongoDB.
- **Modern UI/UX:** Built with React 19, Vite, Tailwind CSS v4, and Framer Motion for a stunning, responsive, and dynamic user interface.
- **Cloud Storage Integration:** Utilizes Cloudinary for efficient image management and delivery.
- **Robust Backend:** Built on Node.js and Express.js with a MongoDB database for scalable performance.

## Technology Stack

### Frontend
- **Framework:** React 19, Vite
- **Styling:** Tailwind CSS v4
- **Routing:** React Router DOM
- **Animations:** Framer Motion, Lenis (Smooth Scrolling)
- **HTTP Client:** Axios
- **Language:** TypeScript

### Backend
- **Framework:** Node.js, Express.js (v5)
- **Database:** MongoDB & Mongoose
- **AI Integration:** Google Gemini GenAI API (`@google/genai`)
- **Cloud Storage:** Cloudinary
- **Authentication & State:** Express Session, Connect-Mongo, Bcrypt
- **Language:** TypeScript

##  Project Structure

The project is structured into two main directories:

- `/CLIENT`: Contains the React/Vite frontend application code.
- `/Backend`: Contains the Node.js/Express backend API and services.

##  Installation & Setup

### Prerequisites
- Node.js (v18 or higher recommended)
- MongoDB instance (local or remote/Atlas)
- Google Gemini API Key
- Cloudinary Account (for image hosting)

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd AI_THUMBNAIL
```

### 2. Backend Setup
Navigate to the `Backend` directory and install dependencies:
```bash
cd Backend
npm install
```

Start the backend development server using `nodemon` and `tsx`:
```bash
npm run server
```

*(Note: Create a `.env` file in the `Backend` directory containing your required configuration variables like `MONGO_URI`, Cloudinary keys, `GEMINI_API_KEY`, and session secrets.)*

### 3. Frontend Setup
Open a new terminal window, navigate to the `CLIENT` directory, and install dependencies:
```bash
cd CLIENT
npm install
```

Start the frontend Vite development server:
```bash
npm run dev
```

*(Note: Create a `.env` file in the `CLIENT` directory if you have any frontend-specific environment variables.)*

##  Available Scripts

### Backend (`/Backend` directory)
- `npm start`: Starts the application logic (`tsx server.ts`).
- `npm run server`: Starts the server with hot-reloading using `nodemon`.
- `npm run build`: Compiles TypeScript source files into JavaScript.

### Frontend (`/CLIENT` directory)
- `npm run dev`: Starts the Vite development server.
- `npm run build`: Builds the production-ready application bundle.
- `npm run lint`: Runs ESLint to check for code issues.
- `npm run preview`: Previews the built production site locally.

