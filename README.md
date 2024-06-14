# VTCNet

In this study, we used the [Kaggle](https://www.kaggle.com/) online platform for code writing, running, and testing. You can import our test code by creating a new file in Kaggle and selecting import.

The code runs with just **one click**.

Introduction to these five files:

VTCNet-baseline: The model without Focus, SPPF, and Separable C3 modules, as a baseline.

VTCNet-noC3: The model with Focus, SPPF module but without Separable C3 module.

VTCNet-noFocus: The model with SPPF and Separable C3 module exclude Focus module.

VTCNet-noSPPF: The model with Focus and Separable C3 module but without SPPF module.

VTCNet: The whole model and complete result.

To ensure a comprehensive evaluation of our VTCNet model, we employed 5-fold cross-validation for all experiments. In this approach, the dataset is divided into five folds: one fold is used as the validation set, and from the remaining four folds, 5% of the data from each fold is combined to form the test set, while the rest constitutes the training set.
