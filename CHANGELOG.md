# Changelog

## 0.1.5-preview - 2026-10-11

- Collegati i pulsanti 24h e 7g al filtro temporale della mappa.
- Aggiornati titolo, conteggio e stato accessibile del periodo selezionato.
- Rimossi il limite di 320 marker e gli eventi fuori dal periodo selezionato.

## 0.1.4-preview - 2026-10-11

- Aggiunto caricamento multi-fonte: USGS globale, EMSC/SeismicPortal euro-mediterraneo e INGV FDSN per Italia.
- Aggiunta barra fonti dinamica con conteggi e stato delle fonti realmente disponibili.
- Aggiunta deduplicazione approssimata tra cataloghi, con priorita INGV per Italia e EMSC per Mediterraneo.
- Campi Flegrei e Friuli V.G. ora usano INGV quando disponibile e restano marcati come incompleti quando il catalogo locale non risponde.

## 0.1.3-preview - 2026-10-11

- Corretto il trattamento delle aree locali Campi Flegrei e Friuli V.G.: non mostrano piu conteggi USGS come se fossero completi.
- Aggiunta indicazione "catalogo locale richiesto" per aree che richiedono INGV/OV-INGV o cataloghi regionali.
- Aggiornata nota fonti per chiarire che USGS M2.5+ non copre la micro-sismicita locale.

## 0.1.2-preview - 2026-10-11

- Corretto il posizionamento degli eventi dentro l'area del planisfero, evitando marker e heatmap fuori mappa.
- Aggiunta trasparenza sulle fonti: fonte live attiva, criteri di selezione eventi e fonti candidate.
- Chiarito che la mappa principale mostra un sottoinsieme operativo, non tutto il catalogo sismico disponibile.

## 0.1.1-preview - 2026-10-11

- Aggiunti metadati SEO e social preview per la pubblicazione GitHub Pages.
- Aggiunti `robots.txt`, `sitemap.xml`, `site.webmanifest` e immagine `social-preview.svg`.
- Migliorati titolo, descrizione, canonical URL, Open Graph, Twitter Card e JSON-LD.
- Aggiornato README con link live, posizionamento pubblico e note promozionali.

## 0.1.0-preview - 2026-10-11

- Prima preview pubblicabile di SismoPulse per GitHub Pages.
- Aggiunta mappa globale con planisfero reale, overlay faglie/placche, heatmap sismica ed eventi.
- Aggiunti pannelli professionali: risposta rapida, watchlist aree, attivita vs baseline, energia cumulata, sequenze, profondita/magnitudo, bande di profondita e indice di attenzione.
- Aggiunte lenti rapide interattive: normale, superficiali, energia, sequenze.
- Dati USGS live quando disponibili, con fallback demo per evitare schermate vuote.
- Nota scientifica: dashboard osservazionale, non previsione sismica.
