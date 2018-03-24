### Which novel do I belong To?

|__Problem__|__Data__|__Methods__|__Libs__|__Link__|
|-|-|-|-|-|
|`NLP`|Text|`Deep Learning - LSTM`, `Word2Vec`|`Sklearn`, `Keras`, `Gensim`, `Pandas`, `Seaborn`|https://github.com/erdiolmezogullari/ml-deep-learning-keras-novel|

This project is related to text classification problem that we tackled with `Deeplearing (LSTM)` model, which classifies given arbitrary paragraphes collected over 12 different novels randomly, above: 

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

In other words, you can think about those novels are our target classes of our dataset.
To distinguish actual class of paragraph, the semantic latent amongst paragraphes would play an important role. Therefore, We used `Deeplearing (LSTM)` on top of `Keras (Tensorflow)` after creating an embedding matrix by `Gensim's word2vec`.

If there is any semantic latent amongst sentences in corresponding paragraph, 
We think about similar paragraphes were collected from same resources (novels) most likely.

