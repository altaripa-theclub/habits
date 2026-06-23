# Giorni di fila

Web app per tracciare i giorni di fila e la check-list quotidiana
(7 pagine · nessuna scommessa · 100g proteine · allenamento).

I dati restano salvati nel browser del dispositivo dove apri l'app
(non vengono caricati da nessuna parte). Funziona anche offline.

---

## 1. Caricare su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `giorni-di-fila`).
2. Carica TUTTI i file di questa cartella nella radice del repo:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `favicon.png`
   - (`README.md` è facoltativo)
3. Vai su **Settings → Pages**.
4. In "Build and deployment", sotto "Source" scegli **Deploy from a branch**,
   seleziona il branch `main` e la cartella `/ (root)`, poi **Save**.
5. Dopo un minuto avrai un indirizzo tipo:
   `https://TUONOME.github.io/giorni-di-fila/`

> Importante: serve HTTPS perché funzionino l'installazione e l'offline.
> GitHub Pages lo fornisce già, quindi sei a posto.

---

## 2. Installare sul telefono

Apri l'indirizzo del passo 5 nel browser del telefono.

**iPhone (Safari)**
1. Tocca il tasto Condividi (quadrato con freccia in su).
2. "Aggiungi alla schermata Home".
3. Conferma: comparirà l'icona come un'app normale.

**Android (Chrome)**
1. Apri il menu (tre puntini in alto a destra).
2. "Installa app" oppure "Aggiungi a schermata Home".
3. Conferma.

Da quel momento la apri dall'icona, a schermo intero, e funziona anche
senza connessione.

---

## 3. Note

- Usa sempre lo stesso telefono/browser: i dati sono salvati lì.
- Il pulsante **Scarica Excel** genera un file `.xlsx` con il diario
  giornaliero e un riepilogo (per scaricare l'Excel serve la connessione).
- Per aggiornare l'app in futuro: ricarica i file modificati nel repo.
  Alla prossima apertura il service worker prende la versione nuova.
