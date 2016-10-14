# RelevancyTuning
Dice.com tutorial on using black box optimization algorithms to tune your Solr search engine configuration.
See _'Automated Relevancy Tuning using Black Box Optimization Algorithms.ipynb'_ for Jupyter Notebook tutorial on using black box optimization algorithms from sci-kit optimize to tune your solr config. Example fake Dice jobs data and a solr core are provided for this example. They are not representative of our real data, nor of our actual Solr search implementation.

## Required software
Solr (Solr core is for 5.0+, for earlier solr versions or later ones, you will need to modify the configs and re-index the data from the notebook).


Python 2.7

Python libraries:
* solrpy
* pandas
* numpy
* scikit-optimize

Slides from my talk: http://www.slideshare.net/SimonHughes13/evolving-the-optimal-relevancy-ranking-model-at-dicecom

The slides and video of the talk will be made available online in a couple of months by LucidWorks.
