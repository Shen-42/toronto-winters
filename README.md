# Toronto Winters

Were Toronto winters as snowy as I remember as a kid? This page charts daily snow on the ground in downtown Toronto for the winters of 2006–07 to 2024–25.

Adapted from [Were Kyiv Winters as Snowy as I Remember as a Kid?](https://observablehq.com/@mourner/were-kyiv-winters-as-snowy-as-i-remember-as-a-kid) by [Volodymyr Agafonkin](https://observablehq.com/@mourner).

## Data

`data/toronto_city_snwd.csv` has daily snow depth in millimetres from Environment and Climate Change Canada, station TORONTO CITY (Climate ID 6158355), 2006–2025. It uses the same columns as the NOAA files in the original notebook: `STATION`, `DATE`, `SNWD`.

The station has no snow depth readings for the winters of 2009–10, 2010–11, 2011–12 and 2014–15, and it does not measure snowfall.

## Running it

The page is plain HTML with Observable Plot loaded from a CDN. To view it locally, serve the folder (opening the file directly blocks the CSV load):

```
python3 -m http.server
```

Then open http://localhost:8000.
