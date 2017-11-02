# Come usare le licenze

Questo repository contiene le licenze per il software sviluppato o rilasciato dal Team Digitale.

# Checklist in breve

Per applicare correttamente una licenza, Bisogna:

- [ ] Selezionare una licenza
- [ ] Cambiare le linee di copyright correttamente
- [ ] Copiarla nella root del repository, con nome `LICENSE`

# Spiegazione

Per applicare una licenza al vostro repository, selezionare la licenza apposita e copiarla nella cartella principale del repository, con il nome `LICENSE`

## Selezionare una licenza

In particolare, è stato scelto di usare:
- `AGPLv3+` per tutto il software accessibile via web o che eroga un servizio via rete (es. servizio web)
- `GPLv3+` per tutto il software "tradizionale"
- `BSD-3-clause` per le librerie
- `CC-BY-4` per la documentazione

Potete copiare e incollare il testo del file direttamente nel vostro repository

## Cambiare la riga di copyright

La riga di copyright può essere cambiata a seconda dell'origine del software

### Caso 1: importare software esistente
In questo caso il copyright deve contenere due righe, la prima che rappresenta l'ente che rilascia il software (che è in generale diverso dalla persona che esegue il primo commit), la seconda per tutti i contributor come da log git.

Esempio con AgID:
```
Initial import: Copyright (c) 2017 Agenzia per l'Italia Digitale
All other contributions:
Copyright (c) 2017, the respective contributors, as shown by the version control
```

### Caso 2: software scritto da zero
Questo caso è più semplice e ha bisogno soltanto di una riga, perché tutte le modifiche sono tracciate da git.
```
Copyright (c) 2017, the respective contributors, as shown by the version control
```
