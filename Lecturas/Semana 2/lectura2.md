# Comment: Matrix Factorization Techniques for Recommender Systems

<p align="justify">
  The paper is about matrix factorization which is this idea of adding more characteristics to items and users than the rating. All the examples used are with movies. So, for example, each movie is categorized by a vector towards a serious versus escapist characteristic. Then, each user is categorized the same way based on their movies watched and ratings. Therefore, if these vectors are similar, there is a match between item and user obtaining a high rating prediction.
</p>

<p align="justify">
  Y. Koren et al. uses two main equations. The rating prediction and the regularized squared error. Throughout the paper they start adding factors/variables, such as the bias, in a way that the reader can comprehend where do all does factor come from and their importance in the final equations. This process is accompanied by examples and visual helpers. Although the figures are not the most appealing to the eye (and on figure 4 two lines are with the same color), it does the work, and it simplifies the way of seeing the matrix.
</p>

<p align="justify">
  One of the things that caught my atention is on figure 4, where increasing dimensionality increases accuracy. This makes a los of sense, because it is adding information to the recommender system and with more information it is easier to make predictions. Nevertheless, as one could also deduce, when the dimensionality is already big enough, the accuracy does not increase at the same rate. So, eventually the accuracy would stop increasing or even it might start to decrease as an overfitting effect. Therefore, which could be a balance point where the number of dimensionality is big enough to get a good accuracy, but not big enough to need a significant amount of computing time? It really depends on the problem. First, depending on the items recommending there might not be many characteristics to form the matrix, so using all or most of the characteristics would be better. On the other hand, computing time could not be a problem, as the recommendations could be done offline or, with a decent dimensionality the recommendation is pretty much the same. This dilema is not explored in the paper, as it is not a problem in that context, and it really depends on the scenario.
</p>

<p align="justify">
  The idea of adding bias to the equation is brilliant. As it is explained, calculating the bias is easy and it makes so much sense. It is a really easy way to adjust a user's ratings and get their actual average rating for a specific item. This bias gives a good starting point which could even be an actual prediction.
</p>

<p align="justify">
  Finally, the biggest motivation of this paper and for the authors is the Netflix Prize. As it is said on the paper, at the time of the writing they were first place after winning two times the Progress Prize. For this achievement it is clear that the matrix factorization technique works. Eventually, BellKor in BigChaos joined  Pragmatic Theory to form BellKor's Pragmatic Chaos and win the Netflix Prize. The [solution proposed by BellKor](https://www.netflixprize.com/assets/GrandPrize2009_BPC_BellKor.pdf) is practically the same idea of a matrix factorization with temporal dynamics, but adding a few more things, such as extensions to restricted Boltzmann Machines which involves biases. After that, blending with [the BigChaos solution](https://www.netflixprize.com/assets/GrandPrize2009_BPC_BigChaos.pdf) and [the Pragmatic Theory solution](https://www.netflixprize.com/assets/GrandPrize2009_BPC_PragmaticTheory.pdf) was how they won the Netflix Prize.
</p>
