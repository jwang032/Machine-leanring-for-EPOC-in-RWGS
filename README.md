# Machine-leanring-for-EPOC-in-RWGS

This GitHub repository is used as supplementary materials for the JCIM paper titled 'Machine Learning-Driven Prediction of Electrochemical Promotion in the Reverse Water Gas Shift Reaction'. It contains the machine learning codes in Jupyter Notebook and datasets used for training, testing, and validating.

The 'data processing' shows how the raw data is filtered, processed, and structured.

The 'Classification' shows how different classification models are applied for training/testing.

The'RFR', 'XGBR', 'SVR', 'NN', and 'Ridge+Lasso' show how different regression models are applied for training/testing.

The 'model comparison' shows the residual density plot and residual plot that used for regression model comparison.

The 'RValidation' shows how the trained regression models are applied to validation dataset for regression validation.

The 'C+R Validation' shows how the combined classification + regression models are applied to validation dataset.

The 'EPOC dataset' contains all EPOC-related data extracted from all previously-published EPOC studies on RWGS and CO2 hydrogenation.

The 'Validate dataset' contains the data collected from experimental results using new materials: LLTO solid electrolyte and Pt-ZnO catalyst.

The 'Integrated Validation' shows retrained models using an integrated dataset, where the 'EPOC dataset' and 'Validate dataset' are combined. This approach aims at evaluating potential improvements in predictive performance for future use. 
