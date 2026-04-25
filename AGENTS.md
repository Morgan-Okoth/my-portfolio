# Kilo Agent Workflows

## Available Commands

### Build & Preview
```bash
npm run dev      # Start Vite dev server (port 3000)
npm run build    # Build for production
npm run serve    # Serve static files
```

### Lint & Type Check
```bash
npm run lint          # No linter configured
npm run typecheck     # No type checker configured
```

### Git Workflow
```bash
git status           # Check working tree
git add .           # Stage all changes
git commit -m "msg" # Commit changes
git push            # Push to remote
```

## Project Structure

```
my-portfolio/
├── index.html          # Main portfolio page
├── package.json        # npm scripts & metadata
├── vite.config.js      # Vite configuration
├── README.md           # Project documentation
├── .gitignore          # Git ignore rules
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Pages deployment
└── AGENTS.md           # This file
```

## Deployment Targets

- **Railway**: `railway up` (requires Railway CLI)
- **Vercel**: `vercel` (requires Vercel CLI)
- **GitHub Pages**: Automated via GitHub Actions workflow
