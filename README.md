# Rice-Leaf-Disease-Detection
## Introduction :-
The rice leaf suffers from several bacterial, viral, or fungal diseases and these diseases reduce rice production significantly. To sustain rice demand for a vast population globally.The rice leaves related diseases often pose threats to the sustainable production of rice affecting many farmers around the world. Early diagnosis and appropriate remedy of the rice leaf infection is crucial in facilitating healthy growth of the rice plants to ensure adequate supply and food security to the rapidly increasing population.
### RICE LEAF DISEASE :-        
#### 1. Leaf Smut :-
Leaf Smut, Caused by the fungus. The Fungus produces slightly raised, angular, black spots on both sides of the leaves. Although rare, it also can produce spots on leaf sheaths. The black spots are about  0.5 to 5.0 millimeters long and 0.5 to 1.5 millimeters wide.
![image](https://github.com/GaneshAhire30/Rice-Leaf-Disease-Detection/assets/114847888/4d17339b-d00c-4591-af4c-79f2b8babdad)

#### 2. Brown Spot :-
Brown spot has been histroically largely ignored as one of the most common and most damaging rice diseases. Its most observable damage is the numberous big spots on the leaves which can kill the whole leaf.  Infected seedlings have small, circular, yellow brown or brown lesions that may girdle the coleoptile.
![image](https://github.com/GaneshAhire30/Rice-Leaf-Disease-Detection/assets/114847888/7253c24d-f994-4a87-9b4b-98283ea33577)
#### 3. Bacterial Leaf Blight :-
Bacterial blight is caused by  wilting of seedlings and yellowing and drying if leaves. It is commonly observed when strong winds and continuous heavy rains occur, allowing the disease-causing bacteria to easily spread. In general, the disease favors temperatures at 25-34 degree Celsius, With relative humidity above 70%.
![image](https://github.com/GaneshAhire30/Rice-Leaf-Disease-Detection/assets/114847888/416b6f7f-b9bf-47e5-992b-82cd5083ec1b)

##  DATA SUMMARY :-
*This dataset contains 119 jpg images of disease infected rice leaves. The images are grouped into 3 classes based on the type of disease. There are 40 images for Brown Spot, 40 images for Bacterial Leaf Blight, 39 images for Leaf Smut.*

**Class :-**

  1. **Leaf Smut**
  2. **Brown Spot**
  3. **Bacterial Leaf Blight**
### WE HAVE DEVICE THE PROJECT INTO MULTIPLE STEPS  :-
* Importing library
* Loading data
* Preparing data
* Data Processing
* Model building
* Training
* Evaluation
* Testing
## Loading Data / Preparing Data :-
* Make a subset of data into three parts train, test, and validation with the help of split folder library.
## Data Processing :-
* In this step generate the batches of training and validation and pre-process the images.
## Model Building :-
* In this steps we create CNN model architecture in that three types of layers  Convolution layer, Pooling layer And Fully connected layer are added.

* Get the summary of model.

* compile model.

* Then the last train the model 

* After training validation accuracy is 90.91% And training accuracy is 91.58%.

* And save the model.

* Plotting a graphical representation of Plot Accuracy And Losses.
## Model Evaluation :-
* Created the model summary.
* Here the loss is 0.31 and the accuracy of the model is 0.8462 percent means 84.62%.
## Model Testing  :-

* Visualise the prediction of the model :-
![image](https://github.com/GaneshAhire30/Rice-Leaf-Disease-Detection/assets/114847888/763e3377-9ade-4b13-b78e-457983955004)

* In this step we are create a funtion to test multiple images from test data.
