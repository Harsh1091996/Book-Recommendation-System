# BOOK RECOMMENDATION SYSTEM
These project is part of the “Machine Learning &Advanced Machine Learning” curriculum as capstone projects at [AlmaBetter](https://www.almabetter.com/). 

#### -- Project Status: [Completed]

## Objective<br>
The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge
amount of income when they are efficient or also be a way to stand out significantly from competitors. 


### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning


### Technologies
* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn
* Surprise

### Data
The Book-Crossing dataset comprises 3 files.
* Users : 
Contains the users. Note that user IDs (User-ID) have been anonymized and map to
integers. Demographic data is provided (Location, Age) if available. Otherwise, these
fields contain NULL values.
* Books : 
Books are identified by their respective ISBN. Invalid ISBNs have already been removed
from the dataset. Moreover, some content-based information is given (Book-Title,
Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web
Services. Note that in the case of several authors, only the first is provided. URLs linking
to cover images are also given, appearing in three different flavors (Image-URL-S,
Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the
Amazon website.
* Ratings :
Contains the book rating information. Ratings (Book-Rating) are either explicit,
expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,
expressed by 0.

## Project Description
* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treaatment
* Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
* Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).

## Memory Based Collaborative Filtering
Memory-based methods use user rating historical data to compute the similarity between users or items. The idea behind these methods is to define a similarity measure between users or items, and find the most similar to recommend unseen items.

## Model Based Collaborative Filtering
Model-based CF uses machine learning algorithms to predict users rating of unrated items. There are many model-based CF algorithms, the most commonly used are matrix factorization models such as to applying a SVD to reconstruct the rating matrix, latent Dirichlet allocation or Markov decision process based models.

Refer this [**blog**](https://towardsdatascience.com/how-does-collaborative-filtering-work-da56ea94e331) for more information on collaborative filtering

## Needs of this project

- data exploration
- data processing/cleaning
- recommendation system developer

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Project Documentation is being kept [here](https://github.com/Harsh1091996/Book-Recommendation-System/blob/main/Book_Recommendation_System_cohort_nilgiri.docx) within this repo.

3. Complete notebook containing Data exploration/Data processing/transformation/model development is being kept [here](https://github.com/Harsh1091996/Book-Recommendation-System/blob/cb7aab70db7b7effe4457e66c2fc26b6e85f64c4/Book_Recommendation_System.ipynb)
 

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Himanshu Sharma | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himan-10/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Harsh1091996)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://harshsharma1091996.medium.com/)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1pyTvHo2Ec4xfCszL7YkHYAwWgFi5Uf2T/view?usp=sharing)
