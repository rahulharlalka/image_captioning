# image_captioning
this is Deep Learning based image captioning project 

the image_captioning_train file is the jupyter notebook file in which all the training regarding the image captioning is done .
the images are used from the flick-30k dataset(dataset being availabelin kaggle )

the images are reduces to the feature vector form using the vgg16 model and are saved in the pickle file.
the captioing and the reduces feature vectors are then trained to learning the captions using lstm models .

predictions for test images can be done by simply running the predict.ipynb file.
for predicting on your own test images you simply need to put your test image in the test folder and run the predict.ipynb file.
the captions for the given image willb e generated.

Thought the project has been completed for the DL part, the training has not been able to be user good due to extensive computationand lack
of hardware resources.
Improved version of this model will be pushed soon.

the project will also be given a web frontend to provide a better user experience in future.
