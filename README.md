# BailFlow - Gestion Locative Intelligente

SaaS pour proprietaires bailleurs. Gerez vos baux, loyers, documents legaux et laissez l'IA rediger a votre place.

## Stack

- Next.js 14 (App Router)
- PostgreSQL + Prisma
- Stripe (paiements)
- Claude API / Anthropic (IA)
- Resend (emails)
- PDFKit (generation PDF)
- Tailwind CSS

## Fonctionnalites

- Tableau de bord bailleur : biens, locataires, loyers en retard
- Gestion des baux : creation, renouvellement, resiliation
- Quittances PDF generees automatiquement et envoyees par email
- Revision automatique IRL avec alertes
- IA : redaction de courriers, relances, etats des lieux (Claude API)
- Depot de garantie en ligne via Stripe

## Demarrage

bash
npm install
npx prisma migrate dev
npm run dev


Variables requises : DATABASE_URL, STRIPE_SECRET_KEY, ANTHROPIC_API_KEY, RESEND_API_KEY, JWT_SECRET