# ENP_MODELS
MIKE models of Everglades National Park

M01_M3ENP - the smaller-domain MIKE model of ENP, including our water quality models
M04_WQ_TEMPLATE - Simple model used to test the chemistry for the water quality models
M06_M3ENP_SF - the larger-domain (South Florida) MIKE model of ENP

M3ENP stands for the MIKE Marsh Model of Everglades National Park
The models are given a number (M01, M04, M06) as well as a name (M3ENP, WQ_TEMPLATE, M3ENP_SF), which facilitates in filename conventions. The models could be referred to by their name or number.

The models are set up so the user runs them by opening the MIKE Zero project file (.mzp) in the top-level directories. Opening this file will allow the user to access all the models in the sub-directories and also set up a common location for Results to be stored.

The ENP_MODELS repo is mostly self-contained, but some models do need a few files to run that are not contained in this repository. These files are contained in the directory ENP_FILES, which can be obtained from Kiren. The user is responsible for keeping the files in this directory up-to-date.

