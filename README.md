<p align="center">
  <img src="https://raw.githubusercontent.com/valentinoavi46-dev/Training-data/main/logo.png" width="220">
</p>


[![Licenza: CC BY-NC 4.0](https://img.shields.io/badge/Licenza-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Pipeline Dati di Allenamento

![Stato Sync](https://github.com/valentinoavi46-dev/Training-data/actions/workflows/auto-sync.yml/badge.svg)

**Last successful sync:** 2026-04-12 16:34:36 UTC


**Ultima sincronizzazione riuscita:** 2026-03-04 21:46:46 UTC

Pipeline automatizzata dei dati da [Intervals.icu](https://intervals.icu) per analisi tramite AI coaching.
Basata sul [Protocollo Section 11](https://github.com/CrankAddict/section-11).

## URL dei Dati

| File | Descrizione | Link |
|------|-------------|------|
| `latest.json` | Snapshot attuale di 7 giorni + metriche derivate | [Visualizza](https://raw.githubusercontent.com/valentinoavi46-dev/Training-data/main/latest.json) |
| `history.json` | Dati longitudinali (giornalieri/settimanali/mensili) | [Visualizza](https://raw.githubusercontent.com/valentinoavi46-dev/Training-data/main/history.json) |

## Auto-Sync

La sincronizzazione dei dati avviene ogni 15 minuti tramite GitHub Actions.  
La pipeline recupera attività, wellness e workout programmati da Intervals.icu, calcola metriche derivate (ACWR, monotony, polarization, rilevamento della fase), e genera alert graduati.

## Analisi AI

```
Analizza i miei allenamenti usando questi file:
- Corrente: https://raw.githubusercontent.com/valentinoavi46-dev/Training-data/main/latest.json
- Storico: https://raw.githubusercontent.com/valentinoavi46-dev/Training-data/main/history.json
```

Per risultati ottimali, abbina queste analisi al https://github.com/CrankAddict/section-11.

## Licenza
https://creativecommons.org/licenses/by-nc/4.0/ — Libero per uso personale e non commerciale. Attribuzione richiesta.
