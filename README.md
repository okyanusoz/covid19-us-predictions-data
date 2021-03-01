# US COVID-19 Predictions data

![Status badge](https://github.com/okyanusoz/covid19-us-predictions-data/workflows/Update%20data/badge.svg)

This repo contains COVID-19 predictions in the US.

### Disclaimer

While this repo predicts COVID-19, deaths and especially cases are still random. USE THIS DATA AT YOUR OWN RISK!

The main focus of this data is to predict deaths, not cases. Therefore we recommend focusing on deaths. Also, death predictions are much more accurate than case predictions.

There are two data files:
- data.json: predicted and current cases and deaths. See https://github.com/okyanusoz/covid19-cases-predictor/blob/main/data.schema.json for the schema.
- dataset.csv: cases dataset, contains cases and deaths, data provided by JHU CSSE

COVID-19 data provided by JHU CSSE. See LICENSE for more details.

### Archived predictions

Archived predictions are also available through Git commit history. Here are the URLs you can use to browse the history of data files:
- data.json: https://github.com/okyanusoz/covid19-us-predictions-data/commits/main/data.json
- dataset.csv https://github.com/okyanusoz/covid19-us-predictions-data/commits/main/dataset.csv

You can also use GitHub's API to query commits of these files.

### Update Frequency
The job starts at around 9:10 UTC(to make sure data is up to date), and should finish in a few minutes

We recommend checking for updates at around 10:00 UTC because the job may start late. There is no guarantee on when the jön will start.

**NOTE:** Please **DO NOT** send pull requests to data.json or dataset.csv, they're automatically updated.
