# Facenet-clustering
Files in this repo are a part of the final project for course CS256 - SJSU. 

Team members : 
1) Atharva Sharma
2) Abhijn Chadalawada
3) Devinesh Singh
4) Nishant Yadav


-----------------------------------------------------------------

# Steps to replicate the results.

1) First download the Facenet_Clustering.ipynb notebook on your local machine.
2) This notebook uses a pre-trained Facenet model to generate embeddings. The pre-trained model cannot be uploaded to github because of size constraints. The model is uploaded here : https://drive.google.com/file/d/142A5LrfirU6Xdksjp_RfAe5rGc6g7VwU/view?usp=sharing
3) Once the pre-trained model "facenet-keras.h5" is downloaded, update the absolute path of pre-trained model in the jupyter notebook here "model = load_model('{ absolute path of the facenet model }')".
4) Download the dataset, from the dataset named as "soccer-players" in the repo. 
5) Update 3 absolute paths in the jupyter notebook using the dataset location : 

    ALT_PATH = ' { path to one particular folder in the soccer-players dataset} | example : /pathToDataset/soccer-players/Mbappe/'

    ALT_TRAIN_PATH = '{ 'path to entire dataset ' }  | example :  example : /pathToDataset/soccer-players/'

6) Execute the Facenet_Clustering.ipynb line-by-line and the results would be generated in the end. 
