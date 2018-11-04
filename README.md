# Convolutional-Neural-Networks
CNN model to classify images of cats and dogs.                                                                                              
**Dataset available at:** http://www.superdatascience.com/wp-content/uploads/2017/04/Convolutional_Neural_Networks.zip          
* ## Model - 1:
  * Two Convolutional Layer with a pooling layer each
  * Two fully connected layer
  * A single output layer                                                                             
                                   
![](Model_1.jpg)

The model **Overfitted**.
                                               
* ## Model - 2:
  * Previous model with Dropout                                                          
                           
![](Model_2.jpg)                                           

This model **Overfitted** too but with less Training accuracy.                                    

* ## Model - 3:
  * Two Convolutional Layer with a pooling layer each
  * Single fully connected layer
  * Single output layer                                                                  
   
   ![](Model_3.jpg)                                                              
   
   This model was also starting to **Overfit**.                             
   
* ## Model - 4:
  * Three Convolutional Layer with a poolng layer each
  * Single fully connected layers with large number of units with a large dropout rate
  * Single output layer                                                                  
  
  ![](Model_4.jpg)                    
  Model with an accuracy of **86%**.                                                        
  The accuracy may increase with the increase in the number of epochs. 
  
