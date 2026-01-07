# Melody Client

<div align="center">

**The AI Video Studio** - Transform ideas into short videos that captivate.

[![Next.js](https://img.shields.io/badge/Next.js-15.1.4-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0.0-blue)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.1-38bdf8)](https://tailwindcss.com/)

</div>

---

## About

Melody Client is a modern, AI-powered video editing platform built with Next.js and React. It provides a comprehensive web-based video editor that enables users to create professional short-form videos with an intuitive interface, powerful editing tools, and AI assistance.

This project is part of the Melody ecosystem, an AI platform that delegates tools to specific LLMs according to user demand, including image generation, video generation, music generation, PDF conversion, web browsing, and more.

## Features

### Core Video Editing
- **Multi-track Timeline**: Professional timeline editor with support for multiple video and audio tracks
- **Clip Management**: Drag-and-drop clip placement, trimming, splitting, and transformation
- **Real-time Preview**: Live preview with synchronized playback controls
- **Zoom Controls**: Precise timeline navigation with zoom in/out functionality
- **Aspect Ratio Support**: Multiple aspect ratios including 9:16 (TikTok), 16:9 (YouTube), 1:1 (Instagram), and 21:9 (Cinematic)

### Editing Tools
- **Animations**: Add dynamic animations to clips
- **Assets Library**: Upload and manage video, audio, and image assets
- **Captions**: Automatic and manual caption generation with style customization
- **Filters**: Apply visual filters and effects
- **Stickers**: Add stickers and overlays to videos
- **Text Overlays**: Rich text editing with customizable styles
- **Voiceover**: Record and add voiceovers
- **Music**: Background music integration
- **Transitions**: Smooth transitions between clips

### AI Features
- **AI Assistant Panel**: Interactive AI assistant for video editing guidance
- **Chat Interface**: Real-time chat with AI for editing suggestions and help
- **Smart Editing**: AI-powered editing recommendations

### Project Management
- **Project Dashboard**: Create, view, and manage multiple video projects
- **Storage Management**: Track storage usage with upgrade options
- **Project Feed**: Browse and organize your video projects

### User Interface
- **Modern Design**: Beautiful, responsive UI with smooth animations
- **Draggable Panels**: Customizable workspace with resizable panels
- **Fullscreen Mode**: Immersive fullscreen editing experience
- **Dark Theme**: Eye-friendly dark theme optimized for video editing

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd melody-client
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
melody-client/
├── src/
│   ├── app/                    # Next.js app router pages
│   │   ├── api/               # API routes
│   │   ├── create/            # Project creation page
│   │   ├── edit/              # Video editor page
│   │   ├── pricing/           # Pricing/subscription page
│   │   └── page.tsx           # Home page
│   ├── components/
│   │   ├── common/            # Shared components (Navbar, Logo)
│   │   ├── create/            # Project creation components
│   │   ├── editor/            # Video editor components
│   │   │   ├── buttons/      # Editor action buttons
│   │   │   ├── panels/       # Tool panels (Assets, Filters, etc.)
│   │   │   ├── timeline/     # Timeline components
│   │   │   └── preview/      # Video preview components
│   │   ├── pricing/          # Pricing page components
│   │   └── ui/               # Reusable UI components
│   ├── constants/            # Application constants
│   ├── store/                # Zustand state management
│   ├── types/                # TypeScript type definitions
│   └── utils/                # Utility functions
├── public/                   # Static assets
└── package.json
```

## Tech Stack

- **Framework**: [Next.js 15.1.4](https://nextjs.org/) (App Router)
- **UI Library**: [React 19](https://react.dev/)
- **Language**: [TypeScript 5](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS 3.4.1](https://tailwindcss.com/) + [Sass](https://sass-lang.com/)
- **State Management**: [Zustand 5.0.2](https://zustand-demo.pmnd.rs/)
- **Icons**: [Lucide React](https://lucide.dev/) + [React Icons](https://react-icons.github.io/react-icons/)
- **Drag & Drop**: [React Draggable](https://github.com/react-grid-layout/react-draggable)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **File Upload**: [Formidable](https://github.com/node-formidable/formidable)

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Key Features in Detail

### Video Editor
The core editor component (`VideoEditor.tsx`) provides:
- Multi-panel layout with toolbar, tool panels, preview, and timeline
- Real-time video playback synchronization
- Draggable dividers for customizable workspace
- Zoom controls for precise timeline editing
- AI assistant panel integration

### Timeline System
- Multi-track support (video and audio tracks)
- Clip manipulation (drag, resize, split, delete)
- Ruler with time markers
- Zoom slider for detailed editing
- Track headers with controls

### State Management
Uses Zustand for efficient state management:
- Editor state (tracks, clips, selected items, playback state)
- User state (authentication, preferences)
- Real-time synchronization across components

## Deployment

The easiest way to deploy this Next.js app is using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

For more deployment options, see the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

## License

This project is private and proprietary.

## Contributing

This is a private project. Contributions are by invitation only.

## Support

For support and inquiries, please contact the development team.

---

<div align="center">

Built with Next.js and React

</div>
