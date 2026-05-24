# Allo Inventory Reservation System

## Stack
- Next.js
- TypeScript
- Prisma
- PostgreSQL
- Tailwind CSS

## Setup

```bash
npm install
```

Create `.env`:

```env
DATABASE_URL=YOUR_DATABASE_URL
```

Run migration:

```bash
npx prisma migrate dev
```

Run seed:

```bash
npx tsx prisma/seed.ts
```

Run app:

```bash
npm run dev
```
