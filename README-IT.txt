DOLCEMAGICO — VERSIONE ANDROID PWA

Questa cartella contiene una web app installabile (PWA), non un APK pubblicato sul Play Store.
Funziona in Chrome Android dopo essere stata pubblicata su un indirizzo HTTPS.

PUBBLICAZIONE SEMPLICE CON GITHUB PAGES
1. Da computer, crea o accedi a un account GitHub.
2. Crea un nuovo repository pubblico chiamato dolcemagico.
3. Carica TUTTI i file di questa cartella nella cartella principale del repository.
4. Apri Settings > Pages.
5. In "Build and deployment", scegli Deploy from a branch, branch main e folder /(root), poi Save.
6. Attendi la pubblicazione. GitHub mostrerà un indirizzo simile a https://TUONOME.github.io/dolcemagico/
7. Apri quell'indirizzo sul telefono Android con Google Chrome.
8. Tocca ⋮ > Installa app (oppure Installa e crea scorciatoia) > Installa.
9. Troverai DolceMagico nell'elenco delle app e potrai spostare l'icona sulla schermata Home.

NOTE IMPORTANTI
- HTTPS è necessario per il service worker e per la modalità offline.
- Le ricette vengono suggerite localmente da modelli inclusi nell'app; non c'è ancora un servizio AI collegato.
- L'immagine del dolce è un'illustrazione incorporata nell'app, non una fotografia generata su richiesta.
- Le ricette salvate restano nel browser/dispositivo e non vengono sincronizzate tra telefoni.
- Per un'app AI completa con foto generate dinamicamente serve collegare un backend/API sicuro: non inserire chiavi API segrete nel codice pubblicato.
