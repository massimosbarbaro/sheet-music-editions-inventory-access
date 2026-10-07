# Inventory of printed music editions for a music archive

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23205236.svg)](https://doi.org/10.5281/zenodo.23205236)

*Inventario delle edizioni musicali a stampa di un archivio musicale*

**Microsoft Access** · 2022 · version 2022  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

This database, with a Slovene interface, inventories the printed music editions of a music archive. Each item records edition mark, old mark, composer, title, publisher, year of publication, type of notation and number of copies, and is classified by typology.

I designed and programmed this application in 2022. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Data-entry form for the archive (`Podatke`).
- Datasheet lists for browsing and sorting (`ArhivTab`, `ArhivTab2`).
- Typology table management (`fTipologija`).
- Automatic numbering of new items.

## Data

Tables `Arhiv`, `Tipologija` and two earlier lists (`Klavir tehnika`, `Klavir zbirke`).

## Technology

Microsoft Access 2010+ format (.accdb), embedded macros, VBA.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The Access application, emptied of all data. |
| `source/` | Plain-text export (UTF-8) of forms, reports, macros, VBA modules (`SaveAsText`) and of the SQL of every query. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: every table has been emptied and the file compacted, so no record of the original data survives. Logos and names of the organisations that used the application have been removed from forms, reports and code, together with printer settings and any credential. Forms, reports, queries, macros and VBA code are otherwise unchanged and are also provided as plain text in `source/`.

## Related repositories

- [music-library-catalogue-access](https://github.com/massimosbarbaro/music-library-catalogue-access)
- [sound-music-archive-catalogue-access](https://github.com/massimosbarbaro/sound-music-archive-catalogue-access)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23205236](https://doi.org/10.5281/zenodo.23205236).

> Sbarbaro, Massimo. 2022. *Inventory of printed music editions for a music archive*. Software (Microsoft Access, 2022), version 2022. Zenodo. https://doi.org/10.5281/zenodo.23205236.

## License

Released under the [MIT License](LICENSE). © 2022 Massimo Sbarbaro.
