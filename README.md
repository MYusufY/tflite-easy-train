This is my first Github repo for testing.



This project makes it easy for you to do custom object detection using Raspberry Pi and TFLite. All you have to do is put the pictures in jpg format in a folder. (There may be 70 images to start with, but more images would be better.) After creating the files required for defining these images in .txt format in LabelIMG, create a folder and create 2 more folders named "train" and "validate". Put all the files in the train folder. Put a few images and .txt files (example: 10 images) in the Train folder into the "validate" folder. Once these are done, zip the main folder containing the "train" and "validate" folders as .zip and upload it to Google Colab inside the folder. For more detailed explanation and example: https://www.youtube.com/watch?v=-ZyFYniGUsw
Link of Collab Notebook used for training: https://colab.research.google.com/github/khanhlvg/tflite_raspberry_pi/blob/main/object_detection/Train_custom_model_tutorial.ipynb

This project contains only the necessary files to make the job easier. When you get the .tflite file, just put it in the folder and run the "detect.py" file. Like I said I'm just making a repo for testing. Good projects.


------------------------------------UPDATE-----------------------------------

You will need to install the tensorflow library because the file is big I couldn't put it in my repo.
