# landscape-image-recognition
 An image recognition project using TensorFlow. In this project I have used the following dataset: https://www.kaggle.com/datasets/utkarshsaxenadn/landscape-recognition-image-dataset-12k-images.

I have built 3 models with TensorFlow, trained to classify images of landscapes into 5 categories: Coast, Desert, Forest, Glacier, Mountain. In the first model I use a standard architecture, a learning rate of 0.001 and 10 epochs. In model 2 I add image augmentation. In model 3, I use image augmentation, modify the architecture to contain more convolutional layers, a dropout layer, and another dense layer. I changed the learning rate to 0.0001 and number of epochs to 15. All models use optimizer Adam. Accuracy was chosen as the metric, because the dataset is balanced and no classes hold more weight than the others.

After training the models on the training and validation data, I evaluate all three on the test data, presenting the results with a confusion matrix and the accuracy score. Model 3 was the best performer with an accuracy of 0.8160, followed by Model 2 with 0.7680, and then Model 1 with 0.7660. 


![Slide1](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/1042b44f-b024-41b1-affa-76190cdc15d3)
![Slide2](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/1f67473c-a7e7-44e4-8756-06c37292f94a)
![Slide3](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/f71b1acb-a388-4241-bf77-f28ee62ccca1)
![Slide4](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/86a401b0-5db5-4f21-9ee2-ef3b821b00f7)
![Slide5](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/d6ca190b-f5d5-4e2b-a5ec-63b49fc831ca)
![Slide6](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/4fed2716-50da-4bdd-86f0-2109cb4c13cd)
![Slide7](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/963b7bcb-a3a9-49ed-9949-2fbfe1ddc361)
![Slide8](https://github.com/shimbarashamba/landscape-image-recognition/assets/73606183/2a219e5c-52f5-4409-b25d-4a12dd67e3a2)

Overall it has been a fun project which allowed me to further familiarize myself with the TensorFlow library.
