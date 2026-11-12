# Robin release assets

Files that Robin, a Mac app for a family's scanned photos, downloads when asked.

## Map data

Under the release tagged `map-data`: one file per state, `<STATE>-<year>-<build>.robinmap.xz`, with that state's
place names, streets and house-number ranges, town lines, parks and water. Robin downloads a state's file when it's
chosen in File ▸ Map Data…, and checks it against a checksum the app carries.

Built from public-domain data of the U.S. Census Bureau (TIGER/Line and the gazetteer) and the U.S. Geological
Survey (the Geographic Names Information System).

A file here is never renamed or replaced: a new build of a state is added beside the old one.
