# L1000_DILI
Use transcriptomics from LINCS L1000 to predict drug-induced liver injury (DILI).

### Data
* The transcriptomic profiles ID is included in the 6000_transcriptomic_profiles_id.xlsx table. Please use the read_gctx_data.ipynb to extract the transcriptomic profiles. 

### Methods
* In the conventional_models, We use three KNN, SVM and RF to predict DILI.
* In the DNN, we use a fully connected deep neural network to predict DILI. For the optimized model, we provided in the file of optimized_model.h5.

