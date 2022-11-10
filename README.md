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

* Initially, I looked at the data in clusters using tsne, and there may have been other preprocessing methods that may have worked better but instead I moved directly onto reducing the data in pca, having it scaled, so we could look at it using K-means.  
* With more time, I may have wanted to explore tsne with more in depth granularity by manipulating the data first. 
* That said combining reducing the data with pca, and examining it using Kmeans was fairly effective at predicting clusters.

---

### Credits and Special Thanks

* Reduced dataset from Orinda Longitudinal Study of Myopia conducted by the US National Eye Institute https://clinicaltrials.gov/ct2/show/NCT00000169