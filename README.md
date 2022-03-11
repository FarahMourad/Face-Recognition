# Face-Recognition
## Download Data
### If it's not the first time you can skip this section
- Create a new folder in My Drive "kaggle_dataset"
- Create new API token from kaggle which downloads kaggle.json file
- Upload kaggle.json to kaggle_dataset folder
- Run Download Faces and Non-Faces Dataset
- Put car, cat, dog, flower, fruit and motorbike directly inside the non-face folder 
- delete any other folders
## Prepare the Faces and Non-Faces Dataset
- these blocks resize the nonfaces pictures to be the same as faces 
- convert the images into a flattened array stores the grayscale not the colors
## Merging Faces and Nonfaces
- split each dataset into 70 for training and 30 testing 
- split each dataset once again into 50 for training and 50 testing 
