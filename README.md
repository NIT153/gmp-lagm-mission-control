# GeoMorphPyramid Mission Control

**GMP-LAGM Mission Control v0.1**  
Computational Geomorphology Portal for Pyramidal Landform Detection.

Dashboard statico tecnico-scientifica per il progetto LAGM / GeoMorphPyramid, dedicata all'identificazione falsificabile di candidati morfologici piramidali tramite DEM/DTM, PSI, QGIS e validazione GIS.

Il sistema non dichiara scoperte archeologiche: genera candidati morfologici da verificare con controlli geomorfologici, multisensore, archeologici e revisione esperta.

## Avvio locale

```bash
python -m http.server 8000
```

Poi aprire:

```text
http://localhost:8000
```

## Pubblicazione GitHub Pages

Impostare:

- Settings -> Pages
- Source: Deploy from a branch
- Branch: main
- Folder: / root

## File principali

- `index.html` — portale statico
- `data/sample_validation_summary.csv` — dati demo validation gates
- `data/sample_top_candidates_spatial.csv` — candidati demo vicino al Cervino
- `data/portal_config.json` — configurazione progetto

## Disclaimer scientifico

GeoMorphPyramid System identifica candidati morfologici da verificare. Il PSI non dimostra artificialità, archeologia o intenzionalità costruttiva. Ogni candidato richiede validazione geologica, archeologica, multisensore e, dove necessario, sopralluogo.
