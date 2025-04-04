# DeliveryPal

DeliveryPal is a platform that connects users with local services and businesses in their area, featuring secure escrow payments and real-time location tracking.

## Features

- User authentication with email/password and Google OAuth
- Role-based access control (customers, businesses, drivers)
- Real-time location services to locate shops and services near users
- Secure escrow payment system
- Business and driver dashboards
- Dark/light mode theme support

## Tech Stack

- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL
- NextAuth.js for authentication
- Google Maps API for location services

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- PostgreSQL database (or use Vercel Postgres)

### Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
# Database
DATABASE_URL="postgresql://username:password@localhost:5432/deliverypal"

# NextAuth
NEXTAUTH_SECRET="your-nextauth-secret"
NEXTAUTH_URL="http://localhost:3000"

# Google OAuth
GOOGLE_CLIENT_ID="your-google-client-id"
GOOGLE_CLIENT_SECRET="your-google-client-secret"

# Maps
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY="your-google-maps-api-key"
