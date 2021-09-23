# Comment: Combining Predictions for Accurate Recommender Systems

<p align="justify">
    The paper is about showing the superiority of ensemble recommender systems over any single collaborative filtering (CF) algorithm. It is used the Netflix Prize dataset. Specifically, for experimenting with the ensembles, it was used the probe set divided in two equal parts (chosen randomly), a pTrain set and a pTest set. Using these sets, it was calculated the root-mean-square-error (RMSE) for different ensemble methods to determine the best parameters for each one and the comparison between methods.
</p>

<p align="justify">
    The paper is written with all the details and the steps necessaries to replicate the experiment. It is used a specific dataset, especific CF algorithms and specific ensemble algorithms. Furthermore, all the results are included in tables/figures, making it easier to compare, including training time, which is important on large datasets. Additionally, the source code and dataset are available. All these things add value and reliability to the paper, as it gives tons of information on every algorithm which is useful to use on other problems.
</p>

<p align="justify">
    All the algorithms used where CF ones, including item and user based KNN and matrix factorization techniques. It would be interesting to see the results using content-based (CB) algorithms. The Netflix Prize dataset only contains the movies' title and year of release (<a href="https://www.kaggle.com/netflix-inc/netflix-prize-data">Netflix Prize dataset</a>), which is not enough for a good CB algorithm. Thus, it is necessary another dataset to experiment with CB algorithms and the consequences of combining with the CF algorithms. Both approaches have pros and cons, which combining them seem the right answer. Yu et. al. presents this idea of combining CF and CB algorithms to form a collaborative ensemble obtaining promising results from a text dataset and a image dataset (<a href="https://arxiv.org/ftp/arxiv/papers/1212/1212.2508.pdf">Collaborative Ensemble Learning: Combining Collaborative and Content-Based Information Filtering via Hierarchical Bayes</a>).
</p>

<p align="justify">
    To conclude, the paper explores a really important area of the recommender systems, as most of the models used are ensembled ones. To support the combining systems, the results obtained are that every ensemble outperforms every single CF algorithm.
</p>
