# Virus Quarantine App

A React-based dashboard for managing quarantined patients, tracking temperature, and handling patient discharge.

## Features

- Staff login
- Patient list with temperature monitoring
- Status indicators (stable, elevated, critical)
- Temperature input and updates
- Patient discharge functionality

## Getting Started

### Prerequisites
- Node.js 14+ and npm installed

### Installation

```bash
npm install
```

### Development

```bash
npm start
```

Runs the app in development mode at [http://localhost:3000](http://localhost:3000).

### Build

```bash
npm run build
```

Builds the app for production to the `build` folder.

## Deployment

### Deploy to Vercel

**Option 1: Using Vercel CLI**
```bash
npm install -g vercel
vercel
```

**Option 2: Using GitHub**
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project" and import your GitHub repo
4. Vercel will auto-deploy on every push

## Technologies

- React 18
- CSS (vanilla)
- Context API for state management
