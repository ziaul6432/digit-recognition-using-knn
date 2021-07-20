
# Recognition of Handwritten Digits using K -nearest Neighbors

Digit recognition system is the machine to train in recognizing the digits from different sources like emails, bank cheque, papers, images, etc.
and in different real-world scenarios for online handwriting recognition on computer systems, recognize number plates of vehicles, processing bank cheque amounts,
numeric entries in forms filled up by hand and so on



MNIST Dataset
 - MNIST(Modified National Institute of Standards and Technology)dataset contains total of 70,000 handwritten digits labeled images from 0 to 9.

- Handwritten digits are images in the form of 28*28 gray scale intensities of images representing an image along with the first column to be a label (0 to 9)
  for every image.
  
  
  ![0_pVowHZmGmmUElRX6](https://user-images.githubusercontent.com/57566639/126276858-32f25f18-c753-45e7-bd76-d359ac77038c.png)
  
  
  
  
  
  # Implementation of KNN from scratch
1-Compute the Euclidean distance between the test data point and all the training data .
2-Sort the calculated distances in ascending order .
3-Get the k nearest neighbors by taking top k rows from sorted array
4-Find the majority class of these rows .
5-Return predicted class.
6-Finding accuracy score to make sure the prediction is correct or not.

