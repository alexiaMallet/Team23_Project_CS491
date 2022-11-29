# Team23_Project_CS491
Final project of course CS491


The aim of this project is to create a classification network from Chest X-ray images to detect Covid 19. 
It relies on the structure COV19_ResNet defined in : Diagnostic Inference Engines for Early Detection of COVID‑19 - Ayturk Keles, Mustafa Berk Keles, Ali Keles - (https://link.springer.com/content/pdf/10.1007/s12559-020-09795-5.pdf). <br>
Data was downloaded from https://www.kaggle.com/datasets/andyczhao/covidx-cxr2?select=competition_test. Only the csv files with the name of images and corresponding labels as well as test images were loaded on the GitHub Repository due to the too large number of images in the training set.  <br>
To reproduce the code (training the model), one should download the data from the link available above and change the paths to access it in the notebook. The notebook should be placed along with the following files : <br>
- train folder (train_image) with all the training images inside  <br>
- test folder (test_image) with all the testing images inside  <br>
- csv file train.csv available when dowloading the dataset (same as the one loaded in the Git Hub repository)  <br>
- csv file test.csv available when dowloading the dataset (same as the one loaded in the Git Hub repository)  <br>
The results presented are from the images in the test folder. 

Description of the contents of the notebook as well as description of the functions are available in the notebook (that was executed on jupyter notebook, in the same directory as the data).<br>

The notebook has the following table of contents : <br> 
I. Set up <br>
I.1. Library importation <br>
I.2. Configuration and Hyper-parameters <br>
I.3. Data importation <br>
II. Network implementation <br>
II.1. Implementation of Conv Block <br>
II.2. Implementation of Identity Block <br>
II.3. Implementation of ResNet Block <br>
II.4. Implementation of the network COV19ResNet <br>
III. Training the network <br>
III.1. Settings <br>
III.2. Training <br>
III.3. Results <br>

Refer to the notebook for details about the code. <br>
The file 'Results_predictions.csv' contains the predictions and ground truth for the model. 
