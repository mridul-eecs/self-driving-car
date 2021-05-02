# self-driving-car

Supervised machine learning applied to images from 3 dashboard cameras capturing the route, along with steering angles using OBD data collector.
The model predicts the steering angle of the car.
Car is modeled for left-lane driving, meeting real-life driving scenarios.
A regression deep neural network is developed referred from "end-to-end self-driving car" paper from NVidia.
The model validation mean-squared error is improved upto 0.014, using commonsensical image augmentations, hyperparameter tuning, and regularization techniques.
The model is tested on Udacity open-source simulator with multiple tracks, the model is also tested on a real-world open-source dataset collected by Sully Chen.

