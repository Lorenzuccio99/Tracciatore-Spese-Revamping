TRACCIATORE SPESE REVAMPING – v3.6
Repository: Tracciatore-Spese-Revamping

- Selettore mese compatto da 46 px, navigazione animata conservata.
- Barra Liquid Glass a sole icone, 52 px, allineata al limite della safe area; auto-hide e trascinamento mantenuti.
- Nuovo Movimento, impostazioni e dialoghi centrati nella zona visibile, adattabili alla tastiera.
- Impostazioni organizzate per gruppi, pannelli espandibili, scroll interno.
- Conferme eliminazione interne e notifiche centrate.
- Chiave di archiviazione, importazione JSON e calcoli finanziari invariati.

Installazione: effettuare un backup completo JSON, estrarre lo ZIP e sovrascrivere i file nella root del repository. Non caricare i propri backup su GitHub. Dopo il deploy aprire online con ?v=3.6. Non cancellare i dati di Safari.

Collaudo Chromium: viewport 393 x 852, safe area simulata 59/34 px, archiviazione simulata; test cambio mese, inserimento, impostazioni, Dark Mode, conferme, importazione file JSON storico, somma tra mesi, drag, auto-hide, grafici e viewport ridotto a 500 px. Nessun errore JS rilevato nei test. Service worker verificato sintatticamente; il server locale era bloccato, quindi avvio offline e Safari iPhone fisico non collaudati.


Versione 3.7 – Premium Design & Motion
Palette, materiali, contorni, barra glass, grafico mensile interattivo con linea guida, animazioni brevi e dettaglio residuo budget. Dati e importazione invariati.
Test Chromium 393×852 con storage simulato; offline da verificare su iPhone.


v3.8: gestione VisualViewport e tastiera con intestazione fissa e form scorrevole; header compatto; riflessi e lente elastica senza loop di rendering. Dati e backup invariati.

V3.9: header opaco isolato, dimmer senza blur, lente continua, riflessi al tocco, morph SVG mensile a durata finita e transizioni barre dal valore precedente, animazioni registro. Storage e backup invariati.
