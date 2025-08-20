Leaflet integration applied automatically by assistant script.

What was added/changed:
- components/MapClient.tsx  (client component using react-leaflet)
- pages/_app.tsx or pages/index.tsx sample created
- pages/mapa_leaflet.tsx  (sample page - open /mapa_leaflet)
- package.json updated/created to include leaflet and react-leaflet

Notes:
- After downloading, run `npm install` (or yarn) in the project root to install dependencies.
- If you use Mapbox tiles, add your token and change the TileLayer url accordingly.
- If your project uses TypeScript and strict settings, you may need small type fixes
  (MapClient.tsx was written in TSX and should compile in typical Next.js TS setups).
- If you want me to also run `npm install` and run build, tell me (I can only modify files here; installing requires running commands locally).

Files changed/created:
No app/pages folder detected — created pages/index.tsx sample and imported leaflet css in component.
Created pages/mapa_leaflet.tsx sample page that uses MapClient.
Created package.json with required dependencies (you should run npm install).

How to test locally:
1) unzip and cd into project root
2) npm install
3) npm run dev
4) open http://localhost:3000/mapa_leaflet

