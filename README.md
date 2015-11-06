# IOS-lane-Detection

##Title:
Real Time Lane Detection
##members:
Yujun Wang(Andrew ID: yujunwan) Juedou Liu(Andrew ID: juedoul)
##Summary:
We want to detect road lane in real time video. Because opencv hough transformation is slow. We want to find a fast way to do it on mobile devise.
##Background:
 We will use descriptors to detect yellow and white road lines.Then use hough transformation to mark the lane area in the video. We will take advantage of OpenGL ES GPUImage package to accelerate the computing speed.
 
##The challege:
This problem can be solve in openCv easily. However, the hough transformation basicly took a lot of time. And it's hard to do it in real time without dropping frames or resize the image to a much smal    ler one. We are trying to implement this on a mobile device at a relative fast speed.  
Sloving this problem in mobile platform means a lot. It further can be combine with GPS and IMU to do Vision SLAM, and this can be used on map navigation app. Because map navigation app, like google m    ap, sometime is ambiguity even with animation.  
##Goals & Deliverables:
###Plan to do:
                                                                                                                                                                                                           
