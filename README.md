# Drunkenness-Face-Detection-Using-Graph-Neural-Network

Tipsy is a an android app, to detect intoxication in a person. This app is backed by GNN based deep learning model. The detailed project idea is is mentioned in the paper. The following repository is the implementation of the model
The requirements to execute this project are as below:

1. Smartphone

	. RAM: 512MB	

	. Space: 500MB

	. Cache: 200KB

	. Camera: 5MP+

	. Android Version: 4.4+

	. SDK : 26+

2. Google Colab

3. Firebase

**Repository Contents -**

**1.**  (Folder - Model)        This contains the saved trained model

**2.**	(File   - Shape.dat)    This is the pre-trained model of facial landmark locator

**3.**  (File   - appUtils.pyc) This is Compiled Python Script File containing utility functions for the server program

**4.**  (File   - App.ipynb )   This is python notebook that is to be runned on Google Colab , which acts as the server for our app.



**STEPS**


**1.**	Make sure all the repository contents are in the same directory

**2.** Download the tipsy.apk from https://tinyurl.com/tipsyapk and install in your smartphone

**3.** Open App.ipynb and execute all the cells, the last cells runs continoulsy

**4.** Open the app and send the image, the result will be displayed in the app shortly