The present repository includes all data and code utilized for the paper "Distinct connectivity patterns between perception and attention-related brain networks characterize dyslexia: machine learning applied to resting-state fMRI". The manuscript is to be published in the journal "Cortex". A DOI identification number for this paper is to be created and added 
to this repository soon.
This repository includes A) two .py files, B) one .sav file and C) a set of .txt files.

A) Python scripts (.py): Both .py files were designed to run using the Google Colaboratory online Python environment:

  I.- The file nilearn_plot_connectome.py is a script that plots the Power atlas (a brain atlas comprising 264 brain nodes). 
  Each node of this atlas is drawn in blue color except the nodes comprising the DAN, that are printed in red. A set of edges are printed as well. Specifically,
  the edges that most significantly differentiate between children with and without dyslexia between the DAN and the rest of the brain.
 
  II.- The file Dyslexia_Detection.py is a Machine Learning model that runs a classification between children with and without dyslexia. Further details of this model are 
  presented in the paper "Distinct connectivity patterns between perception and attention-related brain networks characterize dyslexia: machine learning applied to resting-state fMRI",
  that is to be published in the journal cortex. A DOI identification number for this paper is to be created soon.

B) Behavioral data (.sav): This file includes the anonymized demographic and cognitive data utilized in the statistical analysis reported in the paper.

C) The preprocessed neuroimaging data utilized for the creation of the ML models comprises the .txt files:

   I.- Txt files ending with 2 are between_network connectivity matrices (they are larger and have been compressed to two zip files).
   II.- Txt files with no number are within_network connectivity matrices (smaller and not compressed).
