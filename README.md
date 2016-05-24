# QULOSUS, Query Benchmark

QULOSUS is a framework to process pseudo-SPARQL queries over multiple Linked Data datasets.

We created a benchmark of 30 pseudo-SPARQL queries, and ran them over DBpedia, Yago, and LinkedMDB using different settings:

| #Run | TopK | PlugLabel |
|------|------|-----------|
| Run1 | 30   | false     |
| Run2 | 25   | false     |
| Run3 | 20   | false     |
| Run4 | 15   | false     |
| Run5 | 10   | false     |
| Run6 | 5    | false     |
| Run7 | 15   | true      |
| Run8 | 10   | true      |
| Run9 | 5    | true      |

  * index.html - containes a list of pseudo-SPARQL queries along with their correspondent natural language question.
  * The repo also contains 9 folders named Run1 through Run9. Each run folder contains the results of all queries according to the settings of that run. Query results are shown in two formats: html and xml.
  * Each run folder also contains `stats.csv` file that includes different statistics about the performance of each query execution in that respective run.
