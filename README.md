
 # A self supervised model for image classification using rotation  #

This project is inspired by [Lars Vagnes implemntation of SSL for Image Classification on Cifar-10 dataset](https://medium.com/analytics-vidhya/self-supervised-learning-for-image-classification-263e320fff07) using the image rotation methedology from [this paper](https://arxiv.org/pdf/1803.07728.pdf).In our code we implement Cats vs Dogs dataset image classfication task using self supervised learning. The goal of the project is to determin how much unlabeled data is needed to learn a visual representation that can compete with standard supervised learning with equivalent label data in the downstream task. 

The response is discovered by running two simultaneous training sessions on ten separate data volumes, one with SSL and the other without. The resulted accuracy of image classifier is compared in both scenarios to draw a conclusion about the number of labelled data influencing the downstream task.The detailed report of this experiment can be found in this link: 
