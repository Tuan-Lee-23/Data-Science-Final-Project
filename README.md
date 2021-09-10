Movies Revenue Forecast
==============================

# Collaborators
| Student's ID | Full name | Github account|
| ----------- | ----------- | -------------|
| `18127245`    | Lê Ngọc Tuấn| [@TuanLe23](https://github.com/Tuan-Lee-23)|
| `18127113`   | Võ Văn Quốc Huy |[@HuyVoMindX](https://github.com/HuyVoMindX)|   

## Instructor
- `HCMUS` **Trần Trung Kiên** ([@ttkien](ttkien@fit.hcmus.edu.vn))
- `HCMUS` **Phan Thị Phương Uyên** ([@ptpuyen](ptpuyen@fit.hcmus.edu.vn))

![End semester](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/posterfilm.jpg)

---
<div style="page-break-after: always"></div>

# Description
Our project name: Movies Revenue Forecast.  
The project this time our team will be based on collecting data from TMDB, IMDB, and Box Office Mojo through Scrap information or API provided by the site. The team then preprocesses and visualizes some of the information contained in the dataset it collects. Data preprocessing and model building are here with the LightGBM model. Besides, use more Feature Engineering to discover features that have not appeared and re-evaluate. Finally, use more XGBoost to blend these models for the best results.

---
<div style="page-break-after: always"></div>

# Result
    - Final result:
        - MAPE(Mean Absolute Percentage Error): `0.06873`  
        - R squared: `0.7692`
![final_result](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/Final_result.png)
![shap](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/SHAP.png)
![tree](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/Tree.png)


# Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    │
    │
    ├─────────────────────────────────────────────────────────────────────────────────────────────────


--------
