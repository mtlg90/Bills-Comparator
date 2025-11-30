# Confronto Bollette — Luce & Gas

App React + Firebase per confrontare costi e consumi di bollette luce e gas, con sincronizzazione tra dispositivi.

## Setup

1. Clona la repo o estrai lo zip.
2. Installa le dipendenze:

   ```bash
   npm install
   ```

3. Crea un progetto Firebase e prendi i parametri di configurazione.
4. Crea un file `.env` nella root con:

   ```bash
   VITE_FIREBASE_API_KEY=...
   VITE_FIREBASE_AUTH_DOMAIN=...
   VITE_FIREBASE_PROJECT_ID=...
   VITE_FIREBASE_STORAGE_BUCKET=...
   VITE_FIREBASE_MESSAGING_SENDER_ID=...
   VITE_FIREBASE_APP_ID=...
   ```

5. Avvia in sviluppo:

   ```bash
   npm run dev
   ```

6. Per il deploy (Vercel/Netlify): build command `npm run build`, dir di pubblicazione `dist`.
