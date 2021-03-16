# Face-Recognition-Model
In  this  problem,  we  use  a  pre-trained  model  trained  on  Face  recognition  to  recognise  similar  faces.  Here,  we  are  particularly interested in recognizing whether two given faces are of the same person or not.
Below are the steps involved in the project.
•Load the dataset and create the metadata.
•Check some samples of metadata.
•Load the pre-trained model and weights.
•Generate Embedding vectors for each face in the dataset.
•Build distance metrics for identifying the distance between two given images.
•Use PCA for dimensionality reduction.
•Build an SVM classifier to map each image to its right person.
•Predict using the SVM model.
