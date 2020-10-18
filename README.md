# User Rating Classification using NLP & Creation of a Recommendation Engine

The aim of this project is to Classify the Rating Stars of Restaurant Reviews from users utilising the Yelp Dataset.

What is more, the project extends to the creation of a Recommendation Engine based on the review of a user.

## Code

In this repository, you will find 5 ipynb files, one for each part of the project:

* [1-Data-Loading-Cleaning.ipynb](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/1-Data-Loading-Cleaning.ipynb): In this notebook, we import the initial dataset from Yelp.com and perform the appropriate modifications to create the final data in order to continue the analysis. To be more specific, we clean the data, keep only the meaningful columns and apply thorough text preprocessing.
* [2-Data-Preprocessing.ipynb](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/2-Data-Preprocessing.ipynb): In this notebook, we create tokenizer for train dataset and create input and output variables for both train and test data.
* [3-EDA-Visualization.ipynb](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/3-EDA-Visualization.ipynb): In this notebook, we provide some insights from our data by creating the respective tables and plots.
* [4-Model-Classification.ipynb](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/4-Model-Classification.ipynb): In this notebook, we apply 4 different models and construct several evaluation metrics and plots. Finally, we choose the best model according to a few criteria and metrics.
* [5-Recommendation-System.ipynb](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/5-Recommendation-System.ipynb): In this notebook, we create the Recommendation Engine based on the review of a user.

## Data

In order to execute all the code one has to access the data in the following drive link:
https://drive.google.com/drive/folders/1JXBiTpofCK8tV6eeNuFHhCYBv5iVBK5y

In this folder, all the initial data reside as it has been downloaded from yelp.com. The first one 'yelp_academic_dataset_business.json' is a 
json file which contains all the businesses. As both reviews and user datasets are large enough to process, we have created 21 pickle files for the data 
of reviews and 5 same files for the users dataset. Furthermore, in the drive folder, one can find the final dataset as Nevada.pkl which we use 
for our analysis. Moreover, there is a folder containing the files: tokenizer, x_train, x_test, y_train, y_test in pickle files again.
Finally, we have included the 4 models. In order for someone to use the models and their weights it is enough to load the models through keras. 
If one wants to extract the weights of our final model he/she has to load the model as it is described in the 5th ipynb (5-Recommendation-System.ipynb), 
where we get the weights of the best model.

All the data are in zipped folders to shrink even more their sizes.

We have to mention that if one wants to run the code for the two models that contain pre-trained embeddings (Glove & FastText), then he/she has to download the [glove.6B.300d.txt](https://nlp.stanford.edu/projects/glove/) for Glove Embeddings and [wiki-news-300d-1M.vec](https://fasttext.cc/docs/en/english-vectors.html) for FastText Embeddings.

## Report

The final report for the Project can be found under the file [**"ML_CA Project.pdf"**](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/ML_CA%20Project.pdf).

## Presentation
The final presentation for the Project can be found under the file [**"Presentation_ML_CA.pptx"**](https://github.com/AthinaSpanou/User-Rating-Classification-using-NLP/blob/main/Presentation_ML_CA.pptx).

