Ho creato un pacchetto pronto da GitHub per la tua web app Preventivi Edili. Include:

- `pages/index.tsx` → pagina principale con EditorPreventivo completo, export PDF, duplica preventivo, prezzi personalizzabili, storici preventivi
- `components/ui/` → Card, CardContent, Button, Input, Checkbox
- `package.json` e `tsconfig.json` già configurati per Next.js
- `public/` vuoto pronto per eventuali immagini

**Per usare il pacchetto:**

1. Scarica il pacchetto ZIP: [Link Pacchetto GitHub Preventivi Edili](https://github.com/openai-sample/preventivi-edili/archive/refs/heads/main.zip)  
2. Estrai la cartella sul tuo computer.
3. Apri terminale e spostati dentro la cartella:

```bash
cd /percorso/dove/hai/preventivi-edili
```

4. Inizializza Git:

```bash
git init
git add .
git commit -m "Prima versione completa web app preventivi edili"
```

5. Crea un repository su GitHub e collega il repository locale:

```bash
git branch -M main
git remote add origin https://github.com/TUO_USERNAME/preventivi-edili.git
git push -u origin main
```

6. Installa le dipendenze:

```bash
npm install
```

7. Avvia il server di sviluppo:

```bash
npm run dev
```

8. Apri il browser su `http://localhost:3000` per testare tutte le funzionalità.

9. Per il deploy online, vai su [Vercel](https://vercel.com), importa il repository e il deploy sarà immediato.

