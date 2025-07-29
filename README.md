# data_project_template
This will act as a template for all of my future projects. I will clone the repo, disconnect from this repo, delete unnecessary files, and then create a new one for the relevant project at hand.


Key information about this project: [...]


Replicability guide: [...]



Folder structure: 

proj/
 ├── README.md
 ├── data/
 │    ├── raw/            ← immutable raw data
 │    ├── processed/         ← cleaned/intermediate data
 │    └── external/         ← external datasets if needed
 ├── code/         ← analysis & programming scripts
 │    ├── funs/         ← reusable functions
 │    ├── src/         ← main processing code
 │    │    ├── 01_gather_data.py         ← import from APIs / scrape (in addition to downloads)
 │    │    ├── 02_clean_data.py         ← clean raw data and save into "data/processed"
 │    │    ├── 03_univariate_analysis.py     
 │    │    └── ...
 ├── output/              ← final tables, datasets, CSVs
 ├── figs/                ← plots and graphics
 └── docs/                ← documentation, reports, manuscripts
 └── temp/                ← transient files (optional)
 


Notes for myself: [...]
- Be sure to include metadata in your file names. (Example: YYYYMMDD_ProjectID_Sample_Description_v01.csv)
- 