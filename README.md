# NeuronImageSegmentation

Full data and model exploration notebook for segmentation of microscope images of neurons of different types. Created for the [Sartorius - Cell Instance Segmentation competition](https://www.kaggle.com/c/sartorius-cell-instance-segmentation) hosted by [Kaggle](https://kaggle.com).

The original notebook (with full notebook preview, version history, and connection to the relevant data sources) is availabile [on Kaggle Notebooks](https://www.kaggle.com/ppjanka/2021-sartorius-neuronsegmentation).

**Contents:**
 - (image) data cleaning,
 - initial dataset exploration to identify biases,
 - image data augmentation,
 - image classification (vanilla CNN),
 - image segmentation (CNN-based detection + clustering with DBSCAN),
 - quasi-physical pre-processing for clustering (particle simulator that evolves pixel positions),
 - ensemble methods: stacking.
