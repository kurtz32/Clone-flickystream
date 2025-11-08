# FlickyStream Clone

This is a cloned version of flickystream.ru created using wget.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the server:
   ```bash
   npm start
   ```

For development with auto-restart:
```bash
npm run dev
```

## Deployment

This project is ready for deployment on platforms like Heroku, Vercel, or GitHub Pages (with a static build).

For Heroku:
- Push to GitHub
- Connect Heroku app to the GitHub repo
- Deploy

For Vercel:
- Import the project from GitHub
- Vercel will automatically detect and deploy

## Structure

- `flickystream.ru/` - Cloned website files
- `server.js` - Express server for serving the static files
- `package.json` - Node.js dependencies and scripts