# Phase 2 Data Wrangling

Author: Matthew Meede

This submission is complete and addresses the Phase 2 specifications. No required sections are missing.

## Submitted file

- phase2.ipynb: Executed notebook containing the project title and author, data acquisition, initial exploration, documented cleaning, data enrichment, validation checks, and the final analytical dataset.

## Running the notebook

Use Python with pandas, NumPy, IPython, and Jupyter. Run all cells from top to bottom. The notebook first looks for ../Data/my2015-2024-fuel-consumption-ratings.csv. If that local file is absent, it loads the CSV directly from the official source URL, requiring internet access. The raw dataset is not included in the school-server submission and is not saved to disk by the notebook. No other supporting scripts are required.

## Preparation results

The source snapshot has 10,060 records. Filtering to gasoline codes X and Z for model years 2015–2024 retains 9,495 records. Optional CO2 and smog rating columns are excluded. Original vehicle classes are preserved; Small and Standard sport utility vehicles are grouped as SUV, and only Compact is grouped as Compact. Other classes remain available. Estimated annual fuel use assumes 15,000 km. All 15 validation checks pass.

The final in-memory datasets are analytical (9,495 rows), suv_compact (4,028 rows), and yearly_summary. Saved notebook outputs show the results; rerunning regenerates these datasets without requiring a separate cleaned CSV.

## Source and licence

Natural Resources Canada fuel consumption ratings:
https://open.canada.ca/data/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

Contains information licensed under the Open Government Licence – Canada:
https://open.canada.ca/en/open-government-licence-canada/
