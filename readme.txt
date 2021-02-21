Data sets:
The following data sets have been used:
1. Adult Data Set (also known as Census Income dataset)
Available at UCI repository 
https://archive.ics.uci.edu/ml/datasets/adult
2. Pima Indian Diabetes Database
Available at Kaggle 
https://www.kaggle.com/uciml/pima-indians-diabetes-database

Both the datasets are already added to this repository as adult.{data,test}
for Adult data set and diabetes.csv for Pima Indian Diabetes dataset.

Analysis:
1. census-final.ipynb notebook shows analysis of Adult dataset.
2. diabetes-final.ipynb notebook shows analysis of Pima Indian Diabetes dataset.

Runtime Environment:
All the code was tested on Python 3.7.6. The required packages are listed in
requirements.txt and may be installed through the following command:

$ pip install -r requirements.txt

The key packages (installed automatically with the above command) are:
Keras==2.4.3
Keras-Preprocessing==1.1.2
keras-tuner==1.0.1
matplotlib==3.3.0
numpy==1.18.5
pandas==1.1.0
scikit-learn==0.23.1
seaborn==0.10.1
tensorboard==2.3.0
tensorboard-plugin-wit==1.7.0
tensorflow==2.3.0
tensorflow-estimator==2.3.0
