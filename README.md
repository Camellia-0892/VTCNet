# VTCNet: A feature fusion DL model based on CNN and ViT for the classification of cervical cells
## Abstract
Cervical cancer is a common malignancy worldwide, with high incidence and mortality rates in underdeveloped countries. The Pap smear test, widely used for early detection of cervical cancer, aims to minimize missed diagnoses, which sometimes results in higher false-positive rates. To enhance manual screening practices, computer-aided diagnosis (CAD) systems based on machine learning (ML) and deep learning (DL) for classifying cervical Pap cells have been extensively researched. In our study, we introduced a deep learning-based method named VTCNet for the task of cervical cell classification. Our approach combines CNN-SPPF and ViT components, integrating modules like Focus and SeparableC3, to capture more potential information, extract local and global features, and merge them to enhance classification performance. We evaluated our method on the public SIPaKMeD dataset, achieving accuracies, precision, recall, and F1 scores of 97.16%, 97.22%, 97.19%, and 97.18%, respectively. We also conducted additional experiments on the Herlev dataset, where our results outperformed previous methods. The VTCNet method achieved higher classification accuracy than traditional ML or shallow DL models through this integration.

## File Description
In this study, we used the [Kaggle](https://www.kaggle.com/) online platform for code writing, running, and testing. You can import our test code by creating a new file in Kaggle and selecting import.

The code runs with just **one click**.

Introduction to these five files:

VTCNet-baseline: The model without Focus, SPPF, and Separable C3 modules, as a baseline.

VTCNet-noC3: The model with Focus, SPPF module but without Separable C3 module.

VTCNet-noFocus: The model with SPPF and Separable C3 module exclude Focus module.

VTCNet-noSPPF: The model with Focus and Separable C3 module but without SPPF module.

VTCNet: The whole model and complete result.

To ensure a comprehensive evaluation of our VTCNet model, we employed 5-fold cross-validation for all experiments. In this approach, the dataset is divided into five folds: one fold is used as the validation set, and from the remaining four folds, 5% of the data from each fold is combined to form the test set, while the rest constitutes the training set.
