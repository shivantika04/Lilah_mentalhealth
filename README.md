# Lilah — Mental Health Support Web App

A React web app for daily mental wellness support, built for the IEEE Techideate Hackathon (honorable mention).

## What it does

- **Daily Affirmations** — a page of rotating positive affirmation cards to support daily mental wellness habits
- **About** — information section explaining the app's purpose
- **Feedback** — a form for users to submit their name, email, and feedback on the app
- Client-side routing between pages via `react-router-dom`

## Pages / Components

| Route | Component | Purpose |
|---|---|---|
| `/` | `IntroSec` | Landing/intro section |
| `/about` | `About` | About the project |
| `/daily` | `Daily` | Daily affirmation cards |
| `/feedback` | `Feedback` | User feedback form |

Shared components: `Navbar`, `InfoCard`, `Info`.

## Running it locally

```bash
npm install
npm start
```

Runs at `http://localhost:3000`.

## Tech

React 18, React Router, CSS

## Background

Built as part of a collaborative hackathon team submission (IEEE Techideate), recognized with an honorable mention.
