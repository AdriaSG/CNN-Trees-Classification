# CNNfTreesClassification
For Depp ;eraning class at BHT I has implemented a model for tree bark classification using the dataset given at https://www.vicos.si/Downloads/TRUNK12 (just above 1GB)

One way to solve this task is to use the features computed by different layers of a standard convolutional neural network, feel free to pick one here:
https://keras.io/api/applications/, that page also contains the code examples for extracting features from different network layers and finetuning models. 

The goal of this task is to explore how the most important feature of tree/bark recognition can be predicted with the features in earlier or later layers of a CNN. For this implementation I had chosen MobileNet2 using TensorFlow, data has been splittes 60%/40%. Accuracy achieved for this task reaches 92% for explored data. 
 
