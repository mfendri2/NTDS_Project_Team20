# Spammer on social network detection
<p> <center> (NTDS EPFL, Fall 2018)</center>  </p>
<p> Feature extraction, classification , and prediction of spammers on social network

In this project we focus on detecting spammers in a social network. The ultimate purpose of this project to identify (i.e., classify) the spammer users based on their relational and non-relational features.</p>
See the report for more details. </p>

## Running the code

The dataset represent users from tagged.com social network. The full dataset is provided in : https://linqs-data.soe.ucsc.edu/public/social_spammer/. </p>

Please think to change the name of the csv files to be able to run the code. These are the name of the different datasets we worked on : 
* usersdata.csv : this file contain the different users and they content features.
* filtered_relations_1.csv : This file  contains the edges of the relation 1 between the nodes. 
* filtered_relations_2.csv : This file  contains the edges of the relation 2 between the nodes. 
* filtered_relations_4.csv : This file  contains the edges of the relation 4 between the nodes.
* filtered_relations.csv : This file  contains the edges of the relation 5 between the nodes.
* filtered_relations_7.csv : This file  contains the edges of the relation 7 between the nodes.

These filtered relations files should be generated using the spammer_subnetwork.ipynb after downloading the full dataset from the link above. </p>
              
The repository contains two jupyter notebooks and one file containing all the datasets:
* spammer_subnetwork.ipynb : (©) Eda Bayram : Please  filter the original huge file based on the relation. Create relation 1 2 4 5 and 7: these are the relations we worked on for this project.
* feature_extraction.ipynb : This Notebook allows to compute the graph based features and create a final dataset containing the nodes of the network and the calculated features (content based and graph based).
* feature_exploration.upynb : This notebook try to better understand the computed features in details. 
* Classification.ipynb : This notebook allows to tune hyperparameters for different supervised learning algorithm on the dataset provided by the first notebook in order to classify the nodes beetween spammers and non spammers.</p>
 
## More details
See the project report provided also in the repository. The slides presented is also provided.


## Authors
<p> <center> (©) EPFL-NTDS-Group20-Fendri Hedi,Jeha Paul,Nguyen Minh Nguyet,Mantonanaki Christina  </center> </p>

