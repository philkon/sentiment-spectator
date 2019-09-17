# Text Sentiment in the Age of Enlightenment
This repository contains the code for the analysis conducted in the paper *Text Sentiment in the Age of Enlightenment*

# The Data
We work with TEI encoded XML Files available at https://gams.uni-graz.at/mws.
All XML files need to be placed in the same dictionary.
Further you have to correctly set paths to files in the respective Jupyter Notebooks.

# The Code
Code is available as Jupyter Notebooks. Execute the notebooks in the following order:

## 01_extract_data.ipynb
Used to extract texts and additional meta data from the XML files. You have to configure two paths:
1. data_dir: Pointing to the dictionary containing the XML files.
2. results_dir: Pointing to the dictionary where results should be stored.

## 02_conduct_analysis.ipynb
Used to conduct the analysis. Make sure you set the *dataframe_input_path* to the correct dictionary and file.
