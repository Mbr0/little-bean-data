# little-bean-data

Public pregnancy food-safety alerts feed for the [Little Bean](https://github.com/Mbr0/little-bean) app.

`public/alerts.json` — fetch URL for the mobile app:
`https://raw.githubusercontent.com/Mbr0/little-bean-data/main/public/alerts.json`

## About the feed

The feed collects official food recalls and alerts that may matter during pregnancy (for example Listeria, Salmonella, undeclared allergens or chemical contaminants). It draws on six regulators: RappelConso (France), the Food Standards Agency (UK), the U.S. FDA, the NVWA (Netherlands), FAVV-AFSCA (Belgium) and the CFIA (Canada). Each record keeps the original notice text and links to the official notice.

Records are selected and classified automatically. The feed is regenerated once a day (06:00 UTC) by GitHub Actions in the main repo. The time of the latest run is in the `generated` field.

## Disclaimer

This feed is for information only and is not medical advice. It may be incomplete, delayed or wrong. Always check the official recall notice linked in each record, and ask a healthcare professional about your own situation.

## Licence

`public/alerts.json` is licensed under [CC BY 4.0](LICENSE). The records are based on notices published by the regulators listed above. Their notices remain under their own terms. See [NOTICE](NOTICE) for each source's licence and the attribution it requires.
