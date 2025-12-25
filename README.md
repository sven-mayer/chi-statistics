# CHI Conference Program Committee Statistics

This repository aggregates and curates publicly available data about the **CHI Conference Program Committee (PC)** across multiple years. It combines information collected from official CHI conference websites, the front matter of CHI proceedings, and publicly accessible ORCID records.

The goal of this repository is to **document and make visible the substantial volunteer effort** contributed by hundreds of researchers who have served on the CHI Program Committee over the years.

## Data Sources and Curation
All primary data sources are listed in: `data/paper-data.csv`. The dataset is derived exclusively from publicly available information. No private or confidential data is included.

## Disclaimer
The contributors to this repository **do not guarantee the correctness or completeness of the data**. Errors may exist due to inconsistencies in public records, name variants, affiliation changes, or incomplete metadata.

If you identify any inaccuracies, please open an issue or submit a pull request with a correction.

## Data Standards and External Resources

### Country and Region Declarations

- Country names follow **ISO 3166 (Alpha-3 codes)** using the dataset from <https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes>
- Regional groupings follow the **UN M49 standard** <https://unstats.un.org/unsd/methodology/m49/overview>

ACM does not consistently use official ISO country names. To address this, we provide a manual mapping file: `utils/mapCountryNamesACM.csv`. This file maps ACM country name variants to their corresponding ISO Alpha-3 codes.

### Affiliation Name Mapping
A major data-cleaning challenge is the consolidation of affiliations that appear under multiple name variants across years.

All known mappings are stored in: `utils/mapAffiliation.csv`
If an affiliation is missing or inconsistently represented, please add a new entry to this file and submit a pull request.

Affiliations are linked to **Wikidata** entries whenever possible: <https://www.wikidata.org/>. Affiliation names generally follow their English-language canonical form. If an affiliation differs from its Wikidata label, this reflects a different official naming convention rather than an error. The file: `utils/mapAffiliationDefault.csv`maps affiliations to their corresponding Wikidata entries and default country assignments.

### Geographic Data for Maps
All geographic visualizations are based on data from **Natural Earth**: <https://github.com/nvkelso/natural-earth-vector>

## General Conference Metadata
The `data` directory also contains general CHI conference metadata, including:
- Conference locations  
- Acceptance rates  
- Yearly conference attributes






