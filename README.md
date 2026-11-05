# DispatchWala

DispatchWala helps truck dispatchers find active, MC-authorized US motor carriers by MC number range, location, or the date their operating authority was granted.

Filters: equipment type (inferred from cargo), cargo classification, CDL / Non-CDL drivers, truck count, phone/email on file. Results export to CSV.

## Data sources

Live from FMCSA open data on [data.transportation.gov](https://data.transportation.gov), updated daily:

- Company Census File (`az4n-8mr2`)
- Motus Authority History (`yu5v-wbh6`)
- Motus Carrier (`inys-ebih`)
- L&I Carrier (`6eyk-hxee`)
- Insurance on file: Motus Insurance (`c5y8-a4uz`) and L&I Active/Pending Insurance (`qh9u-swkp`)
- BOC-3 process agent: Motus BOC-3 (`6snj-ed7q`) and L&I BOC-3 (`2emp-mxtb`)

Out-of-service orders are not in these datasets.

## Run it

Open `index.html` in a browser, or host it on any static host (GitHub Pages, Netlify, Vercel). No server or API key needed.
