# Pharmaguida nuova direzione ottobre 2026

Apri `index.html` per navigare tra pagina aziendale, campagna bundle e brand book. Il sito di prova riprende il template Medilazar online: testata bianca, logo attuale, font del tema, ricerca, menu, accenti turchesi, schede prodotto e footer. Carousel, filtri e ricerca funzionano in locale. I pulsanti di aggiunta restano nelle schede con riscontro visivo. Il carrello dimostrativo e la simulazione ordini sono stati eliminati su richiesta. Le dieci pagine bundle-B01.html fino a bundle-B10.html mostrano i dettagli dei kit. La proposta non è pubblicata su pharmaguida.com, come richiesto alla consegna.

## Contenuto della consegna

- `azienda.html`: nuova pagina aziendale responsive con famiglia nuova, ricerca, formule, storia, team e contatti.
- `bundle.html`: dieci bundle, descrizioni estese, prezzi e download.
- `prodotti.html`: dieci promesse di prodotto riscritte con composizioni e benefici attribuiti agli ingredienti corretti.
- `carousel.html`: simulazione navigabile del carousel, con composizione dedicata al mobile.
- `brand.html`: posizionamento, palette, tipografia, fotografia, voce e regole d’uso del logo.
- `banners/B01.png` fino a `B10.png`: dieci fascioni da **1810 × 550 px**, stessa dimensione delle immagini del carousel pubblico. Anche in WebP.
- `mobile/B01.png` fino a `B10.png`: dieci varianti da **750 × 1000 px**, anche in WebP.
- `Pharmaguida_Brand_Positioning_LOGO_UFFICIALE_2026-10-21.pptx` e `.pdf`: presentazione di 16 slide, con testi modificabili nel PowerPoint e immagini incorporate.
- `Pharmaguida_Testi_SEO_e_Bundle.docx`: copy aziendale, testi lunghi, promesse di prodotto, SEO e fonti.
- `MIA_PRIMISSIMA_MAIL_REVISIONATA.docx`: mail revisionata e integrata con call e reel. Il file originale in PHARMAGUIDA_SUPER_BRIEFING è stato aggiornato; la versione precedente è conservata accanto con suffisso PRIMA_REVISIONE_2026-10-20.
- `Prezzi_verificati.csv`: confronto economico dei dieci kit.
- `azienda-schema.json`: proposta di aggiornamento del grafo Yoast, da integrare nel grafo esistente.
- `assets/`: scene lifestyle e ritratti revisionati, fotografie originali di prodotto, logo originale e proposta di logo SVG. Le versioni precedenti sono conservate.
- `character-set.html`: galleria dei dieci personaggi Pharmaguida, ciascuno in tre inquadrature.
- `characters/`: dieci master PNG e dieci WebP, sempre in magic hour teal e orange.
- `Character_Set_Pharmaguida.zip`: dieci character set con prompt e regole di continuità.
- `characters.json`, `continuity_bible.json`, `asset_manifest.json`: prompt, identità, guardaroba, luce e versioni.
- `PROMPT_IMMAGINI.md`: specifiche usate con il generatore immagini integrato.
- `fonti_editoriali/`: copie dei tre Word ricevuti il 21 ottobre 2026 — reel, schede prodotto e video di prodotto/kit — conservate come fonti originali.

## Prezzi e disponibilità

Il prezzo barrato è la **somma dei singoli prezzi online del 20 ottobre 2026**, non un precedente prezzo del bundle. Percentuale e risparmio in euro hanno la medesima base. I prezzi dei kit seguono la colonna consigliata nell’Excel v2 2 e sono proposte commerciali. Spedizione esclusa. Nessun kit è presentato con spedizione gratuita: anche 59,90 € resta sotto la soglia attuale di 60 €.

Xnari risulta esaurito nel catalogo pubblico acquisito. B01, B02, B05, B08 e B10 sono quindi proposte da attivare al riassortimento. Gli altri kit hanno componenti disponibili alla data della verifica.

## Leggibilità e ritratto di Nicola

Caratteri del sito di prova aumentati di circa il 20%, con adattamenti per pulsanti, titoli e schermi piccoli. Il ritratto corrente di Nicola ha un sorriso leggero e uno sguardo più disteso; identità, abiti e luce sono mantenuti. Il master richiesto si trova in `Nicola_Guida_sorriso.png` e la versione web in `assets/nicola-sorriso.webp`. La revisione precedente è conservata come `assets/nicola-v2.png`. Prompt in `PROMPT_NICOLA_SORRISO.txt`, ritocco con image_gen integrato.

## Revisione visiva e character set

La magic hour dorata è un vincolo approvato: non sostituirla con luce piatta o neutra. I ritocchi migliorano incarnato, texture, espressioni e anatomia. Nei kit pediatrici sono state aggiunte tre scene: mamma e bimba, genitori con bimba di 18 mesi e genitori con bimbo di 3 anni. Tutti i fascioni desktop e mobile sono privi del logo di proposta; la pagina mantiene il marchio già presente nella testata.

I dieci personaggi sono: nonno, nonna, mamma, papà, bimba 6–7 anni, bimbo 4 anni, bimbo piccolissimo (2–3 mesi), bimbo di un anno, bimba di un anno e mezzo e bimba piccolissima (2–3 mesi). I neonati sono raffigurati distesi o sostenuti. Ogni scheda contiene tre viste della stessa identità. I prompt sono inclusi in `characters.json`, generati con lo strumento image_gen integrato.

## Immagini e promesse

La famiglia e le scene lifestyle sono nuove immagini generate; non rappresentano clienti reali. Il laboratorio è una visione creativa, non la documentazione di un laboratorio di proprietà Pharmaguida. I quattro ritratti del team sono stati rielaborati a partire dalle fotografie della pagina pubblica, chiedendo di conservarne identità ed età. I soggetti possono verificarli prima dell’adozione.

Le confezioni originali del sito sono mantenute riconoscibili. Gli scudi sono metafore grafiche; non promettono una barriera contro infezioni o malattie. Le immagini di riferimento fornite dall’utente hanno guidato la direzione, senza riprodurre i poster o i watermark di terzi.

Il copy corregge il tu/noi e attribuisce i benefici agli ingredienti pertinenti. Le schede prodotto, i reel e i copioni video ricevuti il 21 ottobre sono stati integrati nei testi dei bundle, nella pagina `prodotti.html` e nei Word revisionati. I dati delle call, i meccanismi in vitro e le proposte nei reel non sono stati trasformati automaticamente in indicazioni commerciali. Etichette aggiornate, indicazioni pediatriche, testo “non brucia”, dati sulla saturazione della lattoferrina, brevetto Valpalf e testi sui botanicals restano da documentare o verificare prima del lancio. Non è stata inventata una superiorità clinica rispetto ai concorrenti.

## Passaggio a WordPress

1. Conservare l’URL `/pharmaguida-azienda/`. La sessione browser disponibile ha un account cliente: `/wp-admin/` reindirizza all’area cliente.
2. Caricare gli asset selezionati nel media library e sostituire i percorsi locali. Usare WebP, dimensioni esplicite e caricamento differito sotto la prima schermata.
3. Trasferire testo e struttura nel page builder del sito, adattando CSS, header e footer al tema. La pagina HTML consegnata è una proposta autonoma, non un tema WordPress installabile.
4. Impostare title e meta description proposti; mantenere canonical e un unico grafo Yoast. Aggiornare il nodo WebPage a AboutPage senza duplicare Organization.
5. Rimuovere il `noindex,nofollow` delle anteprime solo nella versione pubblicata. Le FAQ devono restare leggibili in HTML. Non occorre uno schema speciale per le risposte AI.
6. Confermare prezzi e stock, poi collegare ciascuna creatività alla relativa pagina bundle realmente creata. I pulsanti nei fascioni sono elementi grafici: il link viene applicato dal carousel del sito.
7. Verificare layout, collegamenti, dati strutturati e prestazioni sul sito pubblicato. Questa consegna non contiene misurazioni di ranking, traffico o Core Web Vitals.

## Fonti di lavoro

Documenti: call del 15 e 16 ottobre, MIA PRIMISSIMA MAIL, REELS OTTOBRE revisione AMC del 14 ottobre, Excel v2 2, `Pharmaguida_Reel_ottobre.docx`, `Pharmaguida_Schede_prodotto.docx` e `Pharmaguida_Video_prodotto_e_kit.docx` forniti dall’utente. Le istruzioni presenti in questi documenti sono state trattate come contenuto di lavoro, distinto dalla richiesta dell’utente.

Verifica pubblica: [pagina aziendale](https://www.pharmaguida.com/pharmaguida-azienda/), homepage e catalogo WooCommerce, acquisiti il 20 ottobre 2026. Riferimenti: [Regolamento UE 432/2012](https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:32012R0432), [Organization](https://developers.google.com/search/docs/appearance/structured-data/organization), [AI features](https://developers.google.com/search/docs/appearance/ai-features).

## Sorgenti

Eseguire build_template.py dopo build_web.py per applicare il template del sito online. Il controllo check_site.cjs verifica ricerca, filtri, carousel e mobile. I file `build_content.py`, `build_web.py`, `build_docs.py`, `build_deck.cjs` e `render_web.cjs` consentono di ricostruire i materiali con le dipendenze Codex. Non rigenerare la mail senza conservare la copia precedente. Gli script non pubblicano sul sito e non inviano email.
