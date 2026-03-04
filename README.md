# NEUROZEN - Nootropic Gum Landing Page

A premium landing page for NEUROZEN nootropic gum, featuring Swiss Dada design with bold typography, grid animations, and dark premium aesthetic.

![NEUROZEN Preview](./public/images/hero-bg.jpg)

## Features

- **Hero Section**: Animated grid collage with bold title blocks
- **Science Section**: Ingredient breakdown with research data
- **How It Works**: 4-step process visualization
- **Product Showcase**: 3D mouse parallax and floating animation
- **Flavor Collection**: Interactive color palette grid
- **Testimonials**: Customer reviews with slider
- **Brand Philosophy**: Diagonal split layout with glitch effect
- **Shopping Cart**: Full cart functionality with add/remove/quantity controls
- **Toast Notifications**: Success/error feedback system

## Tech Stack

- React 19 + TypeScript + Vite 7
- Tailwind CSS 3 with custom animations
- GSAP 3 with ScrollTrigger
- shadcn/ui components

## Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it `neurozen` (or any name you prefer)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Update Configuration

Open `package.json` and update the `homepage` field with your GitHub username:

```json
"homepage": "https://YOUR_GITHUB_USERNAME.github.io/neurozen"
```

Also update `vite.config.ts` if you used a different repository name:

```ts
base: '/neurozen/',  // Change this if your repo has a different name
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Deploy

```bash
npm run deploy
```

This will:
1. Build the project (`npm run build`)
2. Deploy the `dist` folder to the `gh-pages` branch

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Select **gh-pages** branch and **/(root)** folder
5. Click **Save**

Your site will be live at: `https://YOUR_GITHUB_USERNAME.github.io/neurozen`

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
├── public/
│   └── images/          # Static images
├── src/
│   ├── components/      # React components
│   ├── sections/        # Page sections
│   ├── hooks/           # Custom hooks (cart, toast)
│   ├── config.ts        # Site configuration
│   └── ...
├── dist/                # Build output (auto-generated)
└── package.json
```

## Customization

Edit `src/config.ts` to customize all content:
- Navigation links
- Hero text and images
- Product details and pricing
- Flavor options
- Testimonials
- Footer content

## License

MIT License - feel free to use this template for your own projects.
