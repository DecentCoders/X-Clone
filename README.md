# X-Clone | DecentCoders
[![Nuxt 3](https://img.shields.io/badge/Nuxt-3-00DC82?logo=nuxt.js)](https://nuxt.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?logo=tailwindcss)](https://tailwindcss.com/)
[![Last Commit](https://img.shields.io/github/last-commit/DecentCoders/X-Clone)](https://github.com/DecentCoders/X-Clone/commits/main)

A fully functional, open-source clone of X (formerly Twitter) built with Nuxt 3. This project replicates the core social media experience of X, with a modern, type-safe front-end architecture, responsive UI, and essential social platform features. It serves as both a production-ready foundation for custom social media projects and a practical learning resource for modern Vue/Nuxt front-end development.

## ✨ Key Features
### Implemented Core Features
- Responsive home feed with post display and consistent layout controls
- Post creation with integrated emoji picker for rich content
- User profile customization and editing functionality
- Follow/unfollow user interaction system
- Global loading indicators for smooth, seamless user experience
- Accessible tooltip UI elements with fully resolved interaction bugs
- Username validation and fixed username-related edge cases
- Max post height constraints for uniform feed layout

### Upcoming Features (Roadmap)
- Real-time post updates and in-app notifications
- Image/video media upload support for posts
- Direct private messaging between users
- Like, retweet, and comment functionality
- Hashtag and @mention support with search integration
- Secure user authentication and authorization
- Advanced search for posts, users, and trending topics
- Dark/light mode theme toggle
- Profile analytics dashboard

## 🛠️ Tech Stack
### Core Framework & Runtime
- **Nuxt 3**: Full-stack Vue 3 framework with SSR/SSG support, file-based routing, and native server API capabilities
- **Vue 3**: Progressive JavaScript framework with Composition API for reactive, component-based UI development
- **TypeScript**: End-to-end type safety for consistent, maintainable, and bug-resistant code

### Styling & UI
- **Tailwind CSS**: Utility-first CSS framework for rapid, responsive, and consistent UI development
- Custom reusable component library for X-like UI/UX patterns

### State & Backend
- **Pinia**: Official Vue state management library (via `stores` directory) for global app state management
- **Nuxt Server API**: Built-in server backend for handling API requests, data processing, and business logic

### Tooling & Compatibility
- Cross package manager support: npm, yarn, pnpm, bun
- TypeScript configuration for strict type checking
- Git version control with conventional commit history

## 📁 Project Structure
This project follows the official Nuxt 3 directory convention for optimal organization and scalability:
```
X-Clone/
├── assets/          # Global static assets
│   └── css/         # Global styling and custom CSS
├── components/      # Reusable Vue 3 UI components
├── layouts/         # Page layout templates for consistent app structure
├── pages/           # File-based routing for all application pages
├── plugins/         # Nuxt plugins (emoji picker, custom utilities)
├── public/          # Static public assets accessible directly via URL
├── server/          # Backend server API endpoints and business logic
├── stores/          # Pinia global state management modules
├── .gitignore       # Git ignore configuration
├── app.vue          # Root Vue application component
├── nuxt.config.ts   # Core Nuxt 3 application configuration
├── package.json     # Project dependencies, scripts, and metadata
├── tailwind.config.ts # Tailwind CSS custom theme and configuration
├── tsconfig.json    # TypeScript compiler configuration
└── yarn.lock        # Yarn dependency lock file
```

## 🚀 Getting Started
### Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- **Node.js**: Version 18.x or higher (required for Nuxt 3)
- A package manager: npm, yarn, pnpm, or bun

### Installation
1. Clone the repository to your local machine:
```bash
git clone https://github.com/DecentCoders/X-Clone.git
cd X-Clone
```

2. Install project dependencies using your preferred package manager:
```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

### Local Development Server
Start the hot-reloading development server at `http://localhost:3000`:
```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev

# bun
bun run dev
```
The server will automatically reload when you make changes to any source files.

### Production Build
Build the optimized, minified application for production deployment:
```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build

# bun
bun run build
```
Nuxt will automatically optimize your application for maximum performance in production.

### Preview Production Build
Locally validate your production build before deploying to a live environment:
```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview

# bun
bun run preview
```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! We appreciate all contributions to improve and expand this project.

To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes and commit them with a descriptive message (`git commit -m 'Add amazing new feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please ensure your code follows the project's TypeScript and styling conventions, and test all changes before submitting a PR.


## 🙏 Acknowledgements
- Built with [Nuxt 3](https://nuxt.com/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Inspired by X (formerly Twitter)
- Extended from the official Nuxt 3 Minimal Starter template
