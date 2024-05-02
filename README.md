# Coffee-Roasting-Classification-with-Neural-Networks
This repository contains code for implementing a neural network model for coffee roasting classification using TensorFlow and NumPy. Below is a breakdown of the key components and steps involved:

## Data Preprocessing
- The coffee roasting dataset is loaded and visualized using plt_roast. It includes features such as temperature and duration of roasting, along with corresponding labels indicating the quality of coffee roasting.
- To enhance model convergence and performance, the features are normalized using TensorFlow's Normalization layer.
## Model Construction
- A neural network model is constructed using TensorFlow's Keras API. It comprises two dense layers (layer1 and layer2) with sigmoid activation functions.
- The model is compiled with binary cross-entropy loss and Adam optimizer.
- Training is conducted on the augmented dataset (Xt and Yt) for a specified number of epochs.
## Weight Initialization and Evaluation
- Upon training completion, the trained model's weights are retrieved and inspected.
- Optionally, the model can be initialized with predefined weights.
- Predictions are made on test data (X_test), and decisions are determined using a threshold of 0.5.
## Visualization
  The model's decision-making process and predictions are visualized through various plotting functions:
   - plt_roast: Visualization of the Coffee Roasting Data.
![Plot-Coffee-Roasting-Data](https://github.com/UMMY87/Neurons-and-Layers-in-Linear-and-Logistic-Regression/assets/117314436/038d7b66-0b4c-459b-96e6-b416f11b5f78)

   - plt_layer: Visualization of the hidden layer's decision boundaries.
![Plot-of-layer1-with-unit-0,1,2](https://github.com/UMMY87/Neurons-and-Layers-in-Linear-and-Logistic-Regression/assets/117314436/daf851af-20c1-4e81-8fb2-ce00b55bb82a)

   - plt_output_unit: Visualization of the output unit's decision boundary.
![Plot-of-layer2-with-unit-0,1](https://github.com/UMMY87/Neurons-and-Layers-in-Linear-and-Logistic-Regression/assets/117314436/4ddaede6-0586-4e72-a1c3-eb23bec8c1d7)

   - plt_network: Visualization of the entire neural network architecture.
![Plot-of-network-probability- -decision](https://github.com/UMMY87/Neurons-and-Layers-in-Linear-and-Logistic-Regression/assets/117314436/23475555-f7c1-466c-81e3-63a50bcaf7aa)

## Conclusion
This repository serves as a demonstration of implementing a neural network model for coffee roasting classification, covering data preprocessing, model construction, weight initialization, evaluation, and visualization using TensorFlow and NumPy. It provides insights into leveraging deep learning techniques for classification tasks in real-world scenarios.
