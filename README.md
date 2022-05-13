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
2) This notebook uses a pre-trained Facenet model to generate embeddings. The pre-trained model cannot be uploaded to github because of size constraints. The model is uploaded here : <a href="https://drive.google.com/file/d/142A5LrfirU6Xdksjp_RfAe5rGc6g7VwU/view?usp=sharing">Pre-trained Facenet</a>
3) Once the pre-trained model "facenet-keras.h5" is downloaded, update the absolute path of pre-trained model in the jupyter notebook here "model = load_model('{ absolute path of the facenet model }')".
4) Download the dataset, from the dataset named as "soccer-players" in the repo. 
5) Update 3 absolute paths in the jupyter notebook using the dataset location : 

    ALT_PATH = ' { path to one particular folder in the soccer-players dataset} | example : /pathToDataset/soccer-players/Mbappe/'

    ALT_TRAIN_PATH = '{ 'path to entire dataset ' }  | example :  example : /pathToDataset/soccer-players/'

6) Execute the Facenet_Clustering.ipynb line-by-line and the results would be generated in the end. 

# Steps to replicate the results for Approach 3

1) Download the "C256_Facenet_Clustering.ipynb" notebook and the CS256_Dataset.
2) Download the pretrained "facenet-keras.h5" model.
3) Initialize the path variables as mentioned below (the dataset is to be kept in such directory format):

   ALT_PATH = '/content/drive/MyDrive/CS256_Dataset/Football_Images/Images/'  (images are present inside the "Images" folder)

   ALL_PATH = '/content/drive/MyDrive/CS256_Dataset/Football_Images/'    ("Images" folder is present inside the "Football_Images" folder)
4) Execute the notebook.

-----------------------------------------------------------------

# Documentation.

The documentation folder contains the project report and the slides used for presentation across milestones.
1) <a href="https://github.com/AtharvaSharmaSJ/Facenet-clustering/blob/main/documentation/Project%20Report.pdf">Project Report</a> is the final report for this project.
2) <a href="https://github.com/AtharvaSharmaSJ/Facenet-clustering/blob/main/documentation/Milestone%201%20slides.pdf">Milestone 1 slides</a> were used with the Milestone 1 presentation.
3) <a href="https://github.com/AtharvaSharmaSJ/Facenet-clustering/blob/main/documentation/Milestone%203%20slides.pdf">Milestone 3 slides</a> were used with the Milestone 3 recording.
4) There were no slides used in Milestone 2.
