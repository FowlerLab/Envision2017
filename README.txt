Our code is separated into five Jupyter Notebook files (.ipynb) and one
R Markown file.


The Jupyter Notebooks contain the following:
------------------------------------------------------------------------
+ singleProteinModels.ipynb -- code for tuning hyperparameters and
training models using the 8 protein data sets individually.

+ envisionTuneTrainPredict.ipynb -- code to tune hyperparameters and
train Envision with all eight data sets

+ LOPOTuneTrain.ipynb -- train each leave-one-protein-out
(LOPO) model to predict the protein data set not used in training.

+ LOPO_10xCV.ipynb -- tune using tenfold cross-validation, train each leave-one-protein-out
(LOPO) model to predict the protein data set not used in training.

+ LOPO_predict_missingFeatureMuts.ipynb -- use each leave-one-protein-out
(LOPO) model to predict the protein data set not used in training with missing features. 

+ LOPO_unnormalized.ipynb -- train each leave-one-protein-out
(LOPO) model with unnormalized data and then predict protein data sets not used in training.

+ downSamplingAnalysis.ipynb -- code to sample 6, 4,and 2 proteins
as training data for model training

+ Clinvar_analysis.ipynb -- use Envision to predict Clinvar mutations
_______________________________________________________________________



The R Markdown contains the following:
---------------------------------------------------------------------

+ envision_figure_code.Rmd -- code for generating manuscript figures. 
---------------------------------------------------------------------

Notes:
 - All necessary data files can be found in /data directory.

 - Graphlab and Python dependencies (e.g. Numpy) are required to
 successfully run all .ipynb code. 

 - All code will be deposited in a public GitHub repository upon publication
 