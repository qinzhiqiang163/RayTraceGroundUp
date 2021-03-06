# RayTraceGroundUp
This renderer is based on the original source code of  the book named Ray Tracing From The Ground UP.  
I extended it from the following aspects.  
**Objects**: part of sphere, part of tori, globe, and so on.  
**Tessellation**: sphere, horn, rotational sweeping surfaces, bezier patches (Utah teapot).  
**2D** **texture**: solid cylinder checker, sphere checker.  
**Scene** **building**: several scenes were built and the corresponding resultant images were produced.  

Some of the resultant images were put in the folder ./results/picture  

The default settings is to render the fifth scene, which is the most complicated one of the scenes.  
If you want to render other scenes, you can modify the Macro, ChapterNum, in BuildShadedObjects.cpp to produce corresponding images.  

If you can read simple Chinese, you could find more details in my blog: https://blog.csdn.net/libing_zeng/article/details/72625390  
If you have any question to share with me, you can reach me by email: libingzeng123@gmail.com  

![1.1](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/1.1-Tessellation-horn%2C%20sphere.jpg)
![1.2](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/1.2-Tessellation-bezier%20patches%2C%20rotational%20sweeping%20surface.jpg)
![2.1](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/2.1-2D%20Checker-sphere%2C%20cylinder.jpg)
![3.1](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/3.1-Scene1.jpg)
![3.2](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/3.2-Scene2.jpg)
![3.3](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/3.3-Scene3.jpg)
![3.4](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/3.4-Scene4.jpg)
![3.5](https://github.com/libingzeng/RayTraceGroundUp/blob/master/results/picture/3.5-Scene5.jpg)
