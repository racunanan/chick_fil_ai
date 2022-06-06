# Chick-fil-AI
This project applies basic ANN to detect presence of Coccidiosis in chickens using images of chicken droppings.

## Prerequisites
1. Latest version of Anaconda
2. Latest version of Jupyter Notebook (should come with Anaconda)

## Dataset
Data used was obtained from this [link](https://zenodo.org/record/4628934#.YoD156dBzIU).
The site contains several images of droppings from healthy chickens and chickens infected with Coccidiosis, Salmonella, and Newcastle Disease.
Only a subset of the images were used. Specifically, 500 images of healthy droppings and 500 images of Coccidiosis droppings were used.

## Confusion Matrix
For the following images:
* 0 -> Coccidiosis
* 1 -> Healthy
1. Training Accuracy and Confusion Matrix
---
![training_acc](https://user-images.githubusercontent.com/57553041/172099563-65578400-1076-41ad-88ee-dfed4326e2ae.jpg)

2. Test Accuracy, F1 Score, and Confusion Matrix
---
![test_acc](https://user-images.githubusercontent.com/57553041/172099684-3a2df74c-b712-4264-b536-87f43ff23ec1.jpg)
