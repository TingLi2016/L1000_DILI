# L1000_DILI
Predict drug-induced liver injury (DILI) based on the transcriptomic profiless from LINCS L1000.

### Data
* The transcriptomic profiles ID used in this study is included in the 6000_transcriptomic_profiles_id.xlsx table. The transcriptomic profiles were extracted from the website (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE92742). Please use the read_gctx_data.ipynb to extract the transcriptomic profiles. 

### Methods
* In the conventional_models, We applied algorithms of k-Nearest Neighbors, Support Vector Machine and Random Forest to predict DILI. For each algorithm, the hyperparameters were optimized. The optimized model (model with the optimized parameters) was used to make predictions.
* In the deep neural network (DNN), we used a fully connected 8 layers of DNN to predict DILI. The hyperparameters of activation function and optimizer were optimized. The optimized model was provided in the file named optimized_model.h5. 

