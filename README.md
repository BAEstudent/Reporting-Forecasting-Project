# Reporting-Forecasting-Project

### This is a repo for Reporting Forecasting project at CMF made by Kirill Yudaykin.

---

### Data Analysis

See `Forecasting_EAD.ipynb`

The data from all available Income Statements was compiled into two list of pandas DataFrames (one list for train data, on list for test data).

Some preliminary data analysis has been conducted.

### Quality Metrics

SMAPE metric will be used for the model valuation.

I am also attempting to construct a metric, that will penalize overforecasting more than underforecasting, because we might assume that overforecasting is wose, because managers might undertake riskier inestment decisions. I am planning on using `Mean Directional Accuracy` (MDA). This instrument will alow us to separate underfitting and overfitting. 
