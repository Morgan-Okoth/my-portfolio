# Morgan Okoth — Backend Developer Portfolio

Professional portfolio showcasing backend engineering work, focusing on system reliability, data integrity, and backend architecture for fintech and multi-tenant SaaS platforms.

## Local Development

```bash
# Install dependencies (optional - vanilla HTML/CSS)
npm install

# Start dev server
npm run dev

# Or serve statically
npm run serve
```

## Build

```bash
npm run build
```

## Deployment

### Railway

```bash
# Install Railway CLI
npm install -g @railway/cli

# Login
railway login

# Deploy
railway up
```

### Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

### GitHub Pages

```bash
# From project root
git branch -m gh-pages
# Or use GitHub Actions workflow
```

## Projects

1. **PayLink** — Payment & Invoice Management System (Flagship)  
   Financial state machines, idempotency, audit-safe transactions

2. **EduCore** — Multi-Tenant School Management SaaS  
   Tenant isolation at query level, RBAC, shared-schema architecture

3. **OrphanageTracker** — Student Accountability System  
   RBAC, audit logging, document management

## Tech Stack

- **Backend**: Laravel 11, PHP 8.2, MySQL
- **APIs**: RESTful API design, Sanctum authentication
- **Architecture**: Multi-tenancy, event sourcing patterns, state machines
- **DevOps**: Railway deployment, Git workflows, CI/CD
- **Data**: Relational modeling, indexing strategies, transaction management

## Contact

- **Website**: https://morganentp.dev
- **GitHub**: https://github.com/Morgan-Okoth
- **Location**: Kenya
- **Email**: morganokoth410@gmail.com
