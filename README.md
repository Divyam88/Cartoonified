# Cartoonified

This project aims to convert regular images into cartoon-like representations using image processing techniques.The project uses Cv2, matplotlib, and numpy to convert an image into its cartoonised image. 

It is done by creating edge mask of the image and creating a blurred version of the image. Then, superimposition the two image obtained before.

# Creating an edge mask of the image:
  * Convert the color scheme from BGR To Gray
  * Create a blur image by using medianBlur()
  * Using adpative Threshold which adjusts the threshold value
    
# Creating blurred version:
  * Firstly, We reduce the color palette
  * Reduce the noise using Bilateral filter is used which is one of the prominent filter technique.

  


