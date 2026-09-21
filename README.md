# 🎒🗣️ Taalspiegels · Specchi linguistici

**Live:** https://taalspiegels-specchi-linguistici-z3.vercel.app/

---

## 🇳🇱 Nederlands

### Wat is dit?
Eén overzichtspagina met alle Taalspiegels: taal-oefenapps om te spreken en na te zeggen (shadowing). Elke spiegel is een aparte app op een eigen adres; deze pagina brengt ze samen en linkt terug naar het Zaino-dashboard.

### De spiegels
| Taal | Link |
|---|---|
| Catalaans | https://rodionrask.vercel.app/ |
| Spaans | https://spechio-espanol.vercel.app/ |
| Italiaans | https://specchio-magico-shadowing-kdv7.vercel.app/ |
| Duits | https://zauberspiegel.vercel.app/ |
| Engels | https://magic-mirror-two-tawny.vercel.app/ |
| Nederlands | https://de-taal-toverspiegel.vercel.app/ |
| Frans | https://specchio-francais.vercel.app/ |

### Bestanden
| Bestand | Doel |
|---|---|
| `index.html` | De hele pagina (HTML, CSS en JavaScript in één bestand) |
| `manifest.webmanifest` | Maakt installeren als app mogelijk |
| `sw.js` | Service worker: cachet de pagina en de iconen |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App-iconen |

Alle bestanden staan in de hoofdmap (root) van de repo.

### Functies
- **Installeren:** een knop "Installeer" verschijnt zodra de browser dat toestaat.
- **Waardering:** drie stoplichtbolletjes (groen, oranje, rood); de waardering komt per mail binnen via [Web3Forms](https://web3forms.com).
- **Analytics:** Vercel Web Analytics, cookieloos.
- **Copyright:** © Jan den Hollander, in de voetregel en in de metadata.

### Instellen
1. Vervang in `index.html` `PLAK_HIER_JE_WEB3FORMS_KEY` door je eigen Web3Forms-key.
2. Zet in Vercel bij het project *Analytics* aan.
3. Upload alle bestanden naar de root van de repo (via de uploadfunctie van GitHub, niet via plakken); Vercel publiceert automatisch.

### Eigen bezoeken uitsluiten
Open op elk eigen apparaat eenmalig `…vercel.app/?owner=1`. Daarna telt je bezoek niet mee en wordt er geen waardering verstuurd. Met `?owner=0` zet je het weer uit.

### Nieuwe spiegel toevoegen
Kopieer in `index.html` een blok `<a class="tile" …>…</a>`, pas de link en de taalnaam aan en upload het bestand opnieuw.

---

## 🇮🇹 Italiano

### Che cos'è?
Un'unica pagina che raccoglie tutti gli specchi linguistici: app per esercitarsi a parlare e a ripetere (shadowing). Ogni specchio è un'app separata con il proprio indirizzo; questa pagina li riunisce e rimanda alla dashboard Zaino.

### Gli specchi
| Lingua | Link |
|---|---|
| Catalano | https://rodionrask.vercel.app/ |
| Spagnolo | https://spechio-espanol.vercel.app/ |
| Italiano | https://specchio-magico-shadowing-kdv7.vercel.app/ |
| Tedesco | https://zauberspiegel.vercel.app/ |
| Inglese | https://magic-mirror-two-tawny.vercel.app/ |
| Olandese | https://de-taal-toverspiegel.vercel.app/ |
| Francese | https://specchio-francais.vercel.app/ |

### File
| File | Scopo |
|---|---|
| `index.html` | L'intera pagina (HTML, CSS e JavaScript in un solo file) |
| `manifest.webmanifest` | Permette di installare la pagina come app |
| `sw.js` | Service worker: salva in cache la pagina e le icone |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Icone dell'app |

Tutti i file vanno nella cartella principale (root) del repository.

### Funzioni
- **Installazione:** compare un pulsante «Installa» non appena il browser lo permette.
- **Valutazione:** tre pallini da semaforo (verde, arancione, rosso); la valutazione arriva per e-mail tramite [Web3Forms](https://web3forms.com).
- **Analytics:** Vercel Web Analytics, senza cookie.
- **Copyright:** © Jan den Hollander, nel piè di pagina e nei metadati.

### Configurazione
1. In `index.html` sostituisci `PLAK_HIER_JE_WEB3FORMS_KEY` con la tua chiave Web3Forms.
2. In Vercel attiva *Analytics* per il progetto.
3. Carica tutti i file nella root del repository (con la funzione di caricamento di GitHub, non incollando); Vercel pubblica in automatico.

### Escludere le proprie visite
Su ogni tuo dispositivo apri una volta `…vercel.app/?owner=1`. Da quel momento la tua visita non viene conteggiata e non viene inviata alcuna valutazione. Con `?owner=0` si disattiva di nuovo.

### Aggiungere un nuovo specchio
In `index.html` copia un blocco `<a class="tile" …>…</a>`, cambia il link e il nome della lingua e ricarica il file.

---

© 2026 Jan den Hollander · jandenhollander@duck.com · vrij en niet-commercieel · libero e non commerciale
