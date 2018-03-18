### Which novel do I belong To?

|__Problem__|__Data__|__Methods__|__Libs__|__Link__|
|-|-|-|-|-|
|`NLP`|Text|`Deep Learning - LSTM`, `Word2Vec`|`Sklearn`, `Keras`, `Gensim`, `Pandas`, `Seaborn`|https://github.com/erdiolmezogullari/ml-deep-learning-keras-novel|

This project is related to text classification problem that we tackled with NLP and sufficient machine learning approaches. Dataset consists of different arbitrary passages which were collected over the different popular novels, below. We need to build a machine learning model that classifies those given arbitrary contexts as belonging to out of the following 12 novels:

    0. alice_in_wonderland
    1. dracula
    2. dubliners
    3. great_expectations
    4. hard_times
    5. huckleberry_finn
    6. les_miserable
    7. moby_dick
    8. oliver_twist
    9. peter_pan
    10. talw_of_two_cities
    11. tom_sawyer

In other words, those novels are our target variables as we listed above. To handle that problem, We need to focus on the semantical meaning of sentences amongst passages. If there is any semantical flow amongst sentences in corresponding passage, We think about similar passage were collected over same novels mostlikely. Therefore, `Deeplearing (LSTM)` is the most suitable apporach with `word2vec`.

`Deeplearing (LSTM)` were used on top of `Keras (Tensorflow)` after creating embedding matrix by `Gensim's word2vec`.
