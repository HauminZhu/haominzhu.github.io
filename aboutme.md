---
layout: page
title: ""
subtitle: Robotics | Computer Vision | Learning | Mechatronics
---
## Reserch and Projects
> ### A journey of a thousand miles begins with a single step. 
> #### 不积跬步无以至千里

### Event-based Camera Model with Conditional Adversarial Networks (ongoing)
> Conditional GAN for event-based camera model generation. Details are upcoming.

### Quadrotor Localization and Control Based on VIO and Single Apriltag
[![apriltag](http://img.youtube.com/vi/SXhylsI6tZY/0.jpg)](http://www.youtube.com/watch?v=SXhylsI6tZY "apriltag")
> In this project, I developed the VIO based algorithm using single apriltag to do quadrotor global localization. Also we control the quadrotor based on the the global frame aligning with the apriltag. At the very beginning, before the quadrotor detects the apriltag and defines the global frame, it can only go to relative position based on takeoff frame. After it detects the apriltag, it can go to global position based on that. And every time it sees the apriltag again, it can refresh and correct its global position. Using this way, we no more need big motion capture system and can do outdoor job better.

### Fully Connected Network Based Loop-closure Simultaneous Localization and Mapping
[![FCNSLAM](http://img.youtube.com/vi/UbIvX2wLOx0/0.jpg)](http://www.youtube.com/watch?v=UbIvX2wLOx0 "FCNSLAM")
> In this project, we focus on using loop closure to improve the performance of SLAM. We train a Fully Convolution Network (FCN) to segment the scene. Then we conduct loop detection through two approaches: the first approach is based on comparing patterns in the images recognized from the segmentation results; the second approach is based on comparing the feature maps extracted from the last convolutional layer in the FCN. After detecting the loop, we conduct local scan matching to obtain the optimal loop closing pose. Comparing this optimal pose with corresponding pose from original SLAM process, we derive the pose error in loop closing point. Finally, we backpropagate the error back to optimize the trajectory, and re-estimate the map. From the results, we can see that our loop closure pipeline has satisfactory performance. More details can be found [**HERE**](https://docs.google.com/presentation/d/1LXZBWzL3knhRaRUoEIvMcnIDkkwjKsgEsluMrY89CKI/edit?usp=sharing).

### Omni-bearing Mobile Chassis Control and Localization (ABU ROBOCON 2014)
[![ROBOCON2014](http://img.youtube.com/vi/GRFTnDMXKEM/0.jpg)](http://www.youtube.com/watch?v=GRFTnDMXKEM "ROBOCON2014")
> The [ABU Robocon 2014](https://www.youtube.com/watch?v=GchwbtfqDzc) was conducted on 24 August 2014 at Pune, India. The Theme for Robocon 2014 declared by India was "A Salute for Parenthood". As a member of competative robotics lab of USTB, I participated in manually and automatic robots design, building. We built one manully controlled 'mother' robot which can holds the fully-automatic 'baby' robot to different mission fields and let the 'baby' automatically finish required tasks. I also took charge of the related student research training program of omni-bearing mobil chassis design and control algoithm development which is used on 'mother' robot.

### Unscented Kalman Filter Based Robot Orientation Estimation and Scene Panorama
[![UKF10](http://img.youtube.com/vi/YZcB-QJcKUk/0.jpg)](http://www.youtube.com/watch?v=YZcB-QJcKUk "UKF10")

> In this project, I implemented an UKF algorithm that estimates the 3D orientation (roll, pitch, yaw) of robot using data from gyroscopes and accelerometers, we will estimation the underlying 3D orientation by learning the appropriate models parameters from the ground truth given by a Vicon motion capture system. And then using estimation to generate a real-time panoramic image from camera. More detalis can be found [**HERE**](https://drive.google.com/file/d/1o5SvcSBA19LULOKvvoPVM_jdCfaBRu-j/view?usp=sharing).

### Robockey 2016 of Penn
[![ROBOCKEY](http://img.youtube.com/vi/-ZKGABq9zFw/0.jpg)](http://www.youtube.com/watch?v=-ZKGABq9zFw "ROBOCKEY")
> [Robockey](http://medesign.seas.upenn.edu/index.php/Courses.MEAM510-12C-ROBOCKEY) is final project for MEAM510 Mechatronics System and Design at Penn. It's an annual tournament at Penn. Over the course of six weeks we designed, prototyped, built, and tested a team of three robots to autonmously play hockey. Our team-17 won the second place in the final contest among 30 teams. I took charge of the design of all tree different hockey robots and help develop the control algorithm of them.

### Particle Filter Based Simultaneous Localization and Mapping
[![SLAM](http://img.youtube.com/vi/pIXTOGjYGwI/0.jpg)](http://www.youtube.com/watch?v=pIXTOGjYGwI "SLAM")

(Irrelavent to the project, just a show of same type robot used in this project)
> In this project, I implemented a particle filter based SLAM Using data collected by a humanoid robot, THOR-OP. The sensors in the robot used in this project are IMUs, a 2D laser range finder(LIDAR), which are used for SLAM, and an RGBD camera(Kinect), which is used for ground detection and texture mapping. This project utilized the Monte Carlo probabilistic localization to update the robot pose and built an occupancy map. After the robot odometry and map have been updated, we can then use images and depth information from RGBD sensor to build the full textured map. More details can be found [**HERE**](https://drive.google.com/file/d/16IkqVXOwycFfrLx0UPp3M5D0AOkudBLr/view?usp=sharing). This is a naive version of SLAM, I improved the result of this project in another project FCN based loop-closure SLAM.

### ABU ROBOCON 2015
[![ROBOCON2015](http://img.youtube.com/vi/D9vJPjMSstM/0.jpg)](http://www.youtube.com/watch?v=D9vJPjMSstM "ROBOCON2015")

The [ABU ROBOCON 2015](https://www.youtube.com/watch?v=XiAct2sre-M) was held in August in Yogyakarta, Indonesia. The contest theme was "Robominton-Badminton RoboGame".

### Color Segmentation and Object Detection Based on Gaussian Mixture Model
TODO


### Hidden Markov Model Based Gesture Recognition
TODO



