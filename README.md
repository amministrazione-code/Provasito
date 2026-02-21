# Book Cartolab - Sito Web

Landing page del sito di **Book Cartolab**, una copisteria e cartoleria situata in **Via Bologna 88, Torino**.

## Cosa fa il sito

Il sito presenta i servizi di stampa e cartoleria offerti dal negozio, permettendo ai clienti di scoprire le opzioni disponibili e richiedere preventivi. Le sezioni principali sono:

### Servizi offerti

- **Stampa Online** — Carica il tuo file, ricevi un preventivo istantaneo e scegli tra la consegna a domicilio o il ritiro in negozio.
- **Copisteria Self-Service** — Postazioni di stampa fai-da-te con prezzi trasparenti (€0,05 B/N, €0,10 colore).
- **Rilegatura** — Rilegatura a spirale, pinzatura e brossura per tesi, documenti e cataloghi.
- **Grandi Formati** — Stampa su plotter fino al formato A0 per manifesti, disegni tecnici e planimetrie.
- **Spedizioni** — Servizio di spedizione con corrieri convenzionati (GLS, BRT, TNT, FedEx, Poste Italiane), con ritiro e consegna in 24 ore.
- **Cartoleria & Materiale Scolastico** — Oltre 10.000 articoli: libri di testo, cancelleria, materiale per l'ufficio e la scuola.

## Stack tecnologico

Il sito è un'applicazione web **statica pura**, senza dipendenze esterne o framework:

| Tecnologia | Utilizzo |
|---|---|
| HTML5 | Struttura semantica della pagina |
| CSS3 | Stile, animazioni, layout responsive |
| Google Fonts | Tipografia (Plus Jakarta Sans) |

Nessun JavaScript, nessun backend, nessun build step: basta servire i due file `index.html` e `style.css`.

## Struttura del progetto

```
Provasito/
├── index.html   # Pagina principale
└── style.css    # Stili e animazioni
```

## Come avviare il sito in locale

Apri semplicemente `index.html` nel browser, oppure usa un server locale:

```bash
npx serve .
# oppure
python3 -m http.server 8000
```

Il sito sarà raggiungibile su `http://localhost:8000`.

## Informazioni negozio

- **Indirizzo:** Via Bologna 88, Torino
- **Servizio rapido:** fino a 60 pagine/minuto
- **Spedizioni:** consegna garantita entro le 24 ore per pacchi ricevuti entro le 16:00
