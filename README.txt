TRACCIATORE SPESE REVAMPING – v3.5
Repository: Tracciatore-Spese-Revamping

- Nuovo Movimento compatto, descrizioni alfanumeriche, categoria con emoji nel menu.
- Emoji personalizzate dalla tastiera; importazione JSON storica con emoji automatiche se mancanti.
- Selezione spese su più periodi; totale cumulativo fino a Totale/Annulla.
- Navigazione Liquid Glass da 56 px e safe area; nuovo selettore mese con intervallo e animazione.
- Blocco overscroll e azioni di selezione/clipboard gestibili dal browser.
- Dati locali e periodo finanziario del 27 invariati. Cache aggiornata.

Installazione: effettuare un backup completo JSON, estrarre lo ZIP e sovrascrivere i file nella root del repository. Non caricare il backup personale su GitHub. Dopo il deploy aprire l'app online e poi verificare offline. Non cancellare i dati di Safari.

Collaudo: Chromium viewport 393 x 852, storage simulato in memoria; verificati creazione categorie, inserimento movimento, somma tra periodi, trascinamento nav, hide/show, eventi ai bordi, clipboard, import JSON e dark mode. Service worker verificato sintatticamente, non collaudato su iPhone fisico.
