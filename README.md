# Canadian Vehicle Fuel Analysis

A CSCI 2227 project investigating how engine size and vehicle class are associated with rated fuel consumption among gasoline vehicle configurations offered in Canada for model years 2015–2024.

## Project progress

- Phase 1: Proposal completed and submitted.
- Phase 2: Data wrangling in progress. The notebook imports and explores the original CSV, filters gasoline records, and documents data preparation.
- Phase 3: Visualization and statistical analysis planned.

## Files

- `Phase1/phase1.pdf`: Project proposal.
- `Phase1/README.md`: Phase 1 submission statement.
- `Phase2/phase2.ipynb`: Data preparation notebook in progress.
- `Data/my2015-2024-fuel-consumption-ratings.csv`: Original source dataset.

## Running the notebook

Open `Phase2/phase2.ipynb` in Jupyter with Python and pandas installed. Run the cells from top to bottom. Keep the folder structure unchanged: the notebook loads the CSV using the relative path `../Data/my2015-2024-fuel-consumption-ratings.csv`.

## Data source and licence

Fuel consumption ratings from Natural Resources Canada, downloaded through the Government of Canada Open Government Portal:
https://open.canada.ca/data/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

Contains information licensed under the Open Government Licence – Canada:
https://open.canada.ca/en/open-government-licence-canada/

The data licence applies to the source dataset. No separate licence has been selected for the project code or writing.

## Interpretation

The records represent listed vehicle configurations and standardized fuel consumption ratings. They do not represent sales-weighted averages or drivers' observed fuel use. Findings will be added after the analysis is completed.