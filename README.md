# COVID19D_detector
A deep learning algorithm using Colab and Tensorflow to predict whether or not a person has COVID-19 by uploading his CT scan 
The accuracy achieved in this model is 80%, we are aiming to achieve about 90% as we are working on that
The content of this folder is constatly changing cuz we are improving the model and adding more data.
I have uploaded the whole folder in my drive to be used and improved immediately.
This folder contains:

1- images: Training, validation and test pics are mixed. You might consider the Traning and Vlidation only cuz you can find a CSV file 
here in this folder containing the identifiers, so you can address them easily. Even though the test pics are mixed with others you can just negelect them for now.
If you want to organize it yourself, you might consider this link which contains all the dataset
https://paperswithcode.com/paper/covid-ct-dataset-a-ct-scan-dataset-about#code

2- The COVID-19 dataset identifers and labels in this file covid_data.csv in the data folder

3- logs and models you will understand them when you run the code

4- Test folder: contains a test picture for a covid-19 patient which I received today from a doctor, the algorithm reported 0.7% positive and 0.04 negative which means the algorithm was totally right. 
