# Covid X-Ray Image Classification
Classify X-ray images into three classes: Covid, Normal, and Viral Pneumonia using CNN model based on VGG-16 model. Given 3,616 COVID-19 positive cases along with 10,192 Normal, and 1345 Viral Pneumonia images, only 1,345 cases were sampled to balance target distribution.

# Objective
This project is to learn applying deep learning using a CNN model to multiclass classification.

# Summary
![Model Loss](/images/model_loss.png = 450x300)
![Model Accuracy](/images/model_acc.png = 450x300)
![Classification Report](/images/covid-report.png)
- The model got train accuracy and test accuracy at 95% and 90%, in turn. The model was still far from human level performance or Bayes Error. It can be improved by training with more data or improving the neuron network.
![Confusion Matrix](/images/covid-cm.png)
- The confusion matrix showed that the model classified well on Viral Pneumonia cases. Meanwhile, many normal cases were mistaken to COVID cases or vice versa.

# Licenses / Acknowledgements / References
Data Resource: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database/code
References:
1) ![CNN - How to use 160,000 images without crashing](https://www.kaggle.com/vbookshelf/cnn-how-to-use-160-000-images-without-crashing)
2) ![Medical X-ray ⚕️ Image Classification using Convolutional Neural Network](https://towardsdatascience.com/medical-x-ray-%EF%B8%8F-image-classification-using-convolutional-neural-network-9a6d33b1c2a)
