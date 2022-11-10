# Myopia Predictor

### Predicting myopia status using unsupervised machine learning models

##### Authors:
* John Torgerson (JohnTorgerson)
---

##### Tools & Supplies:

* myopia patients database

* Python, Pandas, Matplotlib, plotly, graphviz, pydotplus, Scikit-learn
---

### Guide to Repo Contents:

* `README.md` is the contents file you're currently viewing
* `Myopia Predictor.ipynb` is the notebook running the code to predict myopia with clusters
* In folder, `Resources` is the following:
    1. `myopia.csv` is the raw data file used to analyze and predict myopia
---

### Observations:

* This data was preprocessed in various ways before I chose one
* Even after preprocessing different ways I still didn't know which best represented my data
* Random Forest Regression can be used on the data 'as is', or scaled, or selected, or both & it matters how it is preprocessed
* There remains a lot more to learn about the math happening behind the scenes with these regression tools

---

### Credits and Special Thanks

* Thanks to SMU; Kaitlin Kirasich, Trace Smith, and Bivin Sadler, PhD, for the educationl review article that helped me further my understanding of machine learning models https://scholar.smu.edu/datasciencereview/vol1/iss3/9