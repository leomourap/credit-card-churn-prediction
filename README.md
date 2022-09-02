![Credit_Card_Churn_Prediction](https://user-images.githubusercontent.com/105673165/187865009-bedea22b-2f52-4964-8979-29a293a22311.png)

## Producing a model to predict customer churn potential - a Classification problem!
##### *My first machine learning project.

  - dataset available at: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

*Please, to check an ideal notebook, i recommend you to open the repository link in NBViewer (https://nbviewer.org/), since it's a heavy notebook with a Pandas Profiling report that doesn't appear in GitHub.

### Problem description - extracted from the "dataset publisher" at the link above:
  - A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really 
  appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide 
  them better services and turn customers' decisions in the opposite direction

  - Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit 
card category, etc. There are nearly 18 features.

  - We have only 16.07% of customers who have churned. Thus, it's a bit difficult to train our model to predict churning 
customers.

##



Pandas Profiling
Overview

![image](https://user-images.githubusercontent.com/105673165/188078259-071bc721-8ccf-4351-936a-11fd5922f628.png)

Alerts

![image](https://user-images.githubusercontent.com/105673165/188078725-983aa823-30db-4550-897d-57efba89e635.png)
![image](https://user-images.githubusercontent.com/105673165/188078596-6bc5a51b-1506-44c8-8f9e-a388c4a0eee9.png)
![image](https://user-images.githubusercontent.com/105673165/188078880-962e879c-4555-4f1a-a392-a8bcaa3edb6d.png)
![image](https://user-images.githubusercontent.com/105673165/188078653-add19c87-0da0-47e9-8667-8ade986045f3.png)

Detalhes variaveis

![image](https://user-images.githubusercontent.com/105673165/188076977-9c40070b-0e63-429d-9afd-dacd871498de.png)

Var. Correlations

![image](https://user-images.githubusercontent.com/105673165/188079353-377126d0-3e23-407d-a38d-1a696c4213d4.png)
![image](https://user-images.githubusercontent.com/105673165/188079429-a6ccda09-21fb-4beb-a18f-bc3a9700be0a.png)


Unseen Data e Dataset para modelo

![image](https://user-images.githubusercontent.com/105673165/188080928-f72f1041-7f93-4d5f-8d03-5bc23c29f698.png)
![image](https://user-images.githubusercontent.com/105673165/188080978-ff41186c-46e2-4b3c-ae44-f68b89c539e4.png)

PyCaret
![image](https://user-images.githubusercontent.com/105673165/188081282-56258ed8-5fed-4dc6-ab59-16be701471f1.png)

Data Preprocessing
![image](https://user-images.githubusercontent.com/105673165/188081539-fd832d08-3d4b-46f1-b4da-85b267d16b30.png)
![image](https://user-images.githubusercontent.com/105673165/188081738-96a359ff-cbeb-4019-830d-ada3a59c9939.png)
![image](https://user-images.githubusercontent.com/105673165/188082226-9eaf29d8-db8b-4c85-b197-1bea916a5ad5.png)


Model Training
![image](https://user-images.githubusercontent.com/105673165/188081598-1fedb736-1ae6-427c-97c4-1db13e840263.png)
![image](https://user-images.githubusercontent.com/105673165/188082341-c56981f3-a50f-460e-a273-353d100e3f18.png)

FALAR DOS RESULTADOS!

Imbalanced Target

![image](https://user-images.githubusercontent.com/105673165/188078095-bd4d8bb9-2855-42e4-8e58-986a0d0a22d2.png)
