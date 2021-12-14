# NOX_emmision
#### Regression 

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)

**Introduction**: Its not hidden how Industries are producing Polutants like sox, nox, co2, co etc. One of the example is gas turbine, and the aim was to predict the quantity of Nitrogen oxides (NOx) mg/m3 emmision from gas turbine few features were given in the data set which was taken from an industry for research purpose,features are:
* Ambient temperature (AT) C 
* Ambient pressure (AP) mbar 
* Ambient humidity (AH) (%) 
* Air filter difference pressure (AFDP) mbar 
* Gas turbine exhaust pressure (GTEP) mbar
* Turbine inlet temperature (TIT) C 
* Turbine after temperature (TAT) C
* Compressor discharge pressure (CDP) mbar 
* Turbine energy yield (TEY) MWH 
* Carbon monoxide (CO) mg/m3 

Used four models to predict NOX emmision to compare better model, it was regression problem, used multiple methods in order to achieve better accuracy, with Feature engineering and feature selection.

**Technologies**: A few libraries and techs used in project
1. Jupyter notebook
2. Python 3.6
3. Pandas
4. Tensorflow 2.3.1
5. Matplot

**Feature Selection**: To choose best features correlation matrix was used and similar feature with more than 90% correlation was removed.

**conclusion**: In all model ANN performed with highest accuracy on 20% test dataset followed by random forest.
