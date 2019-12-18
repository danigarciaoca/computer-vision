### Directions for Running check_images.py using all 3 Model Architectures (uploaded_images folder)
The main script will be check_images.py. To get the output, you will have to run it on all 3 models (VGG, Alexnet and Resnet) to classify the four images in the uploaded_images folder. To do this you will be calling the following shell script that will output the following results files:

- resnet_uploaded-images.txt - that contains the results using CNN model architecture ResNet
- alexnet_uploaded-images.txt - that contains the results using CNN model architecture AlexNet
- vgg_uploaded-images.txt - that contains the results using CNN model architecture VGG

The shell script file is **run_models_batch_uploaded.sh**, and it can be run by typing the following on a terminal window:
```sh
sh run_models_batch_uploaded.sh
```
