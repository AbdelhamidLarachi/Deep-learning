
## 1 - Binary classification 

The company wanting to automate the selection of photos for annotations, deliverable 2 will have to provide a classification method based on neural networks in order to filter images that are not photos from the starting dataset. The solution may be based on the neural network architecture of your choice, which you will justify in particular from the point of view of the obtained results. 

[![Classification](https://i.ibb.co/QX400HT/classification.png "Classification")](https://i.ibb.co/QX400HT/classification.png "Classification")

## 2 - Image processing  (denoising)

The goal is to process a set of photographs in order to make them better processable by Machine Learning algorithms. The processing to be performed is a denoising operation. You will need to produce a Jupyter notebook explaining these preprocessing steps, and their performance. These algorithms will rely on convolution auto-encoders, and apply them to improve image quality. 

[![denoising](https://i.ibb.co/PhMHn8G/Screen-Shot-2022-01-21-at-12-13-54-PM.png "denoising")](https://i.ibb.co/PhMHn8G/Screen-Shot-2022-01-21-at-12-13-54-PM.png "denoising")
## 3 - Image captioning 

This deliverable concerns the last stage of the required processing. The goal is to create a neural network that generates captions for photographs, based on the MS COCO dataset dataset. The network will consist of two parts, the CNN part which encodes the images into an internal representation, and the RNN part uses this representation to predict the annotation sequence by sequence. Before training the model, the images are pre-processed by a pre-trained CNN for classification. 

[![captioning](https://i.ibb.co/9gtwTSG/Screen-Shot-2022-01-21-at-12-18-19-PM.png "captioning")](https://i.ibb.co/9gtwTSG/Screen-Shot-2022-01-21-at-12-18-19-PM.png "captioning")
