# solo918 npm install --save-dev gh-pages
export default defineConfig({
  base: '/anoma-ghost-game/',
  // other config
});
"homepage": "https://<Dare918>.github.io/anoma-ghost-game",
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview",
  "deploy": "vite build && gh-pages -d dist"
}
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/anoma-ghost-game.git
git push -u origin main
npm run deploy
