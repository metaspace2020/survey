# METASPACE #
This repository accompanies the manuscript: "Where imaging mass spectrometry stands: here are the numbers" Andrew Palmer, Dennis Trede, Theodore Alexandrov. It contains all the data and analysis required to reproduce the figures in the paper.

# Quick View #
The  [metaspace_survey.ipynb](https://github.com/SpatialMetabolomics/metaspace-survey/blob/master/metaspace_survey.ipynb) digital noteook contains all the survey analysis and can be viewed directly in most modern web-browsers. All figures contained in the paper are shown here (although the colourscheme may vary).

# Reproducing the results  #
## Get the Data ##

The anonymised survey data can be downloaded from [here](https://github.com/SpatialMetabolomics/metaspace-survey/tree/master/data). It contains two files:

1. survey_final_all.csv: a raw dump of the results in csv format
2. survey_final_all_otherMoved.csv: The same results as `survey_final_all.csv` with entries in free-text 'other' fields that had two or more responses transfered to their own columns.

## Making the figures ##

1. Install the jypyter/ipython environment from here: http://jupyter.readthedocs.org/en/latest/install.html
2. Download and unzip all the files from this [repository](https://github.com/SpatialMetabolomics/metaspace-survey/archive/master.zip)
3. Open and run `metaspace_survey.ipynb` in the jupyter notebook environment 
