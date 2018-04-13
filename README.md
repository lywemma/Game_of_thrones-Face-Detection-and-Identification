# Game_of_thrones-Face-Detection-and-Identification

Besides image classification, face detection and recognition are super useful for business. By training images of human faces, retailers could recognize new and returning customers. With this technique, we could identify the demographics of the customers such as Age and Gender, helping retailers better profile and target their customers.

In this case, I used Images from Game of Thrones. 

First, I used a pre-trained model to detect faces. I tested the results with several group photos, and it could detect all the faces successfully.

Next, I downloaded 5 Game of Thrones characters' photos (including 'Arya_Stark', 'Cersei_Lannister' , 'Daenerys_Targaryen' , 'Jon_Snow',  'Tyrion_Lannister'). Photos were downloaded from Google Images using "Fatkun Image Downloader". In the training set, I have 76 photos in total. I trained the model to detect and recognize these characters.

Finally, I picked several photos from the testing set, which weren't included in the training set. This app recognized the characters correctly.

Code and Results see: [Game_of_thrones-Face-Detection-and-Identification](https://github.com/lywemma/Game_of_thrones-Face-Detection-and-Identification/blob/master/Face_Detection.ipynb)

reference: https://www.superdatascience.com/opencv-face-recognition/