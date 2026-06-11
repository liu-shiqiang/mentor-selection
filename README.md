# 学生选导师系统 (Student Mentor Selection System)

A modern web application for managing and facilitating the student mentor selection process. Built with Vue 3, TypeScript, and Vite for optimal performance and developer experience.

## Features

- **Student Dashboard**: Browse and filter available mentors
- **Mentor Management**: View mentor profiles, specialties, and availability
- **Selection System**: Intuitive interface for students to submit mentor preferences
- **Real-time Updates**: Dynamic data synchronization across the application
- **Responsive Design**: Seamless experience on desktop and mobile devices

## Tech Stack

- **Frontend Framework**: Vue 3
- **Language**: TypeScript
- **Build Tool**: Vite
- **Styling**: CSS
- **IDE Support**: VSCode with Volar

### Language Composition
- Vue: 51.3%
- TypeScript: 39.1%
- CSS: 8.2%
- HTML: 1.4%

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/)
- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur)
- [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)

## Project Setup

### Install Dependencies

```sh
npm install
```

### Development

Run the development server with hot-reload:

```sh
npm run dev
```

The application will be available at `http://localhost:5173`

### Production Build

Type-check, compile, and minify for production:

```sh
npm run build
```

### Linting

Check code quality with ESLint:

```sh
npm run lint
```

## Project Structure

```
src/
├── components/        # Reusable Vue components
├── views/            # Page components
├── stores/           # State management
├── types/            # TypeScript type definitions
├── assets/           # Static assets
└── App.vue           # Root component
```

## Usage

1. Start the development server: `npm run dev`
2. Open your browser and navigate to the local development URL
3. Browse mentors, view their profiles, and submit your preferences
4. Build for production: `npm run build`

## Development Notes

### Type Checking

TypeScript type checking uses `vue-tsc` instead of the default `tsc` CLI. This ensures proper type support for `.vue` files.

For faster type checking in your editor, consider enabling Volar's Take Over Mode:

1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
2. Find `TypeScript and JavaScript Language Features` and disable it for this workspace
3. Reload VSCode with `Developer: Reload Window`

### Configuration

See [Vite Configuration Reference](https://vitejs.dev/config/) for build and development server customization options.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Author

liu-shiqiang
