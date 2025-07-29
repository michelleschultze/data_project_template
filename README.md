# data_project_template
This repository acts as a reusable template for all of my future data projects. To use it, I clone the repo, then disconnect and assign it to a new project repo, where I delete unnecessary files and customize the structure before starting. This maintains clarity, proper logging of important information, and replicability in my workflow.

Key information about this project: 
```
[...]
```

Replicability guide: 
```
[...]
```

Folder structure: 
```
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
 ```

Notes for myself: [...] 
```
- Be sure to include metadata in your file names. (Example: YYYYMMDD_ProjectID_Sample_Description_v01.csv)
```
