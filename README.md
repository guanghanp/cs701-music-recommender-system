## Building A Music Recommender System
### Middlebury College, Computer Science CSCI 701 (Fall 2020)

### about
In this project, we present a comparative study of collaborative filtering, content-based filtering, and hybrid models to establish the most suitable recommender system for the KKBox music preference dataset available on Kaggle as part of the WSDM - KKBox's Music Recommendation Challenge.

view our website [here](https://guanghanp.github.io/cs701-music-recommender-system/)

### building

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

You should have Python and Jupyter Notebook running on your computer in order to execute this program.

1. Clone the repository to your local computer:

    ```
    git clone https://github.com/guanghanp/cs701-music-recommender-system.git
    ```

1. Use pip to install necessary dependencies:

    ```
    pip install -r requirements.txt
    ```

1. Download the KKBox music preference dataset from the [Kaggle Challenge](https://www.kaggle.com/c/kkbox-music-recommendation-challenge/data), and unzip the files.

### usage

The program can be executed from the command line like this:

```
jupyter notebook kkbox-music-recommendation.ipynb
```

After opening the notebook, change the file paths in the second code block to the paths of the dataset downloaded. 

The notebook is then ready to run. The whole program might take a while to complete, since it is training many different models and creating data visualizations.

### limitations
Our final results are based on models trained using only 20\% of the available training data. The next step is to train our models using more training data. To try and improve the accuracy further, we may need to explore even more sophisticated feature engineering, for example, computing non-linear features and testing subsequent performance on a validation set. Moreover, we only experimented with a naive hybrid model. Our results indicate that hybrid models are promising; implementing different ensemble techniques for combining the content-based and collaborative models is therefore another possible area of further exploration. 

### author
- Guanghan Pan
- Musab Shakeel

### references
- [WSDM - KKBox's Music Recommendation Challenge](https://www.kaggle.com/c/kkbox-music-recommendation-challenge/data)
- [Link to our paper]()


