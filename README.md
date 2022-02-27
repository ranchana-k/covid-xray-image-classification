# Covid X-Ray Image Classification
Classify X-ray images into three classes: Covid, Normal, and Viral Pneumonia using CNN model based on VGG-16 model. Given 3,616 COVID-19 positive cases along with 10,192 Normal, and 1345 Viral Pneumonia images, only 1,345 cases were sampled to balance target distribution.

# Objective
This project is to learn applying deep learning using a CNN model to multiclass classification.

# Summary
- Train and validation loss decreased during training. For the highest validation accuracy of 92.69%, train accuracy was and 92.10% The model still has high bias and can be improved by training with more data, training longer, or improving the neuron network.

<img src="/images/model_loss.png" width="400" height="300">  <img src="images/model_acc.png" width="400" height="300">
- From the classification report, `Covid` and `Normal` cases has almost the same f1-score at about 90%. Meanwhile, `Viral Pneumonia` case has f1-score at 97%
<img src="/images/covid-report.png" width="500">                                   
- The confusion matrix showed that the model classified well on Viral Pneumonia cases in accordance with classification report. There were still many normal cases were mistaken to COVID cases or vice versa.
<img src="/images/covid-cm.png" width="500">

# Licenses / Acknowledgements / References
Data Resource: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database/code
References:
1) ![CNN - How to use 160,000 images without crashing](https://www.kaggle.com/vbookshelf/cnn-how-to-use-160-000-images-without-crashing)
2) ![Medical X-ray ⚕️ Image Classification using Convolutional Neural Network](https://towardsdatascience.com/medical-x-ray-%EF%B8%8F-image-classification-using-convolutional-neural-network-9a6d33b1c2a)
