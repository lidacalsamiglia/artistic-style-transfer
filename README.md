# Artistic Style Transfer
*Authors: Lida Calsamiglia 231319, Patricia Castelijns 229651, Pau Cobacho 216834*

This is our final project of Deep Learning. Artistic Style Transfer (Neural Style Transfer) is a technique that takes an image and outputs that image with a determined artistic style. We follow the Neural-Style algorithm developed by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge (https://arxiv.org/pdf/1508.06576.pdf).  
<div align="center">
    <img src="data/sea.jpg" width="300" height="200">
    <img src="data/sea_vangogh.png"  width="300" height="200">
</div>

In this project we use a pretrained VGG model from pytorch and implement color preservation and masking to the generated images. We also do some modifications to achieve two style transfer. Throughout the provided ipynb notebook you can see the obtained results and the different outputs modifying parameters. We worked with Google Collab so if you want to run this notebook in your computer be sure to have the necessary libraries installed and do the necessary modifications (e.g. image loading). 
