# Come usare le licenze

Questo repository contiene le licenze per il software sviluppato o rilasciato dal Team per la Trasformazione Digitale, e vale come raccomandazione anche per il software presente in Developers Italia. Non ha valore di raccomandazione generale per il software open source della PA.

# In breve

Per applicare correttamente una licenza, bisogna:

1. scegliere una licenza tra quelle qui proposte;
2. copiarla nella root del repository, con nome `LICENSE`
3. creare e compilare il file `AUTHORS` sempre nella root del repository.

## Come scegliere la licenza

In particolare, è stato scelto di usare:
- [`AGPL-3.0-or-later`](AGPL-3.0-or-later) per tutto il software accessibile via web o che eroga un servizio via rete (es. servizio web)
- [`GPL-3.0-or-later`](GPL-3.0-or-later) per tutto il software da usare in locale (ad es. desktop)
- [`BSD-3-Clause`](BSD-3-Clause) per le librerie
- [`CC-BY-4.0`](CC-BY-4.0) per la documentazione
- [`CC0-1.0`](CC0-1.0) per le leggi e i documenti normativi

## Come compilare il file AUTHORS

Il file `AUTHORS` contiene tre informazioni:

1. i **detentori di copyright**;
2. i **detentori di diritti morali**: sono i nomi dei singoli autori del codice, in modo da riconoscere anche i loro diritti morali (che nel diritto italiano sono inalienabili) a prescindere dai detentori di copyright; in caso di lavoratori dipendenti o altro regime di subordinazione infatti il copyright è del datore di lavoro mentre i diritti morali restano all'autore effettivo;
3. la dicitura *The version control system provides attribution for specific lines of code.* che rimanda allo storico del repository per la mappatura delle corrispondenze tra autori e singole porzioni di codice.

Non è obbligatorio aggiungere il proprio nome alle due liste; è raccomandato solo per contributi di codice rilevanti. Tutti i contributi sono in ogni caso tracciati dal version control system, ma si potrebbero perdere in caso di distribuzioni del codice al di fuori di GitHub e inoltre dal solo storico dei commit non è chiaro se l'autore del commit abbia il copyright oppure no. È per questo che raccomandiamo il file `AUTHORS` per elencare i soggetti detentori di diritti.

Un esempio di file `AUTHORS` [è disponibile qui](AUTHORS)

## Step ulteriori

### GPL-3.0-or-later
Bisogna creare un file `README` o `README.md` che contenga, in coda, la seguente dicitura:

```
Copyright (c) the respective contributors, as shown by the AUTHORS file.

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
### AGPL-3.0-or-later
Bisogna creare un file `README` o `README.md` che contenga, in coda, la seguente dicitura:

```
Copyright (c) the respective contributors, as shown by the AUTHORS file.

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
