# Where imaging mass spectrometry stands: here are the numbers
This repository accompanies the manuscript: [Andrew Palmer, Dennis Trede, Theodore Alexandrov (2016) Where imaging mass spectrometry stands: here are the numbers, *Metabolomics*, 12(6), 1-3](http://dx.doi.org/10.1007/s11306-016-1047-0). It contains all the data collected in the survey in the end of 2015 and analysis scripts required to reproduce the figures in the paper.

## Introduction
Imaging Mass Spectrometry (imaging MS) is a technology for spatial analytics increasingly attracting attention in particular in metabolomics. Imaging MS has diverse applications, platforms, and used imaging of molecules from different classes. But there is little quantified information when answering such questions about the imaging MS field and community as: Is it used mainly for proteins or metabolites? What is the widespread of MALDI as compared to other types of ionisation sources? How much data is generated worldwide?

To seek for quantified answers to these and other questions, we organized an online survey in the end of 2015 and recruited imaging MS practitioners to tell about themselves, their applications, imaging MS technologies they use and what their throughput is.

WE THANK EVERYONE WHO COMPLETED THE SURVEY and in return provide complete data collected in the survey (anonymized), our analytics results and summary figures, and scripts used for analytics.

## Summary Figure
![Summary Figure](https://github.com/SpatialMetabolomics/metaspace-survey/blob/master/summary_figure.png)

NB: Please note that in the figure published in the [paper](http://dx.doi.org/10.1007/s11306-016-1047-0) there is a typo, saying "DATASETS PER DAY" whereas it should be "DATASETS PER WEEK".

### Citation
Please cite this work as:
Palmer, A., Trede, D., & Alexandrov, T. (2016). Where imaging mass spectrometry stands: here are the numbers. Metabolomics, 12(6), 1-3.
DOI: 10.1007/s11306-016-1047-0

## Reproducing the Results
One can reproduce the results in either of the following ways:

### Quick Preview in Web Browser
The  [metaspace_survey.ipynb](https://github.com/SpatialMetabolomics/metaspace-survey/blob/master/metaspace_survey.ipynb) digital notebook contains all the survey analysis and can be viewed directly in most modern web-browsers. All figures contained in the paper are shown here alongside the scripts used to generate them (although the colourscheme may vary).

### On Own Computer
1. Install the jypyter/ipython environment from here: http://jupyter.readthedocs.org/en/latest/install.html
2. Download and unzip all the files from this [repository](https://github.com/SpatialMetabolomics/metaspace-survey/archive/master.zip)
3. Open and run `metaspace_survey.ipynb` in the jupyter notebook environment

## Original Data
The full (anonymised) survey data can be downloaded from [here](https://github.com/SpatialMetabolomics/metaspace-survey/tree/master/data). It contains two files:

1. survey_final_all.csv: a raw dump of the results in CSV format
2. survey_final_all_otherMoved.csv: The same results as `survey_final_all.csv` with entries in free-text 'other' fields that had two or more responses transfered to their own columns.

## Funding

This project is funded from the [European Horizon2020](https://ec.europa.eu/programmes/horizon2020/)
project [METASPACE](http://project.metaspace2020.eu/) (no. 634402),
[NIH NIDDK project KPMP](http://kpmp.org/)
and internal funds of the [European Molecular Biology Laboratory](https://www.embl.org/).

## License
The source code, figures, and anonymized data files are licensed under the [Apache 2.0 license](LICENSE).