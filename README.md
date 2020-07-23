# LSBU-Skin-Image-Analysis-Tool
This graphical user interface (GUI) based skin image analysis tool provide several functions: a) skin image classification by using Deep Learning neural networks such as AlexNet, GoogLeNet and so on; b) skin image search by using Gabor Wavelet Transform, Principle Components Analysis, Gray-Level Co-Occurrence Matrix; c)skin live image analysis in real time which allows RBG calculations, as well as face detection and upper body detection.
# Download and Installation
1. Go to the "Download.txt", use the link to download the MATLAB App Installer file called "LSBU Skin Image Analysis.mlappinstall", and save it in a local directory.
2. In MATLAB, go to the directory, double click the file to install it in your MATLAB App tab.
![Download and Installation](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/install.jpg?raw=true)
3. From your MATLAB App tab, double click the "LSBU Skin Image Analysis" ico to run.
![Download and Installation](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/run.jpg?raw=true)
# Skin Image Classification
1. Training
Click the "Train" tab in the program, first select the folder where your training data is, your images should put into several subfolders, and subfolders names will be used as classification label, then select the Deep Learning model (AlexNet, GoogLeNet etc.), click "Train" button, this might take a few minutes to a few hours, depends on the data size, model and your computing power. But for each data folder, you only need to train once.
![Download and Installation](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/train.jpg?raw=true)
2. Classification
Once you have trained the model, click the "Classify" tab, 
![Download and Installation](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/classify.jpg?raw=true)
