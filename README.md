# Online Python Tutor: Quantitative results and visualizations
Replication package for FSE 2025 Submission #387

For anonymity of authors and human subjects, raw annotations data is not included here. 
Instead, we provide the anonymized output obtained by running the data management and preprocessing scripts.
These scripts are also provided, for reference. 
The dataset is contained in `annotations-data-analysis/derived-dataframes/` and is valid input to the analysis scripts in `annotations-data-analysis`.

## Contents
- `data-management/scripts/data-management_qdpx-to-csv.ipynb` --- script for step 1 of data management/processing
- `data-management/scripts/data-management_csv-cleaning.ipynb` --- script for step 2 of data management/processing
- `data-management/scripts/balanced-f-measure.ipynb` --- script for IRR evaluation
- `annotations-data-analysis/regression-analysis-data-preprocessing.ipynb` --- script for step 3 of data management/processing
- `annotations-data-analysis/derived-dataframes/regression-data-v5/` --- anonymized version of the dataframes output by data management/processing
- `annotations-data-analysis/glmer-regression-analysis-v3.Rmd` --- script for primary quantitative analysis (GLMER models)
- `annotations-data-analysis/rscripts/` --- for ease of use, individual model fitting steps are copied into short R scripts in this directory
- `annotations-data-analysis/counting-things.ipynb` --- script to generate counting results and data visualization presented in the paper
- `annotations-data-analysis/output/` --- data visualizations presented in the paper

