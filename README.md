# multitask
To run the code:
Clone the repo as usual. Run SegNet.py . use_vgg has to be set to false, since pre-trained vgg weights are not being used. 

layers_object.py contains definition of each type of layer
evaluation_object.py contains loss defintions
inputs_object.py contains function definitions for reading from files
SegNet.py contains the class definition for each individual SegNet network, and also the train function
config.json contains the values of the parameters being used
trainp.txt contains image paths in the order image1_path.jpg image1's_label_image.jpg image2....  (p=1,2,3,4)
