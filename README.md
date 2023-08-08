# Project 4 Home Price

### **Project Description:<br>**
Predict Housing prices

### **Project Room 1 Team:**

- Matt Siriani
- Vincent DeScioli
- Phil  Okoth
- Robert Bellgraph


### **Using:** 
- Pandas 
- Matplotlib
- Seaborn
- PostgreSQL
- Scikit-learn
- ML (Logistic Regression Model)
- ML  Root-Mean-Squared-Error (RMSE) 


### **Changes and outcomes:**
Oringal 
Secondary


<br><br>

### **Testing Changes and Outcomes**
*15 variables Using Dummies Model:*

- 50,50,35   relu, relu, relu, relu  output relu Using 100 Epocks 
Rmse   27297   is the estimated that we would see. 

- 35,35,12   LeakyReLU , LeakyReLU ,LeakyReLU , output LeakyReLU using 100 
Rmse  31863   is the estimated that we would see. 

- 75,75,35   LeakyReLU , LeakyReLU ,LeakyReLU , output ReLU using 100 
Rmse  49859.1094   is the estimated that we would see.

- 75,75,35   LeakyReLU , ReLU ,ReLU , output ReLU using 100 
Rmse  30640.2910   is the estimated that we would see.

- 75,75,35  ReLU, LeakyReLU ,ReLU , output ReLU using 100 
Rmse  26541.9277   is the estimated that we would see.

- 25,25,12  ReLU, ReLU ,ReLU , output LeakyReLU using 100 
Rmse  30362.1641   is the estimated that we would see.

- 25,25,12  ReLU, ReLU ,ReLU , output ReLU using 100 
Rmse  29295.9590   is the estimated that we would see.

- 75,75,40  ReLU, ReLU ,ReLU , output ReLU using 110 
Rmse  *25,739.3203*   is the estimated that we would see.

- 75,75,40  tanh, ReLU ,ReLU , output ReLU using 110 
Rmse  35952.0664   is the estimated that we would see.

Using Sigmoid activation as the output we would see rsme greater than 150000


Data:  https://www.kaggle.com/competitions/home-data-for-ml-course/data
Data Description txt file added 

