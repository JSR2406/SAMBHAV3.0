# Sambhav 3.0 Techfest

The React and Vite website for the Sambhav 3.0 college techfest at DY Patil College of Engineering, Akurdi. It lets visitors browse the event catalog, open individual event pages, and view leaderboard, contact, and FAQ information.

## Project layout

| Path | Purpose |
| --- | --- |
| [src/main.jsx](src/main.jsx) | React Router configuration and application entry point |
| [src/components/Events](src/components/Events) | Event catalog |
| [src/components/EventDetails](src/components/EventDetails) | Event detail pages at `/event-details/:id` |
| [src/components/Leaderboard](src/components/Leaderboard) | Leaderboard UI |
| [src/data/leaderboardData.js](src/data/leaderboardData.js) | Bundled leaderboard data |
| [public](public) | Static assets |
| [vercel.json](vercel.json) | SPA rewrite for direct visits to nested routes |

## Run locally

Use Node.js 22.12 or later and npm.

```bash
npm ci
npm run dev
```

Open the address Vite prints. Run `npm run lint` for linting and `npm run build` to generate `dist/`. For a local preview of that build, use `npm run preview`.

## Team

Built by the Sambhav 3.0 techfest team. [Janmejay Singh Rathore](https://github.com/JSR2406) led the technical team.
