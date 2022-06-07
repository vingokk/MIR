# Medical Image Recognition Project
## Detail
This is my project for my undergraduate thesis.
My thesis focuses on how to apply deep learning in medical image recognition. Based on deep learning, the thesis proposes a system with three modules that can automatically obtain medical images with annotation. 
## (1) Image acquisition module
based on keyword retrieval, using python to build a web crawler, the module can automatically download medical images from an academic 
website. 
## (2) Image classification module 
based on the image content, using a CNN model, the module can classify the image. 
## (3) User interface
built on Python toolkits, the module can connect the two modules mentioned above and accomplish the human–computer interaction. In this thesis, through a number of comparative experiments, a VGG-16 model is selected from four classic CNN models to apply in the system, and its classification accuracy now is 82.3%. Based on Jupyter Notebook, the system uses Pytorch to build its algorithm. Besides, the data management and model training mainly rely on ModelArts which is a platform provided by Huawei
