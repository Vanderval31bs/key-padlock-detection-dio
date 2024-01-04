# key-padlock-detection-dio

This project is done with the purpose of constructing a machine learning model that detects keys and padlocks in images.

The dataset is contained in key_padlock_detection_data/zip. It is divided in three files zip files because github has a maximum file limit size, so the first thing to do to run this project is to join the files in the three zip into a single images_and_annotations.zip  file. 
After that, you will need to upload key_padlock_detection_data folder into your google drive, and then you can run the notebook.

Some sample predictions are inside the folder predictions.

The dataset was constructed with images from Shutterstock. 
The annotations were made with the help of makesense.ai.
The model is a transfer learning from the previously trained detection network YOLO.

There are still some changes to be made to make the code more clean.
Another possible modification are related to more accuracy in detection. That could be made by getting a better train dataset (for example, doing some data augmentation).
