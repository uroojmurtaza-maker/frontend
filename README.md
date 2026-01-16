# OMS Frontend (React + Vite)

Employee management frontend built with React, Vite, Tailwind CSS, and Ant Design.

## Prerequisites

- Node.js 18+ (recommended)
- npm (comes with Node)

## Setup

1. Install dependencies:
   - `npm install`

2. Configure environment variables:
   - Create a `.env` file in the project root.
   - Add the API base URL:

```
VITE_API_URL=http://localhost:5000/api
```

This project reads `VITE_API_URL` in `src/hooks/api-handler.js`.

## Run the app

- Start the dev server: `npm run dev`
- Build for production: `npm run build`
- Preview production build: `npm run preview`
- Lint: `npm run lint`

## Notes

- Ensure the backend API is running and reachable at `VITE_API_URL`.
