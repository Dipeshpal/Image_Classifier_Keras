
# Image_Classifier_Keras

 Image Classifier in Keras by using Inception, Resnet, VGG etc

## Get Started-

This is the universal Image Classifier, with this project you can classify any images. You just need to trained it on your own dataset.

1. Download above file

2. Open it on Google Colab (Recommended) or in any Python Editor

	If you are not using Google Colab (If you are using any Python Editor) then comments the **"Connect with Google Drive for Google Colab"** this section of code.

3. Create a folder called "train"

4. Put some set of images in folder
	
	Example-
	![Images](https://i.ibb.co/fY95sdf/Capture.png) 
 

6. Now open **training.ipnyb** or **training.py** file and set your train directory path (mandatory) and few more varibles (optional)

	![Screenshot](https://i.ibb.co/rkV5P6P/2.png)


7. Optional: You can import different model from [Keras](https://keras.io/applications/) and train it. By default it will train on [InceptionV3](https://keras.io/applications/#inceptionv3). If you use different model you may need to change the input shape of images, for mode details you can see the [Keras](%28https://keras.io/applications/%29) model documentations.


## Predict your images after training-

1. Open  [keras_predict.ipynb](https://github.com/Dipeshpal/Image_Classifier_Keras/blob/master/keras_predict.ipynb "keras_predict.ipynb") or [keras_predict.py](https://github.com/Dipeshpal/Image_Classifier_Keras/blob/master/keras_predict.py "keras_predict.py") file and create dictionary of your classes and set it to "dict1" variable in code-
![Image](https://i.ibb.co/CbFHkK4/aaassaaaa.png)

2. Now predict your own image just by set your own path of image and model-
![Predict_Image](https://i.ibb.co/NWc5jqS/2121212121.png)
