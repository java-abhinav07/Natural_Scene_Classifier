# Natural_Scene_Classifier

The classifier is trained to be able to classify 6 classes of natural sceanaries.

Dataset
--------
Image Classifier trained on Intel Image Classification challenge dataset from kaggle: https://www.kaggle.com/puneet6060/intel-image-classification/

Dependencies
-------------
* tensorflow 2.x
* numpy 1.18.2
* cv2 4.2.0
* tf.keras 2.1.6
* matplotlib 3.2.0
* sklearn 0.22.2.post1
* IPython

Metrics
--------
The classifier achieves a 91% training accuracy and 76% validation accuracy having trained only on 16 epochs and 9872 iterations. 

Improvements
-------------
* Clearly the validation accuracy is not up to the mark, and overfitting needs to be reduced by including regularization.
* An end to end browser based framework which runs this model and labels image files, ie a visual interface for the same.

