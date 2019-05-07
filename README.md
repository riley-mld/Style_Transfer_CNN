# Style Transfer

This project was done as part of the [Udacity's PyTorch Scholarship Challenge from Facebook](https://www.udacity.com/facebook-pytorch-scholarship). as part of this project I'll recreate style transfer method that is outlined in the paper, [Image Style Transfer Using Convolutional Neural Networks, by Gatys](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) in PyTorch.

![Trained Agent][image1]

Style transfer relies on separating the content and style of an image. Given one content image and one style image, we aim to create a new, _target_ image which should contain our desired content and style components:
* objects and their arrangement are similar to that of the **content image**
* style, colors, and textures are similar to that of the **style image**

An example is shown below, where the content image is of a cat, and the style image is of [Hokusai's Great Wave](https://en.wikipedia.org/wiki/The_Great_Wave_off_Kanagawa). The generated target image still contains the cat but is stylized with the waves, blue and beige colors, and block print textures of the style image!

<img src='notebook_ims/style_tx_cat.png' width=80% />

## Results
### Style Image:
<p align="center">
  <img width="500" src="images/delaunay.jpg">
</p>
### Feature Image:
<p align="center">
  <img width="500" src="images/janelle.jpg">
</p>
### Results:
<p align="center">
  <img width="500" src="images/result.jpg">
</p>


