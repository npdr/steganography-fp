# Frequency domain based image steganography
## Students
* Fabiana Dalacqua
* Lucas Yamamoto
* Pedro Henrique Nieuwenhoff

## Objective
The goal of this project is to use image processing techniques to hide discreetly data inside a given digital image.
There are various methods to achieve this goal. The one used is a frequency domain based (Fourier Transform)
method, which transforms the input images into a frequency domain and merge them, creating an output image. </br>

This output image will appear to be just the regular input image, but we can recover the information we put in before by decoding,
using a similar method.

![plot](./images/diagram.png)

### Example
Input Images
<p float="left">
  <img src="https://github.com/npdr/steganography-fp/blob/main/images/input.jpg" height="250" width="250">
  <img src="https://github.com/npdr/steganography-fp/blob/main/images/qr.png" height="250" width="250">
<p>
  
Output Image
<p float="left">
  <img src="https://github.com/npdr/steganography-fp/blob/main/images/input+qr.png" height="250" width="250">
<p>



