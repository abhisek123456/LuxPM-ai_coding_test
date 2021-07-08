# LuxPM-ai_coding_test


Step 1 

Download the files from "yolov4apple" folder (which is in my drive and the link is https://drive.google.com/drive/folders/1NBJ6UR9BiOJHG38vF7nhsn16Gzhgo-br?usp=sharing) and save the file in a folder call "yolov4apple" and upload it in your drive.

Step 2

Follow Test_model.ipynb, everything is given clearly. 


The contents of "yolov4apple" folder

backup -- contain the trained weights of 2000 batches. The training of weights has been done in "yolov4apple.ipynb"

generate_test.py and generate_train.py -- custom detector are the train.txt and test.txt files which hold the relative paths to all our training images and valdidation                                             images.

obj.data -- contain the path of train, valid, names and backup

obj.names --  contain the classes, in this case it is only one class. 

obj.zip -- contain the training images 

test.zip -- contain the testing images 

yolov4-obj.cfg --  contain the configuration of the custom training.  In this the size is taken as 416 by 416 and max batches taken is 6000. The filter size is 18 and                      classes is 1


