# K-Nearest-Neighbours-Implementation-in-Python
 This project is the implementation of K-Nearest Neighbours Algorithm in Python. It takes the image from user as input and compares it to a dataset of 50 images by finding Eucledian distances. Then, it chooses the top 1 (or 3 or 5 depending on the value of k) distances and returns the character which resembles the most to the user's immage based on majority voting.
 
 Try running this code, give it your image by passing the directory and check which celebrity you resemble the most. Don’t be surprised as you may observe gender change!!!
 ## Project Includes
 1. KNN.ipynb python 3 notebook containing the code
 2. data.mat file containing a 50x3072 array of uint8s. Each row of the array stores a 32x32 colour image. The first 1024 entries contain the red channel values, the next 1024 are green, and the final
1024 are blue. The image is stored in row-major order.
