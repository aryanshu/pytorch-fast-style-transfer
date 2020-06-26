
# Implementation of Fast neural Style transfer with Pytorch
The neural style trasnfer implemented in this project is based on the paper <b>Perceptual Losses for Real-Time Style Transfer and Super-Resolution</b> by Fei-Fei Li. which was an extension of the <b>"A Neural Algorithm of Artistic Style"</b> by Gatys et al., originally released to ArXiv 2015 , but it was limited to images only due to slow processing of images. 

## Archietecture
The proposed model architecture is composed of two components:
`1. Image Transformation Network `<br>
`2. Loss Network `<br>

<p align="center">
	<img src = 'dataset-for-traning-loss-network(Empty)/fast_style_transfer.jpg' width =800> 
</p>

### Image Transformation Network:

The Image Transformation Network is a deep residual Convolutional Neural Network which is trained to solve the optimization problem proposed by Gatys.Given an input image (x) this network transforms it into the output image (ŷ).

<<<<<<< HEAD
### Loss Network:
The Loss Network(Φ) is a pretrained VGG16 on the ImageNet Dataset.The loss network is used to get content and style representations from the content and style images.


## Results
## Applying style transfer on images

*Content* | *Style* | *Style Transfer* 
:---: | :---: | :---: | 
<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px'> | <img src = 'style-images/Mandalorian.png' width ='300px' height='200px'> |  <img src ="output-images/Mandalorian.jpg" width="300px" height='200px'>
<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px'> | <img src = 'style-images/rain-princess.jpg' width ='300px' height='200px'> |  <img src = "output-images/rain-princess.jpg" width="300px" height='200px'>
<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px' > | <img src = 'style-images/spider-verse.jpg' width ='300px' height='200px'> |  <img src ='output-images/spider-verse.jpg' width ="300px" height='200px' >
<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px' > | <img src = 'style-images/udnie.jpg' width ='300px' height='200px'> |  <img src = "output-images/udine.jpg" width="300px" height='200px'>

## Applying fast style transfer on videos

*Content* | *Style* | *Style Transfer* 
:---: | :---: | :---: | 
<img src = 'Input(content) video/input_video.gif' width ='300px' height='200px'> | <img src = 'style-images/Mandalorian.png' width ='300px' height='200px'> |  <img src ="output-videos/output_videos/Mandalorian.gif" width="300px" height='200px'>
<img src = 'Input(content) video/input_video.gif' width ='300px' height='200px'> | <img src = 'style-images/rain-princess.jpg' width ='300px' height='200px'> |  <img src = "output-videos/output_videos/rain-princess.gif" width="300px" height='200px'>
<img src = 'Input(content) video/input_video.gif' width ='300px' height='200px' > | <img src = 'style-images/spider-verse.jpg' width ='300px' height='200px'> |  <img src ='output-videos/output_videos/spider-verse.gif' width ="300px" height='200px' >
<img src = 'Input(content) video/input_video.gif' width ='300px' height='200px' > | <img src = 'style-images/udnie.jpg' width ='300px' height='200px'> |  <img src = "output-videos/output_videos/udnie.gif" width="300px" height='200px'>
=======
*Content* | *Style* | *Style Transfer* 
:---: | :---: | :---: | 
<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px'> | <img src = 'style-images/Mandalorian.png' width ='300px' height='200px'> |  <img src ="output-images/Mandalorian.jpg" width="300px" height='200px'>

<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px'> | <img src = 'style-images/rain-princess.jpg' width ='300px' height='200px'> |  <img src = "output-images/rain-princess.jpg" width="300px" height='200px'>

<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px' > | <img src = 'style-images/spider-verse.jpg' width ='300px' height='200px'> |  <img src ='output-images/spider-verse.jpg' width ="300px" height='200px' >

<img src = 'input(content) images/input_image.jpg' width ='300px' height='200px' > | <img src = 'style-images/udnie.jpg' width ='300px' height='200px'> |  <img src = "output-images/udnie.jpg" width="300px" height='200px'>
>>>>>>> 42e4b14e5c24aaaacb08ce8c8426e4ac541d9fdc
