# Science-Becoming-Less-Disruptive
## Feature enginnering and training regression models (+NN)

* This is a project created in the context of the course: "Applied Machine Learning".
* In this assignment we will create a Machine Learning model that can predict, as accurately as possible, the CD5 of a published paper.
* The analysis will be done on Google Colab

--- 
## RUN && Install 
* Open jupyter notebook named :: `NeuralNetworkk.ipynb` and run all cells. (For Feature Engineering and Non Neural Network Models)
* Open jupyter notebook named :: `NeuralNetworkk.ipynb` and run all cells. (For Neural Network Model)

Note :: Intall locally all needed python packages that exist in jupyters (first cells). 
## Results / Conclusions of the assignment 

------

* From the whole analysis our best model is the **Neural Network Regressor** with **Mean Absolute Error** equal to **0.03307007625699043**.
     * Then Random Forest is better with about MAE ~0.39
     * Then Decision Tree is the third betetr about MAE ~0.40
     * For both Random Forests and Decision Tree dominant important feature with big diffrence is the feature refrencies, whereas is LightGBM times, refrensies and published year are dominant but without big diffrence.
     * Fianlly, XBoost has the lower MAE in comparison with other regressor models that we trained.
* In addition, our Decision Tree Classifier plays supportive role for debugginh and having a general idea if cdindex will be high or medium, for low cdindexx the model is not predict well.