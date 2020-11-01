# C3 :challenge:



## Structure of the repository

The repository's structure is the following :

```
data/
    interim/
    processed/
    raw/
models/
notebooks/
    exploratory/
    reports/

references/
src/
    *.py
```

Here is each file or directory's purpose:
* `data/`: will contain all the data of the project (not stored on github, cf. `.gitignore`), with a split between:
  * `external/`: Data from third party sources
  * `interimn/`: Intermediate data that has been transformed
  * `processed/`: The final data sets
  * `raw/`: Origianl, immutable data (csv of feather files generally)
* `models/`: Trained and serialized models, model predictions
* `notebooks/`: Jupyter notebooks. Naming convention is a trigram (for ordering), a number and a short ' _ '  delimited description (e.g `LeG_1_read_data.ipynb`). There is also a split between :
  * `exploratory/`: Contains initial exploration
  * `reports/`: More poliseh work that could be exported as html for reporting

* `references/`: Data dictionaries, JSON files, and all orther explanatory tools
* `src/`: Source code for use in this project
  * `data/`: Scripts to download or generate data
  * `features/`: Scripts to turn raw data into features
  * `model/`: Scripts to train models and then use trained models to make predictions

## xx prediction
