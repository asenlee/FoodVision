# FoodVision :fries: 

Food Vision application using TensorFlow (mixed precision training) and Food101 dataset.

As an introductory project for deep learning/neural network, I built an end-to-end CNN Image Classification Model which identifies the food in your image.

I implemented a pre-trained Image Classification Model (EfficientNetB0) that comes with Keras and then retrained it on the Food101 Dataset that is provided by Tensorflow Datasets.

### Fun Fact:
Our model actually beats the DeepFood Paper's model which is also trained on the Food101 dataset.

In the DeepFood Paper, they achieved accuracy of 77.4% while our model produced an awesome score of 80%. What's more is that while it took days to train the DeepFood model, our model was able to train in less than an hour!

### Summary of work performed

1. Imported Food101 dataset from Tensorflow Datasets module.
2. Familiarized myself with the data by visualizing (i.e. generating random images with labels).
3. Set Global dtype policy to `mixed_float16` to implement Mixed Precision Training.
4. Utilized Model callbacks to help with feature extraction and fine-tuning.
5. Fine-tuned our model to improve accuracy by 10%
