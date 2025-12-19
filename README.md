Agridata Frontend (React + Vite + Tailwind)

How to run:
1. unzip this folder to a location
2. open terminal in the folder
3. run: npm install
4. run: npm run dev
5. open http://localhost:3000

Configuration:
- API base URL is in src/api/api.js. Change BASE to: 'http://localhost/agridata_backend/public/index.php?url='
- The frontend expects the PHP backend routes to be available as defined.

Notes:
- Pages created: Dashboard, Parcelles, Cultures, Activites, Meteo, Rapports, Users
- Charts implemented with recharts on dashboard. Tailwind for styling.
