
### 1. Splitting the Dataset into Training, Validation, and Test Sets
  - **Definition**: The process of dividing your dataset into three distinct subsets: training, validation, and test sets.
   - **Why It Matters**: Proper splitting ensures unbiased evaluation and helps prevent overfitting.
   - **Best Practices**:
     - Training Set: Used to train the model and learn hidden features.
     - Validation Set: Used to tune hyperparameters and evaluate model performance during training.
     - Test Set: Used for final evaluation after model training.
- **Documentation & Tutorials:**
    - [Train Test Validation Split: How To & Best Practices](https://www.v7labs.com/blog/train-validation-test-set) provides detailed insights.
     - [A Comprehensive Guide to Train-Test-Validation Split](https://www.analyticsvidhya.com/blog/2023/11/train-test-validation-split/) covers practical aspects.
  - [Scikit-learn: Model Evaluation](https://scikit-learn.org/stable/modules/cross_validation.html)
  - [Machine Learning Mastery: How to Split Data into Training and Testing Sets](https://machinelearningmastery.com/train-test-split-for-evaluating-machine-learning-algorithms/)
- **Git Repositories:**
  - [Dataset Splits: A collection of tools for dataset splitting](https://github.com/jakemdrew/dataset-splits)

### 2. Implementing Traditional ML Classifiers (Random Forests, SVM, XGBoost)
   - **Definition**: These are classic machine learning algorithms that don't rely on deep neural networks.
   - **Examples**:
     - **Random Forests**: Ensemble of decision trees.
     - **Support Vector Machines (SVM)**: Effective for classification and regression.
     - **XGBoost**: Gradient boosting with computational efficiencies.
- **Documentation & Tutorials:**
  - [Scikit-learn: Random Forest](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees)
  - [Scikit-learn: SVM](https://scikit-learn.org/stable/modules/svm.html)
  - [XGBoost: Introduction to XGBoost](https://xgboost.readthedocs.io/en/stable/tutorials/index.html)
   - [How to Develop Random Forest Ensembles With XGBoost](https://machinelearningmastery.com/random-forest-ensembles-with-xgboost/) explains using XGBoost for random forests.
   - [Comparison of Random Forest and XGBoost Classifiers](https://www.mdpi.com/2072-4292/16/4/665) explores their performance.
- **Git Repositories:**
  - [XGBoost: A comprehensive guide](https://github.com/dmlc/xgboost)
  - [SVM Examples in Python using Scikit-learn](https://github.com/entron/entity-recognition-datasets)
- **Research Papers:**
  - [Random Forests](https://link.springer.com/article/10.1023/A:1010933404324)
  - [Support Vector Machines](https://www.jmlr.org/papers/volume2/boser92a/boser92a.pdf)
  - [XGBoost: A Scalable Tree Boosting System](https://arxiv.org/abs/1603.02754)

### 3. Developing CNN Architectures (e.g., U-Net, Mask R-CNN) for Semantic Segmentation
 - **Definition**: Convolutional Neural Networks (CNNs) designed for pixel-wise segmentation tasks.
- **Examples**:
     - **U-Net**: Widely used for biomedical image segmentation.
     - **Mask R-CNN**: Combines object detection and instance segmentation.

- **Documentation & Tutorials:**
  - [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
  - [Mask R-CNN](https://arxiv.org/abs/1703.06870)
  - [Keras: Building a U-Net Model](https://github.com/zhixuhao/unet)
  - [Everything about Mask R-CNN: A Beginner’s Guide](https://viso.ai/deep-learning/mask-r-cnn/) provides an overview.
     - [Mask R-CNN Outperforms U-Net in Instance Segmentation for Overlapping Cells](https://www.degruyter.com/document/doi/10.1515/cdbme-2023-1084/html) discusses performance.
- **Git Repositories:**
  - [U-Net in Keras](https://github.com/zhixuhao/unet)
  - [Mask R-CNN Implementation](https://github.com/matterport/Mask_RCNN)
- **Research Papers:**
  - [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
  - [Mask R-CNN](https://arxiv.org/abs/1703.06870)

### 4. Training Models using Transfer Learning from Pre-trained Networks (e.g., ResNet, VGG)
- **Definition**: Leveraging knowledge from pre-trained models (e.g., on ImageNet) for specific tasks.
- **Examples**:
     - **ResNet**: Popular deep architecture.
     - **VGG**: Well-known for image classification.
- **Documentation & Tutorials:**
  - [Keras Applications: Using Pre-trained Models](https://keras.io/api/applications/)
  - [PyTorch: Transfer Learning for Computer Vision Tutorial](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html)
  - [Train-Test Split - Machine Learning Plus](https://www.machinelearningplus.com/machine-learning/train-test-split/) explains the concept.
- **Git Repositories:**
  - [Transfer Learning with PyTorch](https://github.com/pytorch/examples/tree/main/transfer_learning)
  - [Keras Transfer Learning](https://github.com/keras-team/keras/blob/master/examples/transfer_learning.py)
- **Research Papers:**
  - [Deep Residual Learning for Image Recognition (ResNet)](https://arxiv.org/abs/1512.03385)
  - [Very Deep Convolutional Networks for Large-Scale Image Recognition (VGG)](https://arxiv.org/abs/1409.1556)

### 5. Implementing Ensemble Methods Combining Multiple Model Outputs
 - **Definition**: Combining multiple model outputs for improved performance.
- **Examples**:
     - **Bagging**: Bootstrap aggregating (e.g., Random Forests).
     - **Boosting**: Iteratively improving weak models (e.g., XGBoost).
- **Documentation & Tutorials:**
  - [Ensemble Learning Methods in Scikit-learn](https://scikit-learn.org/stable/modules/ensemble.html)
  - [Machine Learning Mastery: Ensemble Learning Algorithms With Python](https://machinelearningmastery.com/ensemble-methods-for-machine-learning/)
  - [Random Forests in XGBoost](https://xgboost.readthedocs.io/en/stable/tutorials/rf.html) demonstrates using XGBoost for random forests.
- **Git Repositories:**
  - [Ensemble Methods in Python](https://github.com/dmlc/xgboost/tree/master/demo/guide-python/sklearn_examples)
- **Research Papers:**
  - [Ensemble Methods: Foundations and Algorithms](https://www.morganclaypool.com/doi/abs/10.2200/S00171ED1V01Y200912AIM006)


---

Source: Conversation with Copilot, 19/7/2024
(1) Train Test Validation Split: How To & Best Practices [2024]. https://www.v7labs.com/blog/train-validation-test-set.
(2) A Comprehensive Guide to Train-Test-Validation Split in 2024. https://www.analyticsvidhya.com/blog/2023/11/train-test-validation-split/.
(3) How to Develop Random Forest Ensembles With XGBoost. https://machinelearningmastery.com/random-forest-ensembles-with-xgboost/.
(4) Everything about Mask R-CNN: A Beginner’s Guide - Viso. https://viso.ai/deep-learning/mask-r-cnn/.
(5) What is Mask R-CNN? The Ultimate Guide.. https://blog.roboflow.com/mask-rcnn/.
(6) machine-learning-research · GitHub Topics · GitHub. https://github.com/topics/machine-learning-research.
(7) machine-learning-resources · GitHub Topics · GitHub. https://github.com/topics/machine-learning-resources.
(8) 10 GitHub Repositories to Master Machine Learning. https://aiquantumintelligence.com/10-github-repositories-to-master-machine-learning/.
(9) Mask R-CNN - Everything explained — Picsellia. https://www.picsellia.com/post/mask-r-cnn-everything-explained.
(10) Mask R-CNN Outperforms U-Net in Instance Segmentation for Overlapping Cells. https://www.degruyter.com/document/doi/10.1515/cdbme-2023-1084/html.
(11) Mask R-CNN | ML - GeeksforGeeks. https://www.geeksforgeeks.org/mask-r-cnn-ml/.
(12) Comparison of Random Forest and XGBoost Classifiers Using ... - MDPI. https://www.mdpi.com/2072-4292/16/4/665.
(13) Forest Image Classification Based on Deep Learning and XGBoost .... https://link.springer.com/chapter/10.1007/978-3-031-36027-5_16.
(14) Random Forests(TM) in XGBoost — xgboost 2.1.0 documentation. https://xgboost.readthedocs.io/en/stable/tutorials/rf.html.
(15) Train,Test, and Validation Sets - MLU-Explain. https://mlu-explain.github.io/train-test-validation/.
(16) machine learning - Is there a rule-of-thumb for how to divide a dataset .... https://stackoverflow.com/questions/13610074/is-there-a-rule-of-thumb-for-how-to-divide-a-dataset-into-training-and-validatio.
(17) Train Test Split - Machine Learning Plus. https://www.machinelearningplus.com/machine-learning/train-test-split/.
(18) What Is Machine Learning? Definition, Types, and Examples. https://www.coursera.org/articles/what-is-machine-learning.
(19) What is a machine learning model? | Microsoft Learn. https://learn.microsoft.com/en-us/windows/ai/windows-ml/what-is-a-machine-learning-model.
(20) What is Machine Learning? | Google for Developers. https://developers.google.com/machine-learning/intro-to-ml/what-is-ml.
(21) Machine Learning Models: What They Are and How to Build Them. https://www.coursera.org/articles/machine-learning-models.