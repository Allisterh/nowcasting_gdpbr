## Data 

Data used in this research are from multiple sources including the Central Bank of Brazil (BCB), IBGE, ANP, Google Trends, Ipeadata FGV and others. 

Data were collected by API from BCB, Ipeadata and Google Trends, and manually in FGVDados.

You'll find in this folder:

- ``meta_data``: data dictionary with all series used in this research;
- ``now_data_raw``: csv file with all raw series collected;
- ``data_tf``: csv file with all series transformed (stationary series transformed with first or second differences);
- ``data_tfpca``: csv file with all series transformed (stationary) and transformed again by Principal Component Analysis (PCA) to use in models based on dimensionality reduction;
- Other files: ipynb files (Jupyter Notebooks and R files) with series analysis applied to transform and visualize data. 
