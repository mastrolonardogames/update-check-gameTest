# Pubblicare version.json su GitHub Pages

## 1. Crea un account su https://github.com

## 2. Crea un nuovo repository (pubblico)
- Nome esempio: `update-check`
- Lascia vuoto (senza README)

## 3. Carica questi file
- Clicca su "Add file" → "Upload files"
- Trascina `version.json`, `index.html`, `README.md`
- Commit ("Salva")

## 4. Attiva GitHub Pages
- Vai in **Settings** → **Pages**
- Scegli:
  - Branch: `main`
  - Folder: `/ (root)`
- Clicca Save

Il sito sarà accessibile da:
https://tuo-username.github.io/update-check/version.json

## 5. (Opzionale) Usa il tuo dominio GoDaddy
- Crea un file `CNAME` con dentro solo:
update.tuodominio.com

- Vai su GoDaddy → DNS → Aggiungi record `CNAME`:
  - Nome: `update`
  - Tipo: `CNAME`
  - Valore: `tuo-username.github.io`

Attendi fino a 24h per la propagazione.
