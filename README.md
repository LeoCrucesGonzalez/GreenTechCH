# GreenTechCH

This repository contains a data-driven analysis of Chile's technological specialization in green technologies using patent data from the USPTO.

## Purpose

To evaluate Chile's revealed comparative advantage (RCA) across CPC classes and identify opportunities for green diversification based on patent activity.

## Contents

- `AnalisisBases.ipynb`: patent database preprocessing
- `RCA.ipynb`: RCA calculation by country, CPC class, and year
- `.gitignore`: excludes large `.tsv` data files

## Data sources

Patent data files used (not included in this repository due to size constraints):

- `g_patent.tsv`
- `g_cpc_current.tsv`
- `g_assignee_disambiguated.tsv`
- `g_location_disambiguated.tsv`

All datasets are publicly available at the [USPTO PatentsView portal](https://patentsview.org/download/data-download-tables).
