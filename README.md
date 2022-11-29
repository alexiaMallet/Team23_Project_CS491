# Team23_Project_CS491
Final project of course CS491


The aim of this project is to create a classification network from Chest X-ray images to detect Covid 19. 
It relies on the structure COV19_ResNet defined in : Diagnostic Inference Engines for Early Detection of COVID‑19 - Ayturk Keles, Mustafa Berk Keles, Ali Keles - (https://link.springer.com/content/pdf/10.1007/s12559-020-09795-5.pdf). 
Data was downloaded from https://www.kaggle.com/datasets/andyczhao/covidx-cxr2?select=competition_test. Only the csv files with the name of images and corresponding labels were loaded on the GitHub Repository due to the too large number of images in the training set. 
To reproduce the code, one should download the data from the link available above and change the paths to access it in the notebook. The notebook should be placed along with the following files : 
- train folder (train_image) with all the training images inside 
- test folder (test_image) with all the testing images inside 
- csv file train.csv available when dowloading the dataset (same as the one loaded in the Git Hub repository) 
- csv file test.csv available when dowloading the dataset (same as the one loaded in the Git Hub repository) 

Description of the contents of the notebook as well as description of the functions are available in the notebook (that was executed on jupyter notebook, in the same directory as the data).

The notebook has the following table of contents : 
I. Set up
I.1. Library importation
I.2. Configuration and Hyper-parameters
I.3. Data importation
II. Network implementation
II.1. Implementation of Conv Block
II.2. Implementation of Identity Block
II.3. Implementation of ResNet Block
II.4. Implementation of the network COV19ResNet
III. Training the network
III.1. Settings
III.2. Training
III.3. Results

Refer to the notebook for details about the code. 
