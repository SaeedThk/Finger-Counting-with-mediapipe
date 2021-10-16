# Finger Counting using hand tracking with MediaPipe 

### Mediapipe
---
MediaPipe is a cross-platform framework for building multimodal applied machine learning pipelines.
MediaPipe Hands utilizes an ML pipeline consisting of multiple models working together: A palm detection model that operates on the full image and returns an oriented hand bounding box. A hand landmark model that operates on the cropped image region defined by the palm detector and returns high-fidelity 3D hand keypoints. This strategy is similar to that employed in our MediaPipe Face Mesh solution, which uses a face detector together with a face landmark model.
![capture](https://s21.picofile.com/file/8442372750/21_landmark.png)
Hand Tracking model from media pipe. Each hand is having landmarks comprise of 21 points. Goal is to count fingers in the right hand. First stored tip id of fingers in list. Next compare the co-ordinates to check whether finger is open or close. If open, append 1 in list and for close fingers append 0 in list. At last count total fingers and dispay it using its corresponding image.

A quick video from project
---
![capture](https://s20.picofile.com/file/8442372584/Finger_counting.mp4.html)
![A](docs/docfx/images/MixtureOpen.gif)
![B](https://s20.picofile.com/file/8442372584/Finger_counting.mp4.html)
### project video
---
##### To see the complete project video click on the link below:
***https://youtu.be/5oxNreahWdg***

### License Information
---
This product is open source!

So, Feel free to download, use or make any changes you like to this file
Also, you can contact me with email, instagram and telegram to talk about it.
+ Email: Saeedtajikhk@gmail.com
+ Instagram: saeedthk
+ Telegram: SaeedThk

Your friend Saeed Tajik Hesarkuchak.
