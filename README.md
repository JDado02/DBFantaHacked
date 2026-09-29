# Dati di FantaHacked

I dati dei giocatori usati da FantaHacked, in un file solo.

| | |
|---|---|
| aggiornati al | **2026-09-28** |
| pubblicati il | 2026-09-29 12:25 |
| giocatori | 599 |
| dimensione | 189 KB compressi |
| formato | SQLite, schema 1 |

Il programma legge `manifest.json` a ogni avvio - due kilobyte - e
scarica `dati.db.gz` solo se la versione e cambiata. Se internet non c e,
parte con i dati che ha gia.

Dentro ci sono listone, statistiche, gerarchie di reparto e proiezioni.
Non c e niente dell asta: quella resta sul dispositivo di chi la gioca.

Si pubblica con `python database/pipeline/pubblica.py --pubblica`.
