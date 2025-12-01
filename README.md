This repository contains two dataset files used during the development of the visualisation tool:

1. Original Dataset - Filename: "Scooby-Doo Completed.csv"
This is the unmodified dataset downloaded directly from the source - TidyTuesday Scooby-Doo project
It includes all attributes and raw episode-level information before any filtering, reshaping, or transformation

3. Filtered / Cleaned Dataset - Filename: "ScoobyDoo_cleaned_FINAL.csv"
This dataset is derived from the original and includes:
1. Removal of invalid or missing entries (e.g., IMDb ratings, dates)
2. Cleaning of categorical fields (countries/states, terrain values)
3. Structural adjustments required for the Vega-Lite dashboard
4. Preparation for folding character action fields into long format

This cleaned dataset is the one actually used by the Vega-Lite implementation
