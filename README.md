# DiceTechJobs - Relevancy Tuning
Dice.com tutorial on using black box optimization algorithms to tune your Solr search engine configuration, by Simon Hughes ( Dice Data Scientist ). See _'Automated Relevancy Tuning using Black Box Optimization Algorithms.ipynb'_ for Jupyter Notebook tutorial on using black box optimization algorithms from sci-kit optimize to tune your solr config. Example fake Dice jobs data and a solr core are provided for this example. They are not representative of our real data, nor of our actual Solr search implementation.

## Required software
Solr (Solr core is for 5.0+, for earlier solr versions or later ones, you will need to modify the configs and re-index the data from the notebook).

Python 2.7

Python libraries:
* solrpy
* pandas
* numpy
* scikit-optimize

Slides from my talk: http://www.slideshare.net/SimonHughes13/evolving-the-optimal-relevancy-ranking-model-at-dicecom

Vide of my talk: https://www.youtube.com/watch?v=z4c1xU7arhc&index=24&list=PLU6n9Voqu_1F1Skr8qlaO8_VtF4D8JEhm
