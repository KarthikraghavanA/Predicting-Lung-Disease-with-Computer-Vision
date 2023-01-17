# *Computer Vision - Predicting Lung Disease with Computer Vision*

In this project we will predict whether the patient has pneumonia or not

Dataset Link --> https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

![image](https://user-images.githubusercontent.com/112689649/212810094-9434ab60-b16a-43ca-9a99-93c5501cab9a.png)

# *Content*

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.


We used **VGG16** for the model and we did not train the parameters from VGG16
We only trained the Dense layer

![image](https://user-images.githubusercontent.com/112689649/212810224-4f392124-0a71-428f-bf1e-9b6614e0832e.png)
![image](https://user-images.githubusercontent.com/112689649/212810259-3b50b4ad-03c5-4f95-bd28-4eb76eaa07c6.png)

We ran for 5 epochs and the result was okay with final loss and accuracy as below image

![image](https://user-images.githubusercontent.com/112689649/212813508-ea51b84b-6fe8-40f2-85a5-ba48690f36d3.png)


![image](https://user-images.githubusercontent.com/112689649/212813541-0ad1e142-b696-4398-b9c6-e6b7b2addea8.png)


## Loading the model for prediction

![image](https://user-images.githubusercontent.com/112689649/212815420-7f5821d8-e97a-4474-9362-57bbe8d2a5a5.png)
