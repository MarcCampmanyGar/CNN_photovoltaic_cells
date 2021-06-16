# Creation of a Convolutional Neural Network to classify images of photovoltaic cells obtained via electroluminiscence.
Final project of my Master on Organizational Engineering at UPC Barcelona

- The dataset (https://github.com/zae-bayern/elpv-dataset) contains 2,624 samples of 300x300 pixels 8-bit grayscale images of functional and defective solar cells with varying degree of degradations extracted from 44 different solar modules. The defects in the annotated images are either of intrinsic or extrinsic type and are known to reduce the power efficiency of solar modules.
All images are normalized with respect to size and perspective. Additionally, any distortion induced by the camera lens used to capture the EL images was eliminated prior to solar cell extraction.

On this project the main tasks performed have been:
- Exploratory analysis of the dataset
- Creation of train/test files
- Benchmark models of mono+poly datasets
- Benchmark models of mono and poly models separated
- Techniques used to improve models:
  - Data Augmentation
  - Weight balancing
  - L2 regularization
  - Transfer Learning with VGG16
  - Early stopping with validation_AUC
  - Oversampling for mono dataset
  - K-folds to evaluate best models
