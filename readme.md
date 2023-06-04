# Insights from the Past Ninety-Nine Volumes of QUESTA

This repository makes available the source code for the work: "Thirty-six years of contributions to queueing systems: a content analysis, topic modeling, and graph-based exploration of research published in the QUESTA journal" (<https://link.springer.com/article/10.1007/s11134-023-09876-w>).

# Prerequisites

To run the codes you will require Python(>=3.8).

# Directory structure
```
├── project
│   ├── data
│   ├── images
│   ├── results
│   ├── src
│   │   ├── data_preprocess.ipynb
│   │   ├── dblp.dtd
│   │   ├── dblp.ipynb
│   │   ├── initial_analysis.ipynb
|   |   ├── plotting.ipynb
|   |   ├── topic_modeling.ipynb
```
- The `data` folder contains QUESTA dataset including abstracts and titles. 
- The `images` folder contains plots generated from the codes in `src` folder.
- The `results` folder contains all results saved (as .csv) after runing the codes in the `src` folder.
- The `src` folder contains all source codes (as Jupyter Notebooks) required to produce the results and images.

# How to run scripts

1. Run the scripts in  `data_preprocess.ipynb` to preprocess data and generate the dataframes stored the `results` folder.
2. Run the script in `dblp.ipynb` for the analysis presented in the `Author Analysis` section of the manuscript.
3. Run the script in `initial_analysis.ipynb` for the initial analysis presented in the `Author analysis` section of the manuscript..
4. Run the script in `plotting.ipynb` to generate the figures in the `Content analysis` and `topic modeling` sections of the manuscript.
4. Run the script in `topic_modeling.ipynb` for the analysis performed in `Topic modeling` section of the manuscript.
