# Arbitrary Neural Style Transfer using Pretrained Models

Google's Magenta project provides pre-trained models for real-time style transfer using arbitrary images and styles. 
[Check out the full repository here.](https://github.com/magenta/magenta/tree/master/magenta/models/arbitrary_image_stylization)

In addition to the model, I set up a specific directory structure to match my images. This folder is called `Selfies` and is at the root of my google drive. The structure is as follows:
```
Selfies/
    output/
      # Output files will be stored here
    styles/
      style-0.jpg
      style-1.jpg
      style-2.jpg
      style-3.jpg
      style-4.jpg
      style-5.jpg
      style-6.jpg
      style-7.jpg
    videos/
      video-1.mp4
    pictures/
      img-1.jpg
      img-2.jpg
      ...
```

The photos in the `pictures` directory can have any number of images and any filename as long as the extension is `.jpg`. 

The code in this colab notebook evaluates 8 styles on the video `video-1.mp4`.
[Check out the Colab Notebook Here](https://colab.research.google.com/drive/19tVBH6bWBaSjXPrV70rPeJOp0yTqQ0v8?usp=sharing).
