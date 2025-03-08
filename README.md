# Big Data Analytics and Text Mining Exam Project
## Overview
In this repository there is the implementation of the project made as exam of "Big Data Analytics and Text Mining" carried out as an individual work at the University of Bologna by Riccardo Romeo during AY 2024-25.

The project consists in importing a specific node classification task from [Relbench](https://relbench.stanford.edu/) in a compatible input format in order to test an highgly promising fully-inductive model for node classification called [GraphAny](https://github.com/DeepGraphLearning/GraphAny/tree/main).


## Description
The project is based on the main idea to test GraphAny on a particular type of input graph: a relational graph, built starting from a relational database. 
In particular, we selected a binary node classification task from [Formula 1](https://relbench.stanford.edu/datasets/rel-f1/) database, we embedded it in the form of a pickle file and we give it as input to the model.



## File Structure
├── README.md
├── Relbench_GA_data_import.ipynb
├── BDATM_Projecy_GraphAny.ipynb

## File Description
*  `Relbench_GA_data_import.ipynb`: this Jupiter notebook is used in order to import the node classification task from Relbench in a pickle format;
*  `BDATM_Projecy_GraphAny.ipynb`: in this notebook GraphAny is tested on the imported classification task.

## Projectual Details
The entire project has been run usign Google Colab.

## Authors
  - [Riccardo Romeo](https://github.com/RiccardoRomeo01) 
