# Toronto Winters

Charts daily snow on the ground in Toronto for every winter from 2006–07 to 2024–25.

Live page: https://shen-42.github.io/toronto-winters/

## Features

- One strip per winter showing snow depth day by day, November to April
- Bar chart of days with at least 1 cm of snow on the ground
- Winters from 2006–07 to 2015–16 highlighted for comparison with later years

## Run locally

```
git clone https://github.com/Shen-42/toronto-winters.git
cd toronto-winters
python3 -m http.server
```

Then open http://localhost:8000.

## Data

`data/toronto_snwd.csv` has daily snow depth in millimetres from Environment and Climate Change Canada. Most winters come from TORONTO CITY (6158355). Winters 2009–10, 2010–11, 2011–12 and 2014–15 come from TORONTO NORTH YORK (615S001) because the downtown station has no readings for them.

## Credit

Adapted from [Were Kyiv Winters as Snowy as I Remember as a Kid?](https://observablehq.com/@mourner/were-kyiv-winters-as-snowy-as-i-remember-as-a-kid) by [Volodymyr Agafonkin](https://observablehq.com/@mourner).
