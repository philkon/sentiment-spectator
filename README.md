## Text Sentiment in the Age of Enlightenment
This repository contains the code for the analysis conducted in the paper *Text Sentiment in the Age of Enlightenment*

## The Data
### Spectator Journals
We work with TEI encoded XML Files available at: https://gams.uni-graz.at/mws.
All XML files need to be placed in the same dictionary.
Further you have to correctly set paths to files in the respective Jupyter Notebooks.
### Sentiment Dictionaries
The used dictionaries are available at: https://sites.google.com/site/datascienceslab/projects/multilingualsentiment.
These dictionaries were created and analyzed by Chen and Skiena [1].

## The Code
Code is available as Jupyter Notebooks. Execute the notebooks in the following order:

### 01_extract_data.ipynb
Used to extract texts and additional meta data from the XML files. You have to configure two paths:
1. data_dir: Pointing to the directory containing the XML files.
2. results_dir: Pointing to the directory where results should be stored.

### 02_conduct_analysis.ipynb
Used to conduct the analysis. Make sure that you set the *dataframe_input_path* to the pickled dataframe file from the extraction and to point *sentiment_dir* to the directory containing the downloaded sentiment dictionaries.

## Supplementary Material
You can find the top 100 central words according to degree, betweenness and closeness centrality for German, French, Italian and Spanish networks in the *topwords* directory.

## References
[1] Chen, Y., Skiena, S.: Building sentiment lexicons for all major languages. In: Proceedings of the 52nd Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers). pp. 383–389 (2014)
