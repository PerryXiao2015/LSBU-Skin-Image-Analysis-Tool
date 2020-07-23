# LSBU-Skin-Image-Analysis-Tool
This graphical user interface (GUI) based skin image analysis tool provides several functions: a) skin image classification by using Deep Learning neural networks such as AlexNet, GoogLeNet and so on; b) skin image search by using Gabor Wavelet Transform, Principle Components Analysis, Gray-Level Co-Occurrence Matrix; c)skin live image analysis in real time which allows RBG calculations, as well as face detection, eye detection and upper body detection. This can program can work on a range of skin images, such as skin digital images, skin capacitive images, skin ultrasound images, and even X-ray images!

For more details, please read out paper titled "The Development of a Skin Image Analysis Tool by Using Machine Learning Algorithms", submitted to Cosmetics — Open Access Journal (https://www.mdpi.com/journal/cosmetics).
# Download and Installation
1. Go to the "Download.txt" file, use the link to download the MATLAB App Installer file called "LSBU Skin Image Analysis.mlappinstall", and save it in a local directory.
2. In MATLAB, go to the directory, double click the file to install it in your MATLAB App tab.
![Download and Installation](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/install.jpg?raw=true)
3. From your MATLAB App tab, double click the "LSBU Skin Image Analysis" icon to run.
![Run the Program](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/run.jpg?raw=true)
# Skin Image Classification
1. Training
Click the "Train NN" tab in the program, first select the folder where your training data is, your images should put into several subfolders, and subfolders names will be used as classification label, then select the Deep Learning model (AlexNet, GoogLeNet etc.), click "Train" button, this might take a few minutes to a few hours, depends on the data size, model and your computing power. But for each data folder, you only need to train once.
![Training Deep Learning Neural Networks](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/train.jpg?raw=true)
2. Classification
Once you have trained the model, click the "Classify" tab, select a model (e.g. Transferred AlexNet, Transferred GoogLeNet etc), click the "Classify a image" button, select a skin image to classify. You can also tick the "Use Webcam" button to get the query image from a Webcam. Transferred AlexNet and Transferred GoogLeNet are the models trained on your images, while AlexNet and GoogLeNet are pretained models for images defined in ImageNet (http://www.image-net.org/).
![Skin Image Classification](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/classify.jpg?raw=true)
# Skin Image Searching
Click the "Search" tab in the program, first select the folder where your image is, then select the search method, Gabor, PCA or GLCM, click "Update Image Database" button, this might take a few minutes to calculate the feature vectors of all the images. You only need to do this once. Click "Search Image Database" button to select a image file to search the images, it will return with the best matching image, and 2nd, 3rd, 4th and 5th best matching images. You can also tick the "Use Webcam" button to get the query image from a Webcam.

The search results of skin cancer images.
![Skin Image Searching](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/search1.jpg?raw=true)
The search results of skin ultrsound images.
![Skin Image Searching](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/search2.jpg?raw=true)
The search results of X-Ray chest images.
![Skin Image Searching](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/search3.jpg?raw=true)
The search results of skin capacitive images.
![Skin Image Searching](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/search4.jpg?raw=true)
# Skin Live Image Analysis
Click the "Analyze" tab in the program, tick the "Use Webcam" button to get the live image from a Webcam, select a filter from dropdown list, you can select grayscale, red channel, green channel, blue channel and custom. In Custom filter, you can manually specify RGB channel caculations. Also in the filter, you can choose face detection, eye detection and upper body detection. Make sure to tick "Analyze" checkbox to activate the filter.

This shows the original skin image and the Blue channel image.
![Skin Live Image Analysis](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/live1.jpg?raw=true)
This shows the original skin image and the Green channel image.
![Skin Live Image Analysis](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/live3.jpg?raw=true)
This shows the original skin image and the Red channel image.
![Skin Live Image Analysis](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/live4.jpg?raw=true)
This shows the original skin image and the image of Blue x 0.7 + Green x 0.7, no Red channel.
![Skin Live Image Analysis](https://github.com/PerryXiao2015/LSBU-Skin-Image-Analysis-Tool/blob/master/live2.jpg?raw=true)
