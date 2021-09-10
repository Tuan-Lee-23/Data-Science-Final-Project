Movies Revenue Forecast
==============================
![End semester](https://res.cloudinary.com/practicaldev/image/fetch/s--hGvhAGUu--/c_imagga_scale,f_auto,fl_progressive,h_500,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/mih10uhu1464fx1kr0by.jpg)

# Collaborators
| Student's ID | Full name | Github account|
| ----------- | ----------- | -------------|
| `18127245`    | Lê Ngọc Tuấn| [@TuanLe23](https://github.com/Tuan-Lee-23)|
| `18127113`   | Võ Văn Quốc Huy |[@HuyVoMindX](https://github.com/HuyVoMindX)|   

## Instructor
- `HCMUS` **Trần Trung Kiên** ([@ttkien](ttkien@fit.hcmus.edu.vn))
- `HCMUS` **Phan Thị Phương Uyên** ([@ptpuyen](ptpuyen@fit.hcmus.edu.vn))

---
<div style="page-break-after: always"></div>

# Description
## Movies Revenue Forecast.  
The project this time our team will be based on collecting data from TMDB, IMDB, and Box Office Mojo through Scrap information or API provided by the site. The team then preprocesses and visualizes some of the information contained in the dataset it collects. Data preprocessing and model building are here with the LightGBM model. Besides, use Feature Engineering to discover features that have not appeared and re-evaluate. Finally, blend XGBoost with LightGBM for the best results.

## Data
![End semester](https://i.ibb.co/tHsCS5Q/Screenshot-2021-09-10-200927.png)

## Workflow
- Building dataset from TMDB api
- Replace missing values (revenue, budget) with IMDB and Box Office Mojo  
- Data exploring
- Data cleaning
- EDA
- Build default model (LightGBM with default hyperparameters)
- Feature engineering
- Tuning hyperparameters
- Train final model
- Blend LightGBM with XGBoost for lower variance

---
<div style="page-break-after: always"></div>

# Result
    - Final result:
	- MAPE (mean absolute percentage error): `0.0832`
	- R squared: `0.703`
![final_result](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/Final_result.png)
![shap](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/SHAP.png)
![tree](https://github.com/Tuan-Lee-23/Data-Science-Final-Project/blob/main/reports/Tree.png)


# Project Organization
------------
    notebooks/
    ├─ Cleaning_+_EDA_+_Modeling.ipynb    (Main notebook)
    ├─ Scrap IMDB data.ipynb    (scrape IMDB's budget)
    ├─ box_office_mojo_revenue.ipynb    (scrape BoxOfficeMojo's revenue)
    ├─ tmdb_api_request.ipynb    (data from TMDB api)
    data/
    ├─ raw/
    │  ├─ budget.csv    (budget from imdb)
    │  ├─ raw.zip   (data from tmdb api)
    │  ├─ description.txt    (description of tmdb.csv)/
    │  ├─ budget_revenue_tmdb.csv    (revenue from Box Office Mojo)
    │  ├─ tdmb.csv
    docs/
    models/
    ├─ best_params.pkl    (GridSearch tuned hyperparameters)



--------
