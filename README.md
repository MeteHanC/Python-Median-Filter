# Python Median Filter Implementation
A simple implementation of median filter in Python3.

# Median Filter Usage
Median filter is usually used to reduce noise in an image. We will be dealing with salt and pepper noise in example below. Median_Filter method takes 2 arguments, Image array and filter size.
Lets say you have your Image array in the variable called img_arr, and you want to remove the noise from this image using 3x3 median filter. Thats how you do it.

```
removed_noise = median_filter(arr, 3)
```

For 5x5 median filter, you just need to change the second argument to 5, and so on.

#Example

###### You see a noisy image -corrupted by salt and pepper noise- below. We will run the code and try to remove the noise from the image. 

<p align="center"><img src="https://raw.githubusercontent.com/MeteHanC/Python-Median-Filter/master/Screenshots/noisyimg.png"/></p>

###### After running our code with using 3x3 median filter, this is the result we got.

<p align="center"><img src="https://raw.githubusercontent.com/MeteHanC/Python-Median-Filter/master/Screenshots/removed.png"/></p>





