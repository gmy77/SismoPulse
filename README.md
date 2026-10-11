# SismoPulse

Versione: `0.1.0-preview`

Dashboard statica sperimentale per leggere l'attivita sismica osservata con mappa globale, heatmap, faglie/placche, grafici di energia, profondita, sequenze e indice di attenzione.

Questa versione e pensata per GitHub Pages. Nome repository consigliato: `SismoPulse`.

## Pubblicazione su GitHub Pages

1. Crea un repository GitHub, per esempio `SismoPulse`.
2. Carica il contenuto di questa cartella nella root del repository.
3. In GitHub vai su `Settings > Pages`.
4. Imposta `Deploy from a branch`.
5. Seleziona branch `main` e cartella `/root`.
6. Dopo il deploy la dashboard sara disponibile come:

```text
https://gmy77.github.io/SismoPulse/
```

## Note

- Non richiede Cloudflare.
- Non modifica SismoGlobe o SISMO FVG.
- Usa dati USGS live quando disponibili, con fallback demo per non mostrare una pagina vuota.
- La dashboard e osservazionale: non e una previsione sismica.

## Versionamento

- Versione corrente: `0.1.0-preview`
- Aggiorna `VERSION`, `package.json` e `CHANGELOG.md` a ogni modifica pubblicabile.
