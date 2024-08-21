This project uses the specific dataset provided at kaggle:
https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images/data

It serves for practice and studying purposes only.

For the classification we deep learning by feeding the neural network one-hot encoded labels which represent our classes.
We got a pretty good result, even though we did not train for a lot of epochs because of time constraint reasons.

The architecture for the model was really simple in the beginning and it did not bring good results, having an AUC of 0.65 after 100 epochs so as practice I researched for more complex architectures and got way better results in less epochs.
The architecture was inspired from this notebook: https://www.kaggle.com/code/amyjang/tensorflow-pneumonia-classification-on-x-rays#4.-Build-the-CNN.

In the future I'll try to repeat this with google cloud AI or others so I can use multiple TPUs/GPUs to speed up the process and try with more epochs.