# Project 4 Home Price

### **Project Description:<br>**
Predict Housing prices

### **Project Room 1 Team:**

- Matt Siriani
- Vincent DeScioli
- Phil  Okoth
- Robert Bellgraph

Overview:
Buying and/or selling a home is one of the most important financial decisions in an individual’s life. The ability to predict home sales via machine learning  provides important information and benefits to these investments in the real estate market.    
The goal of this project was to analyze property sales records and fit the data to a model that help predict sale prices most accurately.  
Several tools were used to accomplish this task and data was obtained from the link below..


Data:  https://www.kaggle.com/competitions/home-data-for-ml-course/data

### **Using:** 
- Pandas 
- Matplotlib
- Seaborn
- PostgreSQL
- Scikit-learn
- ML (Logistic Regression Model)
- ML  Root-Mean-Squared-Error (RMSE) 


### **Changes and outcomes:**
We had used variables of 15, 22, and 60(all). We tested many vatiations of Featues, Neuron/Layers, activation functions and epochs to determine our best performance. Below are some examples. 
<br><br>
### **Testing Changes and Outcomes**
*15 variables Using Dummies Model testing:*

- 50,50,35   relu, relu, relu, relu  output relu Using 100 Epocks 
Rmse   27297   is the estimated that we would see. 

- 75,75,35   LeakyReLU , ReLU ,ReLU , output ReLU using 100 
Rmse  30640.2910   is the estimated that we would see.

- 75,75,40  ReLU, ReLU ,ReLU , output ReLU using 110 
Rmse  25,739.3203  is the estimated that we would see.

- 75,75,40  tanh, ReLU ,ReLU , output ReLU using 110 
Rmse  35952.0664   is the estimated that we would see.

RELU was the best fit for out models overall performance. 

### *Additional Charts and detail:*

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/b2b94591-6953-49b6-b48d-b00f29639f1f)

The following image is a chart that shows the number of houses sold based on age.

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/7f1cb8b5-d2aa-4bbf-993b-83c197b201e2)

The following image is a chart that shows the number of houses sold based on the garage type.

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/c9beeee0-9783-4c91-b246-1bc52efc4e3b)

The following image is a chart that shows the number of houses sold based on the type of neighborhood they are in.

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/8ee96cbb-44c5-48c8-b561-159cb0c39d2a)

The following chart shows the number of data entries we have for our dataset.

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/1ccce762-8f15-4539-a03f-ab6d6d8e7962)

The following image shows the amount of houses sold based on the number of cars in the garage.

![image](https://github.com/rbellgraph1/project_4_home_price/assets/124213934/23516fae-f17d-4163-88b2-233438c9d15f)

The following image shows the number of houses sold based on house type.


