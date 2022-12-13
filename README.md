Final Project
This code is for my project which achieved 97% using SVM model. This word had been published in Computational Journal. 
For more details and an explanation of the work find the paper at the link: https://www.mdpi.com/2079-3197/10/8/138

# Oil-and-gas-pipeline-leakage

* Randonmly generated data without corrosion defect.
* Used data.csv for Polynomial and linear regression -  polynomial regression.ipynb
* Randomly generated fake_data2.csv in new.py without "CR-corrosion defect" feature.
* Predicted  "CR-corrosion defect" feature for fake_data2.csv using the .ipnyb above.
* Final dataset is called generated_data.csv
* Created a python script for the model - digitalModel.py
* Created a physical model data with 50 data points- stream.csv
* Created an endpoint for the model  - app.py
* Created an endpoint streaming to the digital model to -app2.py (http://127.0.0.1:5001/)

# To get a feel and for the values to output in mm:
* Run app.py on terminal
* Run app2.py on terminal

# To get a feel and for the values to output in NACE classification:
* Run app_1.py on terminal
* Run app_2.py on terminal
