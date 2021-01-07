# Exoplanet_Hunting
Finding exoplanets in space using ML.

The model was trained on data(which are basially flux values of starlight w.r.t time about which an exoplanet revolves) collected using the Transit method, which detects the drop in intensity of starlight when the exoplanet(if hosted) blocks the light reaching the telescope.

Plotted gaussian histogram of the data - Scaled and Normalized the data for ease of training - performed PCA to retain variance upto 98.8% (with 15 columns/features out of 3190 columns) - used SMOTE for resmapling the data accounting for highly imbalanced data, creating synthetic samples of the minority class label - fitting of the model using SVM(SV Classifier) and Random Forest algorithms -  performed cross-validation, generated accuracy measure, classification & confusion matrices (around 98% accurate prediction results).

