# WIP

My Next.js starter template kit to build scalable web-apps.

## Checklist

- [x] Next.js 13
- [x] React
- [x] TypeScript
- [x] ESLint
- [x] Prettier - format code
- [x] Husky & Lint Staged - Run scripts before commiting
- [x] Absolute Path Imports - Import using the `@` prefix
- [x] airbnb styleguide for typescript
- [ ] Conventional Commit Linting
- [ ] Prebuilt Components
- [ ] Custom 404 Page
- [ ] VSCode workspace settings, snippets and recommended extensions
- [ ] Libraries that you should use
  - [ ] Tailwind CSS
  - [ ] Storybook - for building UI Components in isolation
  - [ ] Zustand - State management
  - [ ] React Query - Data fetching
  - [ ] React Hook Form or Alternative - Deal with forms easily
  - [ ] NProgress - cool progress bar
  - [ ] got/axios - request client
  - [ ] js-cookie - manipulate cookies
  - [ ] day.js - date and time
  - [ ] ...
- [ ] Testing
  - [ ] Jest - Unit testing
  - [ ] Cypress - End-to-End testing
- [ ] [Read more docs](https://nextjs.org/docs) - Pending
- [ ] Boiler plate code like user authentication using refreshToken & accessToken
- [ ] 🚀 Production-ready yet?

## Usage

TODO

## Documentation

### Requirements

- Node.js >= 16

### Directory Structure

### Scripts

- `npm run dev`
- `npm run build` - Create production build
- `npm run start` - Start in production mode
- `npm run lint` - Run ESLint project wide
- `npm run format` - Format all files project wide, ignores unknown files

### Absolute Paths or Imports

To import components or files, use the `@` prefix.

```tsx
import { Button } from '@/components/Button';

// Import public files

import avatar from '@/public/avatar.png';
```

## TODO

- [ ] Template for Svelte.js
- [ ] Template for Solid.js

## License

MIT
