# Plant_Disease_Prediction
The " KRISHI- Farmer’s Interface " project intends to reduce the suffering of Indian farmers by giving them a technique for quickly identifying crop diseases so they may treat their crops before they decay. The software has been developed using Python and Machine Learning tools. 

**PROBLEMSTATEMENT**

Farmer suicides in India refers to the national catastrophe of farmers committing suicide since the 1970s, due to their inability to repay loans mostly taken from private landlords and banks. NCRB data shows that the incidence of farmer suicides has remained high in the 6 years between 2014 and 2020. 5,600 farmers committed suicide in 2014, and 5,500 farmers committed suicide in 2020. If you add agri labourers to the 2020 number, the number of suicides rises to over 10,600. (CNBC report August 12, 2022). Crop failure is one of the major factors responsible for farmers committing suicide. Since the past days and in the present too, farmers usually detect the crop diseases with their naked eye which makes them take tough decisions on which fertilisers to use. It requires detailed knowledge the types of diseases and lot of experience needed to make sure the actual disease detection. Some of the diseases look almost similar to farmers often leaves them confused.
 

**AIM/OBJECTIVE**

 Since crop illnesses are the primary cause of the farmer suicides that occur annually in India, the " KRISHI- Farmer’s Interface " model helps Indian farmers by informing them how to recognize crop diseases. 

Some key features of this project are:


A.	Early disease prediction
B.	Farmers can apply fertiliser and pesticides based on the disease found on their crop.
C.	Can use this on their mobile
D.	Take a photo of the diseased plant leaf to check for disease.


**MY ROLE**

•	Machine Learning model development
•	Presentation 

**TECHNOLOGY USED**

•	TensorFlow
•	Keras 
•	VGG19 model
•	Python and its Libraries like (Pandas ) 

**WORKING OF PROJECT**

![image](https://user-images.githubusercontent.com/73419872/212808632-5183383f-d3b5-4d61-911f-2f359e038471.png)
 
Main Steps to build a CNN (or) Conv net:
1.	Convolution Operation
2.	ReLU Layer (Rectified Linear Unit)
3.	Pooling Layer (Max Pooling)
4.	Flattening
5.	Fully Connected Layer
6.	Code.



1. Convolution is the first layer to extract features from the input image and it learns the relationship between features using kernel or filters with input images.

2. ReLU Layer: ReLU stands for the Rectified Linear Unit for a non-linear operation. The output is ƒ(x) = max (0, x). we use this because to introduce the non-linearity to CNN.

3. Pooling Layer: it is used to reduce the number of parameters by down sampling and retain only the valuable information to process further. There are types of Pooling:
•	Max Pooling (Choose this).
•	Average and Sum pooling.
4. Flattening: we flatten our entire matrix into a vector like a vertical one. so, that it will be passed to the input layer.

5. Fully Connected Layer: we pass our flatten vector into input Layer. we combined these features to create a model. Finally, we have an activation function such as softmax or sigmoid to classify the outputs.

![image](https://user-images.githubusercontent.com/73419872/212808651-ce8afa34-d42d-4394-9a96-7edb634c2c23.png)

![image](https://user-images.githubusercontent.com/73419872/212808482-4401285a-970c-435b-ae30-05db6469b8dd.png)

![image](https://user-images.githubusercontent.com/73419872/212808490-7b30b610-7b54-412e-b399-8d00f85d84bd.png)

![image](https://user-images.githubusercontent.com/73419872/212808673-66b8fe61-a7f6-4d7d-b0cc-deac32d792fa.png)

![image](https://user-images.githubusercontent.com/73419872/212808688-4ae0e1f1-856e-4697-95d4-01dbaa93efaf.png)

![image](https://user-images.githubusercontent.com/73419872/212808703-79919203-1c7e-4211-bf61-e42f031fb477.png)

**FUTURE SCOPE**

This website has following Future Scope:
1.Include a farmer-to-customer interface so that clients may purchase fruits and vegetables from this platform directly and without the need for a middleman.
2.Weather forecasting.
 
**REFERENCES**

1.https://towardsdatascience.com/crop-plant-disease-identification-using-mobile-app-aef821d1a9bc 
2.https://towardsdatascience.com/the-basics-of-deep-neural-networks-4dc39bff2c96 
3.https://www.kaggle.com/datasets/rajibdpi/plant-disease-dataset
4.Edureka YouTube Channel 
