# Big Data Analytics and Text Mining Exam Project: testing GraphAny on a Relbench KG
## Overview
In this repository there is the implementation of the project made as exam of "Big Data Analytics and Text Mining" carried out as an individual work at the University of Bologna by Riccardo Romeo during AY 2024-25.

The project consists in importing a specific node classification task from [Relbench](https://relbench.stanford.edu/) in a compatible input format in order to test an highly promising fully-inductive model for node classification called [GraphAny](https://github.com/DeepGraphLearning/GraphAny/tree/main).


## Description
The project is based on the main idea to test GraphAny on a particular type of input graph: a relational graph, built starting from a relational database. 
In particular, we selected a binary node classification task from [Formula 1](https://relbench.stanford.edu/datasets/rel-f1/) database, we embedded it in the form of a pickle file and we give it as input to the model.



## File Structure
```
├── README.md
├── BDATM_Projecy_GraphAny.ipynb
|   Presentation
│   ├── Exam_presentation.pdf
│   └── Exam_presentation.pptx
└── Relbench_GA_data_import.ipynb

```
## File Description
*  `BDATM_Projecy_GraphAny.ipynb`: in this notebook GraphAny is tested on the imported node classification task.
*  `Relbench_GA_data_import.ipynb`: this notebook is used in order to import the node classification task from Relbench in a pickle format;
*  `Exam_presentation.pdf`: the PDF format of the slides used during the exam discussion;
*  `Exam_presentation.pptx`: the Power Point format of the slides used during the exam discussion.

## Projectual Details
The entire project has been implemented on Google Colab.

## Authors
  - [Riccardo Romeo](https://github.com/RiccardoRomeo01) 
