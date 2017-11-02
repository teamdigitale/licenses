# Come usare le licenze

Questo repository contiene le licenze per il software sviluppato o rilasciato dal Team Digitale.

# Checklist in breve

Per applicare correttamente una licenza, Bisogna:

- [ ] Selezionare una licenza
- [ ] Scegliere la linea di copyright a seconda del caso in cui vi trovate
- [ ] Eventuali step ulteriori a seconda della licenza scelta
- [ ] Copiarla nella root del repository, con nome `LICENSE`

# Spiegazione

Per applicare una licenza al vostro repository, selezionare la licenza apposita e copiarla nella cartella principale del repository, con il nome `LICENSE`

## Selezionare una licenza

In particolare, è stato scelto di usare:
- [`AGPLv3+`](AGPLv3+) per tutto il software accessibile via web o che eroga un servizio via rete (es. servizio web)
- [`GPLv3+`](GPLv3+) per tutto il software "tradizionale"
- [`BSD-3-clause`](BSD-3-clause) per le librerie
- [`CC-BY-4`](CC-BY-4) per la documentazione

Potete copiare e incollare il testo del file direttamente nel vostro repository

## La riga di copyright

La riga di copyright deve essere cambiata a seconda dell'origine del software.
La licenza `BSD-3-clause` prevede che questa riga vada cambiata direttamente all'interno del file di licenza. Per le altre licenze bisogna creare un file chiamato `AUTHORS` contenente la riga di copyright.

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

## Step ulteriori

### BSD-3-clause
Se usate BSD, vi basta modificare la linea di copyright all'interno della licenza e inserirla all'interno del vostro codice. Il file in questo repository è già pronto per software scritto da zero.

### GPLv3+
Bisogna creare un file `README` o `README.md` che contenga, in coda, la riga di copyright corretta, e la seguente dicitura:

```
Copyright (c) 2017, the respective contributors, as shown by the version control

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
### AGPLv3+
Bisogna creare un file `README` o `README.md` che contenga, in coda, la riga di copyright corretta, e la seguente dicitura:

```
Copyright (c) 2017, the respective contributors, as shown by the version control

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

### CC-BY-4
Bisogna creare un file [`AUTHORS`](AUTHORS) contenente la riga di copyright.
