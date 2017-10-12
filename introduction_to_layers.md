Layer 
=====================================
## Goals
  - Understanding basics of the layer and how it works by lookig at layer in 01_logistic_regression.sdcproj which is the simplest one as a example.  

## What is Layer ?

> layers and their properties that can be used with the Neural Network Libraries.  

> Reference [Layer reference](https://support.dl.sony.com/391/)

Look at the layer below.

![](images/01_logistic_regression.sdcproj_layer.png)

- **input** 
  - Dataset
    - Specifies the name of the variable to input into this Input layer.
  - size
    - Specifies the input size.
For image data, the size is specified in the “the number of colors,height,width” format.
      - For example, for a RGB color image whose width is 32 and height is 24, specify “3,24,32”. For a monochrome image whose width is 64 and height is 48, specify “1,48,64”.  
  
- **Affine**
  - The affine layer is a fully-connected layer that has connections from all inputs to all output neurons specified with the OutShape property.  
o = Wi+b  
(where **i** is the input, o is the output, **W** is the weight, and **b** is the bias term.)  
[affine transformation](https://en.wikipedia.org/wiki/Affine_transformation#Representation)
