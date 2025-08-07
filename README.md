<div align="center">

# 🎨 Paperbag

_Transform your photos into stunning cartoon art with AI_

[![React](https://img.shields.io/badge/React-19-blue.svg)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-38B2AC.svg)](https://tailwindcss.com/)
[![Convex](https://img.shields.io/badge/Convex-1.21-purple.svg)](https://www.convex.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[Demo](#) | [Report Bug](#) | [Request Feature](#)

</div>

## 📝 Overview

Paperbag is a powerful web application that transforms ordinary photos into various cartoon styles using AI. With support for multiple cartoon styles including Simpsons, Anime, and Disney, Paperbag provides a seamless user experience with its modern interface and efficient processing capabilities.

## ✨ Features

### 🖼️ Image Transformation
- Transform your photos into various cartoon styles
- Real-time processing with AI-powered technology
- High-quality output with preserved details

### 🎭 Multiple Cartoon Styles
- **Simpsons**: Convert images to the iconic yellow cartoon style
- **Anime**: Transform photos into Japanese anime style
- **Disney**: Create Disney-inspired character transformations

### 📱 User Experience
- **Before & After Showcases**: Interactive comparison between original and transformed images
- **Responsive Design**: Optimized for desktop and mobile devices
- **Intuitive Interface**: Simple drag-and-drop functionality
- **Fast Processing**: Quick transformations with immediate results

## 🛠️ Technologies

### Frontend
- **Framework**: [React 19](https://react.dev)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com)
- **Routing**: [TanStack Router](https://tanstack.com/router)
- **UI Components**: [Radix UI](https://www.radix-ui.com/)
- **Icons**: [Lucide React](https://lucide.dev/)

### Backend
- **Database & Functions**: [Convex](https://www.convex.dev/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Analytics**: [Vercel Analytics](https://vercel.com/analytics)

### AI Integration
- **Image Processing**: [OpenAI](https://openai.com)

### DevOps
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Package Manager**: [pnpm](https://pnpm.io/)
- **Deployment**: [Vercel](https://vercel.com)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer)
- [pnpm](https://pnpm.io/) (v8 or newer)
- Convex account (for database)
- Clerk account (for authentication)
- OpenAI API key (for image processing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/paperbag.git
   cd paperbag
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   
4. Update the `.env.local` file with your API keys:
   ```
   CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   OPENAI_API_KEY=your_openai_api_key
   ```

5. Initialize Convex:
   ```bash
   npx convex dev
   ```

### Running the Application

- Start the development server:
  ```bash
  pnpm run dev
  ```
  The application will be available at `http://localhost:5173`

- Build for production:
  ```bash
  pnpm run build
  ```

- Preview the production build:
  ```bash
  pnpm run preview
  ```

### Development Tools

- Lint the codebase:
  ```bash
  pnpm run lint
  ```

## 📁 Project Structure

```
paperbag/
├── convex/              # Convex backend functions
│   ├── files.ts         # File handling
│   ├── image.ts         # Image processing
│   └── transactions.ts  # Transaction management
├── public/              # Static assets
├── src/
│   ├── assets/          # Frontend assets
│   ├── components/      # React components
│   ├── lib/             # Utility functions
│   ├── routes/          # Application routes
│   └── styles/          # CSS styles
└── types/               # TypeScript type definitions
```

## 🧩 How It Works

1. Users upload their photos to the application
2. The system processes the images using AI models
3. Users can select from various cartoon styles
4. The transformed images are displayed with before/after comparison
5. Users can download or share their cartoonified images

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ❓ Troubleshooting

### Common Issues

- **API Connection Errors**: Make sure your API keys are correctly set in the `.env.local` file
- **Convex Development Server**: If you encounter errors with Convex, try running `npx convex dev` in a separate terminal
- **Image Processing Failures**: Check your OpenAI API usage limits and key validity

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [OpenAI](https://openai.com) for providing powerful image processing capabilities
- [Convex](https://www.convex.dev/) for the backend infrastructure
- All the contributors who have helped make this project better

---

<div align="center">
Made with ❤️ by [Micky](https://github.com/michaelshimeles)
</div>
