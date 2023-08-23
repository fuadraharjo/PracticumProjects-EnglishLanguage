### Gold Ore Extraction Prediction Model in Mining Companies

A gold mining company requires a `machine learning model` to predict the extraction of gold ore from the mine. The company provides us with the raw datasets namely the `train`, `test`, and `full` datasets. The extraction and refining process of `gold - Au` from gold ore goes through several stages of `process technology`, namely `flotation`, `primary stage refining`, and `secondary stage refining`. At each `stage` or the process will produce `gold - Au` concentrate, several other concentrates, and some `residue`.

The `machine learning` model is expected to get rid of other non-profitable parameters and focus on those that do. To find out that the `machine learning` model has good quality, it is necessary to test it with the `cross-validation` technique and calculate the SMAPE `(Symmetry Mean Absolute Percentage Error)` value.

Some of the goals and formulation of the problem for this project include:
- How is the distribution of `Au`, `Ag`, and `Pb` metal concentrated in each technological process (`stage`)?
- Find out the particle size distribution of the feed for the `train` and `test` datasets.
- Knowing the distribution of concentrates in each technological process (`stage`) for the `train` and `test` datasets.
- How many features/parameters can be reduced?
- Among the following types of `model machine learning`: `linear regression`, `random forest`, and `K-Nearest neighbors`. Which gives the best results using the SMAPE `cross-validation` scoring technique?
- What is the `SMAPE` score produced by the `best model` in the `test` dataset?

| Project | Description | Library |
| ------- | ------- | ------- |
| [Model Prediction for Gold Ore Extractions](https://github.com/fuadraharjo/PracticumProjects-EnglishLanguage/blob/27f87b0089338b8da967337094eae85c1352d6d1/Project-8%20-%20Gold%20ore%20extraction%20prediction%20model/Gold%20ore%20extraction%20prediction%20model.ipynb) | Exploratory Data Analysis (EDA) and Model Prediction Using Cross-Validation Technique with SMAPE (Symmetric Mean Absolute Percentage Error) Score. | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn* |