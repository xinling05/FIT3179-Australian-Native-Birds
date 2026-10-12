# Australian Native Birds — FIT3179 DV2 starter

## Clean filenames expected in `data/`
- `20260828spcs.csv`
- `australia_states_2026.json`
- `rainbow_lorikeet_points_5000.csv`
- `rainbow_lorikeet_hexbins_50km.geojson`
- `bio_087_horizln1.csv`
- `rainbow_lorikeet_monthly_2025.csv`
- `ala_birds_checklist_2025.csv`
- `bird_family_treemap.csv`
- `ward_bird_threats.csv`

## Important
1. Simplify the 15 MB state TopoJSON in Mapshaper before GitHub. Keep the object name `australia_states_2026`.
2. Do not upload the 126 MB raw ALA Rainbow Lorikeet CSV.
3. The current ALA file lacks `eventDate`, so Chart 6 needs a corrected ALA export with Event fields, then aggregate it to month × state.
4. Save the `Species-Threat-Impact` sheet from Ward et al. as `ward_bird_threats.csv`.
5. Generate `bird_family_treemap.csv` from the ALA checklist using the supplied prep script.

The three-dot actions menu is enabled in `index.html` through Vega-Embed.
