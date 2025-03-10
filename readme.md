# Fraud detection with Pyspark

## General
- I prepare those 2 notebooks to train my ML skills and learn `PySpark` / `MLFlow` frameworks
- I used `PySpark` to:
    - run EDA on dataset
    - feature engineering
    - preprocessing
    - create a pipeline with ML classification models
- I used `MLFlow` to logg ml experiments
- Other packages: `plotly`, `pandas`

## Structure
- `00_eda.ipynb` - notebook with eda, testing features, testing preprocessing functions
- `01_pipeline.ipynb` - preprocessing & ML pipeline; MLFLow expeirment

# Quick Run
- create python env (I used 3.12.1 version)
- install requirements, e.g.
```
pip install uv
uv pip install -r requirments.txt
```
- create `spark_dir` directory for temp files
- create `resources` dir for datasets

## Dataset
Fraud detection dataset: https://www.kaggle.com/datasets/kartik2112/fraud-detection

