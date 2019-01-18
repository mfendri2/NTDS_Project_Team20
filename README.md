# Spammer on social network detection
<p> <center> (NTDS EPFL, Fall 2018)</center>  </p>
<p> Feature extraction, classification , and prediction of spammers on social network

In this project we focus on detecting spammers in a social network. The ultimate purpose of this project to identify (i.e., classify) the spammer users based on their relational and non-relational features.</p>
See the report for more details. </p>

## Running the code
The repository contains two jupyter notebooks and one file containing all the datasets:
* feature_extraction.ipynb : This Notebook allows to compute the graph based features and create a final dataset containing the nodes of the network and the calculated features (content based and graph based).

* Classification.ipynb : This notebook allows to tune hyperparameters for different supervised learning algorithm on the dataset provided by the first notebook in order to classify the nodes beetween spammers and non spammers.</p>

* Data file: The dataset represent users from tagged.com social network. This file Contains : 
                users(nodes) csv file describing each node: 3 content features (Age range,time after validation
                and gender) and  4 different relations between the nodes. 
                The full dataset is provided in : https://linqs-data.soe.ucsc.edu/public/social_spammer/. 
                Please think to change the name of the files, if you change them in the repository and use your own                           filtered dataset from the original one.  
              

## Authors
<p> <center> (©) EPFL-NTDS-Group20-Fendri Hedi,Jeha Paul,Nguyen Minh Nguyet,Mantonanaki Christina  </center> </p>

