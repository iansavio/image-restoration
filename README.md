# image-restoration
A project to restore images with fixed pattern of missing pixels for the final report of the Advanced Topic in Knowledge-based Systems course, Spring semester of 2023 by Ignasius Ian Savio Gunawan 6613230003-9.

A folder in the repository consists of the images used in this project. The dataset is comprised of grayscale bitmap image files from the ([missing pixels database](https://github.com/dmc27/missing_pixels))  as well as the JPEG image files from ([ImageNet ILSVRC2012](https://www.kaggle.com/competitions/imagenet-object-localization-challenge/data)) . Due to time and resources constraint, only a total of 1500 images were used. In the future, more images can be used to expand the dataset and improve the performance of the models. In this repository, three test images have been uploaded.

The trained models have been saved and uploaded here as h5 files. These models can be loaded using Keras' load_model function.

An ipynb file has been uploaded to observe the performance of each model. However, since the dataset is not available in this repository, steps 3 and 4 should not be run at all. Those steps are used strictly for organizing the training data and training the models. In order to test the models, steps 1, 2, and 5 should be executed instead. In this repository, the three test images used in the report are included. The same should be applied to the ([Google Colab](https://drive.google.com/file/d/1syxt3mYaTQAwOQ9v0QVhS2MFcG6P2XXd/view?usp=sharing)) version of the file .

The yaml file provided here can be used to replicate the environment in which the whole project is conducted.

Lastly, there is also a ([OneDrive](https://ritsumei365-my.sharepoint.com/:u:/r/personal/is0532ps_ed_ritsumei_ac_jp/Documents/image-restoration.zip?csf=1&web=1&e=dgn1Q5)) link to access the zipped version of the whole project. 
