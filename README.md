# image-classifier
this is a image classifier made using keras package based on tensorflow backend .
simple implementation of a convolutional neural network model
which differentiates human from horse.
the accuracy is 59.9 percent due to the small size of training samples.
higher accuracy can be achieved by using large amounts of samples or
by transfer learning.
to implement this

1 extract the folder to your jupyter work directory
2 open handh.ipynb which shows step by step process of developing cnn and saving model
3 open handhcopy-2 which shows how to load the already saved model into notenook and run
4 all the data is in correct folder
           train
               humans(images folder)
               horses(images folder)
           valid
               humans(images folder)
               horses(images folder)
            t1
               test
ic.yaml is the exported environment


please add the following in handhcopy-2 in import section:

from keras.preprocessing.image import ImageDataGenerator, array_to_img, img_to_array, load_img
img_width, img_height = 150, 150
