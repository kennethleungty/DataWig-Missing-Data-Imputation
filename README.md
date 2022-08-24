# Imputation of Missing Data in Tables with DataWig
Link to TowardsDataScience article: https://towardsdatascience.com/imputation-of-missing-data-in-tables-with-datawig-2d7ab327ece2 

### Context
Missing values in real-world datasets is a common phenomenon that poses a key challenge for all data practitioners. This issue is even more challenging when the dataset contains heterogeneous data types.

In this project, we look at how DataWig can help us perform the imputation of missing values in tabular data effectively and efficiently.

### DataWig
Developed at Amazon Science, DataWig is a software package that applies missing value imputation to tables containing heterogeneous data types, i.e., numerical, categorical, and unstructured text.

The goal is to build a robust and scalable framework that allows users to impute missing values without extensive engineering efforts or a machine learning background.

DataWig learns machine learning models as part of its approach to imputing missing values in data tables.

Besides handling heterogeneous data types automatically, DataWig also executes efficiently on CPUs and GPU by learning parameters in an end-to-end fashion using the Apache MXNet API.

### Project Structure
- `artifacts`: Output from imputation model runs (i.e. model, data, and metrics)
- `data`: CSV file of the Heart Disease dataset
- `images`: Illustrations used in the article
- `notebooks`: Jupyter notebook for the DataWig Python implementation demo
- `references`: Articles and papers for DataWig

### Data Source
- https://archive.ics.uci.edu/ml/datasets/Heart+Disease

### References
- https://www.jmlr.org/papers/volume20/18-753/18-753.pdf 
- https://github.com/awslabs/datawig
- https://datawig.readthedocs.io/en/latest
- https://arxiv.org/pdf/2205.04731.pdf 
- https://aws.amazon.com/blogs/industries/how-sigmoid-uses-datawig-from-amazon-science-for-missing-value-imputation-to-make-cpg-dataset-ready-for-machine-learning
- https://buildmedia.readthedocs.org/media/pdf/datawig/latest/datawig.pdf
