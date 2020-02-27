

Motivation

This dataset is created for prediction of salaries from an Indian perspective.The dataset contains several parameters which are considered important during the job. The parameters included are : 1. Id 2.job 3.sector 4.BasePay 5. OvertimePay 6. OtherPay 	7. Benefits 8. TotalPay 9.TotalPayBenefits 10.JobTitle 11.Year 12.Notes 13.Agency 14.Status.This dataset is inspired by the monthly_salary_brazil. Data Science-Blog

Here analysis is done pandas to understand variuos parameter that affect employee to get job. The Code is written in Python 3.6.5 . If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. Libraries

Pandas python matplotlib numpy pip scikit-learn Installations

To install pip run in the command Line

python -m ensurepip -- default-pip

to upgrade it

python -m pip install -- upgrade pip setuptools wheel

to upgrade Python

pip install python -- upgrade

Additional Packages that are required are: Numpy, Pandas, MatplotLib, Pytorch, PIL and json which can be downloaded using pip command.

pip install numpy pandas matplotlib pil

or conda

conda install numpy pandas matplotlib pil

In order to intall Pytorch head over to the Pytorch site select your specs and follow the instructions given. Viewing the Jyputer Notebook

In order to better view and work on the jupyter Notebook I encourage you to use nbviewer . You can simply copy and paste the link to this website and you will be able to edit it without any problem. Alternatively you can clone the repository using

git clone https://github.com/koustubha-prog/data-science-blog-post-for-salary

then in the command Line type, after you have downloaded jupyter notebook type

Linear Regrssion Scikit-learn is a powerful Python module for machine learning. Just import the library and start using model from it.

import scikit-learn

jupyter notebook locate the notebook and run it. Command Line Application Data File - Salaries.csv CSV file

In order for the network to print out the employee data .csv file is required. By using a .csv file the data can be sorted into folders with numbers and those numbers will correspond to specific names specified in the .json file. Data and the json file employee Blog Post IPython Notebook

It has all the pandas code written to analyse the Salaries Predict CSV File, visualize results(BAR Charts,Heat Map) and evaluate them. Blog Post

t/wiki/data-employee-Statistics Data Analytics using linear Regression Model

Cloud Services -- There are many paid cloud services that let you train your models like AWS or Google Cloud Coogle Colab -- Google Colab gives you free access to a tesla K80 GPU for 12 hours at a time. Once 12 hours have ellapsed you can just reload and continue! The only limitation is that you have to upload the data to Google Drive and if the dataset is massive you may run out of space.

However, once a model is trained then a normal CPU can be used for the predict.py file and you will have an answer within some seconds. Hyperparameters-The data used specifically for this assignemnt are a database are not provided in the repository as it's larger than what github allows. Nevertheless, feel free to create your own databases and train the model on them to use with your own projects
