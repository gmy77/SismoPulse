# SismoPulse

Versione: `0.1.2-preview`

SismoPulse mostra dove l'attivita sismica osservata e sopra la media recente, senza fare previsioni.

Dashboard statica sperimentale per leggere attivita sismica osservata con mappa globale, heatmap, faglie/placche, grafici di energia, profondita, sequenze e indice di attenzione.

## Live

```text
https://gmy77.github.io/SismoPulse/
```

## Cosa fa

- Mostra eventi sismici recenti su planisfero.
- Evidenzia sequenze, eventi superficiali ed energia rilasciata.
- Confronta l'attivita osservata con una baseline recente.
- Offre una lettura sintetica con indice di attenzione.
- Usa dati USGS live quando disponibili, con fallback demo per evitare schermate vuote.
- Fonte live attiva nella preview: USGS FDSN Event API.
- Fonti candidate per prossime versioni: EMSC/SeismicPortal e INGV FDSN, da integrare con deduplicazione.

## Note

- Non richiede Cloudflare.
- Non modifica SismoGlobe o SISMO FVG.
- La dashboard e osservazionale: non e una previsione sismica.

## Promozione

- URL consigliato per condivisione: `https://gmy77.github.io/SismoPulse/`
- Frase breve: "SismoPulse mostra dove l'attivita sismica osservata e sopra la media recente, senza fare previsioni."
- Topic consigliati GitHub: `earthquake`, `seismic`, `dashboard`, `geology`, `usgs`, `github-pages`, `visualization`.

## Versionamento

- Versione corrente: `0.1.2-preview`
- Aggiorna `VERSION`, `package.json` e `CHANGELOG.md` a ogni modifica pubblicabile.
