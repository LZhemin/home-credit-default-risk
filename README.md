# home-credit-default-risk
This project serves as a platform for hands‐on practice on how to perform a real‐world
KDD (knowledge discovery from data) task from the beginning (data pre‐processing  ‐ 
data collection, cleaning, etc) to the final stage (data post‐processing  ‐ evaluation and
presentation, etc). 

We have chosen the [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) from Kaggle as dataset and the objective is to predict how capable each applicant is of repaying a loan. Presentation slides can be found [here](https://github.com/LZhemin/home-credit-default-risk/blob/master/Presentation.pdf).
# Getting Started
## Google Colab
[Google Colab](http://colab.research.google.com) is used for this project.

Some advantage is that it is a free Jupyter Notebook alike environment that requires no setup and runs entirely on Google's server. Multiple users can edit the notebook at the same time, making the project much more collaborative. Most of the libraries and packages that will typically be used in a Data Analytics/ Machine Learning/ Deep learning project are also pre-installed in the environment. Python commands are executed in the cells and Linux command, such as removing of files can be performed too in the cell with ! prepended to the command such as ```!rm data.csv```. For instance, we can do a XGBoost installation by executing the command ```!pip install xgboost``` in a cell. It also supports GPU and TPU accelerated runtime, making the overall computational time much lower.

One disadvantage the using virtual machine instances and it will be recycled/refreshed every 12 hours and we will need to upload the dataset every time the VM is recycled.

To begin the project, choose to open the respective python notebook via the interface for Google Colab under the file tab in the header. After opening the notebook, you can upload the dataset in the dataset folder, by selecting the files tab on the left panel of the interface. To speed up the upload, you can upload the compressed dataset and uncompress them in the Colab Notebook itself, instead of uploading the raw dataset.
    
****
***Disclaimer:*** This repo is deprecated and no longer maintained. The Project was submitted as part of the course project for CZ4032 DATA ANALYTICS & MINING at NTU in AY 18/19 Semester 1. All rights reserved to Nanyang Technological University and the Designer of course CZ4032. The author will bear no responsibilities for any issues arose from academic integrity or honour code violations of anyone who takes this repository as a reference.