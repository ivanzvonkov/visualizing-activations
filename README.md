# Visualizing Activations

This repository contains a notebook for visualizing activations of a VGG-13 neural network.

### Example using activations from 20th channel of 5th layer

**Images with most activation**

<img src='assets/activated-images.png' width='50%'>

**Activations from most activated images**

-   dark = less activated, light = more activated
-   it appears that this channel activation detects red edges
    <img src='assets/activations.png' width='50%'>

**Images with activated pixels brightened**

-   The red edges are indeed highlighted when the images are combined with the activations

    <img src='assets/images-with-activation.png' width='50%'>

**Optimizing random noise to generate activation**

-   Opimizing random pixels to generate a high activation yields red lines further confirming that this channel helps determine red edges

    <img src='assets/optimizing-noise-on-activation.png' width='70%'>

### Example using church class activation

-   Optimizing random pixels to activate the class that represents a church yields images with certain characteristics of churches (chapels, windows)

    <img src='assets/optimizing-noise-on-churches.png' width='70%'>
