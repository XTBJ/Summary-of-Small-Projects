### Challenge
Using fundamental knowledge of digital image processing, rather than end-to-end training, 
the car achieve real-time tracking of dynamic targets in situation where the background color is similar to the target color. 

### Method
We combine color segmentation and optical flow for real-time tracking of dynamic target. 
The algorithm is complemented in C++ language and utilize OpenCV library. 
We perform color threshold segmentation based on HSV color model. 
Besides, optical flow is employed to optimize the tracking algorithm for the application scenario involves constant brightness and small motions. 
Finally, we use mean shift algorithm for target tracking and drive a two-wheeled vehicle on the Dashgo platform to achieve real-time tracking of leg target.

https://github.com/user-attachments/assets/27cc8312-9c81-47c1-b51d-001a220c271c

