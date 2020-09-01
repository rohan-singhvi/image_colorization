# image_colorization
This is a program that allows black and white coloured images to be colorised again through ideas of deep learning and some colour theory (RGB and Lab). This uses OpenCV as the deep neural network with DNN architecture which is trained on ImageNet dataset. For colorizing black and white images we will be using a pre-trained caffe model, a prototxt file, and a NumPy file.

wget https://github.com/richzhang/colorization/blob/master/colorization/resources/pts_in_hull.npy?raw=true -O ./pts_in_hull.npy\
wget https://raw.githubusercontent.com/richzhang/colorization/master/colorization/models/colorization_deploy_v2.prototxt -O ./models/colorization_deploy_v2.prototxt
wget http://eecs.berkeley.edu/~rich.zhang/projects/2016_colorization/files/demo_v2/colorization_release_v2.caffemodel -O ./models/colorization_release_v2.caffemodel
