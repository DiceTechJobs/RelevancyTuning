# Solr Jobs Core and Data

Copy the Jobs folder here under the ./server/solr directory of your Solr install and reload the core to access it.
Included is the ./data directory with 2,000 fake jobs, already indexed. This was created using Solr 5 and targets Lucene version 5.0.
If you have Solr 6 with its managed schema, or a version of Solr earlier than 5.0, you will need to re-index. The accompanying Jupyter Notebook in the parent folder contains code for reading and indexing the jobs.csv file that is included so as to re-create this collection if you are unable to load the data directory successfully.
