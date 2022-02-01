## Emissie race barchart
Visualisatie van CO2 emissies die onder EU-ETF vallen

### Gebruik
* create_emissions_to_race_bar_chart.ipynb -> maakt de video
* emissie_mapping.csv -> bevat de mapping tussen vergunningnaam en installatie en bedrijf
* colors.csv -> bevat de mapping tussen bedrijf en type bedrijf
* Emissiecijfers+2013-2020.ods -> source data

### Beperkingen
* Een installatie heeft de hele periode dezelfde eigenaar
* Sommige installaties zijn erg lastig te splitsen. Daarom heb ik Chemelot niet naar een bedrijf gesplitst, (SABIC/RWE/anderen)
* Installaties worden altijd in zijn geheel aan een type toegewezen, dus bv of geheel gas, of geheel kolen

### Requirements and thanks to these packages
* https://pypi.org/project/bar-chart-race/
install with `pip install git+https://github.com/dexplo/bar_chart_race`
you also need to install FFmpeg
* odfpy to read the source data format

### Links
[Overall breakdown of NL emissions](https://www.cbs.nl/nl-nl/dossier/dossier-broeikasgassen/hoofdcategorieen/hoe-groot-is-onze-broeikasgasuitstoot-wat-is-het-doel-)
[Factsheets ETS CO2 emissions](https://www.emissieautoriteit.nl/onderwerpen/rapportages-en-cijfers-eu-ets/documenten/publicatie/2021/05/31/factsheet-ets-uitstoot-2020)
[Source data](https://www.emissieautoriteit.nl/documenten/publicatie/2021/05/05/ets-uitstoot-2020)

### License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
You can use this under the MIT license
nl/)
