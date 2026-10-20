# Walk2Earn Ghana

Walking rewards app for Ghana - Earn rewards while staying healthy!

## Features

- Track your daily walking distance
- Earn points for every kilometer walked
- Redeem rewards from local partners
- Join challenges with friends
- Improve your health while earning

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- Vite for build tooling
- Vercel Web Analytics for tracking

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm (or yarn/pnpm/bun)

### Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Vercel Analytics

This project includes Vercel Web Analytics for tracking page views and user interactions.

### How it works

The analytics script is injected in the `<head>` section of `index.html`:

```html
<script>
  window.va = window.va || function () { (window.vaq = window.vaq || []).push(arguments); };
</script>
<script defer src="/_vercel/insights/script.js"></script>
```

### Custom Events

You can track custom events using:

```javascript
window.va('event', { name: 'event_name' });
```

### Enabling Analytics

1. Deploy your project to Vercel
2. Navigate to your project's Analytics section in the Vercel dashboard
3. Click the Enable button
4. Deploy again to activate analytics tracking

## Deployment

This project is configured for deployment on Vercel:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## License

MIT
