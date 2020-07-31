<h2>Visualizing image-specific class saliency map in classification ConvNets in Pytorch</h2>

Recently I started to explore pytorch framework for creating deep learning models. Having worked with tensorflow for past few years, I found myself spending most of the my time just to figure out how to do 'X'. Although tensorflow is great for productionizing ml models, I wished to have a framework which would help me to express my ideas easily in code for faster prototyping. I was pleasently surprised by the fact that how easy pytorch makes it to express your ideas in code and run experiments. After going through the basics of pytorch I decided to implement the image-specific Class Saliency Visualisation method as described in https://arxiv.org/abs/1312.6034.

Saliency refers to what’s noticeable or important in an image. In context of convolution neural networks Saliency map for an image represents the important pixels in the image that influence class score of the prediction of network.