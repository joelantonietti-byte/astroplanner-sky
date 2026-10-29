# AstroPlanner – foto del cielo

Foto del cielo degli oggetti del catalogo di AstroPlanner, servite da GitHub Pages
all'indirizzo https://joelantonietti-byte.github.io/astroplanner-sky/.

Per ogni oggetto ci sono due foto quadrate da 1600 px, proiezione tangente (TAN),
nord in alto ed est a sinistra, centrate sull'oggetto:

- `<id>-near.jpg`: lato pari al doppio dell'asse maggiore, almeno 40′;
- `<id>-wide.jpg`: lato di almeno 4° (il doppio della foto vicina per gli oggetti grandi), al massimo 30°.

`index.json` riporta per ogni oggetto il file e il lato in gradi di ciascuna foto.
Nei nomi dei file spazi e simboli dell'identificativo diventano `_` (per esempio `NGC_7000-near.jpg`).

Le foto sono composte dallo strumento `tools/build_sky_photos.swift` di AstroPlanner
a partire dalle tessere HiPS «DSS colored» del mirror ESASky (https://skies.esac.esa.int/DSSColor/).

## Crediti

Digitized Sky Survey – STScI/NASA; colori e HiPS del CDS (Université de Strasbourg / CNRS).

Le immagini della DSS sono soggette ai copyright dei rispettivi titolari:
California Institute of Technology, Anglo-Australian Observatory, Royal Observatory Edinburgh
e Association of Universities for Research in Astronomy.
Vedi https://archive.stsci.edu/dss/copyright.html e https://archive.stsci.edu/dss/acknowledging.html.

Le foto sono pubblicate qui solo per l'uso nell'app AstroPlanner, senza scopo commerciale.
