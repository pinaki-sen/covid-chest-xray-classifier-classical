# covid-chest-xray-classifier-classical
---
# Problem statement - 
### Detecting Covid19 or Viral Pneumonia using Chest x-ray

---
# Dataset used - 
I have used this [datset](https://www.kaggle.com/pranavraikokte/covid19-image-dataset) from Kaggle which contains 250 training and 65 testing images for our model.

![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-1.png?raw=true)

---
# Plotting accuracy, cost, adaptive learning rate - 
## Accuracy
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/accuracy.png?raw=true)

## Training and Validation Loss
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/loss.png?raw=true)

## Adaptive Learning Rate
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/learning-rate.png?raw=true)

---
# Predicting on individual images - 
This model has 87.5% validation accuracy as tested on the given test images. Although there is still some room for improvement using larger dataset for both training and testing. 

## Correct Predictions 
#### Label: Covid , Predicted: Covid
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-1.png?raw=true)

---
#### Label: Covid , Predicted: Covid
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-3.png?raw=true)

---
#### Label: Normal , Predicted: Normal
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-4.png?raw=true)

---
#### Label: Normal , Predicted: Normal
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-5.png?raw=true)

---
#### Label: Viral Pneumonia , Predicted: Viral Pneumonia
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-6.png?raw=true)

---
#### Label: Viral Pneumonia , Predicted: Viral Pneumonia
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-7.png?raw=true)

---
## Wrong Predictions
#### Label: Covid , Predicted: Normal
![alt text](https://github.com/senpinaki222/covid-chest-xray-classifier-classical/blob/main/images/test-2.png?raw=true)

---
# Disclaimer - 

### 87.5% accuracy is something really huge to claim and we can't do that exactly here. One of the reasons is that the dataset is not enough large to be trained on for a industry level deep neural network architecture.

### So there is a scope of future improvement by training on more data
