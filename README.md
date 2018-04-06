# Emotion-Detection-Using-AI
In this evolutionary world, human’s likely to exhibit their emotions in the form of images rather than text. And analysing emotions from the text processing has been an ordinary thing till now. Analysing emotions from text there is a chance to fool the algorithm. So, we would like to analyse emotions from the image where Humans can not fool the algorithms with their images as input.  

Initially the image is analysed with the help of opencv and with some python packages like Numpy, Scipy, Dlib, Matplotlib, Scikit- learn, Scikit- image  with the predictions of seven emotions like Anger, Contempt, Disgust, Fear, Happy, Sadness, Surprise. 
	
 We use landmark file for detecting facial structure key points in face regions like Mouth, Right eyebrow, Left eyebrow, etc.. And these results will be send to the where we 
used Euclidean algorithm which is used to find out the distance between the points based on 
the point indices taken from the landmark file.
	
  The  traindata file,  pca(principal component analysis) file  along  with the point indices will be given to the opencv, and the output generates emotion of the image.
