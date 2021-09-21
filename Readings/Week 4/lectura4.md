# Comment: Content-Based Recommendation Systems

<p align="justify">
  The paper is about content-based recommendation systems, mainly on text as a content. These systems recommend an item to a user based upon a description of the item and a profile of the user’s interests. Pazzani and Billsus describe different algorithms with examples. First of all, it is important the item and user clasiffication or representation. For the item representation are used things such as tf*idf, which calculates the frequency of words, and basic item characteristics like genres on movies. On the other hand, the user's representation is based on the items they interact with. With this information it is possible to start using algorithms such as decision trees, KNN, linear classifiers, among others presented.
</p>

<p align="justify">
  One of the problems presented is the recollection of information through tf*idf (or other word frequency method), where the results might not be the ones expected. For example, polysemous (the same word, but with different meaning) and synonyms (different words, but with the same meaning). When retrieving information from the text the idea is to group together all the words by their meaning. To automatize this is really hard and it is a problem from the natural language processing area. Other thing to consider is the elimination of words that have no meaning. That is, connectors or words such as "the". Furthermore, words with the same root must be grouped together. It is presented the concept of stemming. The idea is to group together all the words that have the same meaning as coming from the same family, for example: play, playing and played.
</p>

<p align="justify">
  Along with the last problem, it is really important to have a good item representations. That is, it might be hard to obtain information, but these information regarding item characteristics is the most crucial thing for the content-based algorithms. With the item cahracteristics not only are the items grouped together, but also the users, as they are classified according to the items. User modeling can be obtained through explicit and implicit feedback (although almost always explicit feedback gives more information), therefore to get the user information is mainly an item characteristic problem.
</p>

<p align="justify">
  To conclude, the most important part of the content-based recommendation systems it the item characterization. Retrieving information and classifying the item (i.e. as a vector). Additionally, these recommendation systems work well with high content problems. Therefore, specially for those problems it is better to complement with other recommendation systems, such as collaborative filtering or matrix factorization techniques.
</p>
