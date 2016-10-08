#ROSCON Day 1 (1)

## Whats new in Gazebo

they do the powerpoint in gazbo....

1. dynamic simulator of robots in indoor/outdoor environment, working with TOS.

2. several use cases with video

3. dependencies

4. design goals

5. user center IDP

5. New Features

    5.1 better world

        hight map DEM

        actors

        roads

        nested model

    5.2 better control

        axis when rotating/translating

        undo movemnet

        switch from top/buttom view

    5.3 introspection visualizatinos (physics engine)

        linksFrames

        jointsFrame

        collisions

        center of mess of every link

    5.4 building editor according to 2D map directly

        models of buildings

        wall/ window

    5.5 model editor

        join model / overview of model

    5.6 plotting tool

        dynamic seraching and drag data into viewer, powerful as yiyi's viewer. :p

    5.7 sensor support

        multi / wideangle/ depth camera, gps ,alimeter, sonar, logical sensor, sensor noise, etc.

    5.8 log with GUI

    5.9 screen capture video

    5.10 several new plugins

    5.11 hardware integration

        oculus vr, optitrack, 3D glasses

6 what's next

    terrain editor

    visual redesign

    GUI console

    Graphical tools to physics valid

## ROS2 update

1. Goal

    bare-metal micro controller, and several other unimportant features

2. DDS as said in design doc, lossy network.

    >http://design.ros2.org/articles/ros_on_dds.html

    |user Code|

    |DOS client libraray API|

    |ROS milldeware API for DDS A or B or C or ...| (paired adapter)

    |DDS implementation A or B or C or ...|

3. changes since ROSCON2015: user-facing

    windows update/ FAST RTPS/ python library update/ arm support/ wait\_for\_service node / turtlebot demo

4. ROS client libraries

    >http://design.ros2.org/articles/ros_middleware_interface.html

    |User Code|

    |rclcpp, rclpy, rclcs, rcljava| (rcl means ros client library)

    |ROS client library|

    |ROS middleware interface|

    |DDS vendor|                            <--ddl-->                |Another DDS| (^ then from bottom to top)

    (talker down, the subscriber listen from downside)

5. porting experience

    catkin(ROS1) <--> ament(ROS2)

    similar -> mix -> together -> be one build tool

6. roadmap

    beta1 o ROS 2 end of this year

    _Let's move dji_sdk_ros to ROS2!_


## APC Champion

    sorry my laptop has no power :(

1. moveit is suitable for pick and place pipeline for an industrial 'boxpacking' task

2. simple and clear system architectture:

    sense -. plan -> act


---

I jumped over about three talks in order to charge my laptop = =

---

## Trutle Bot III

They come here to sell products.

1. a highly packaged hardware PCB

2. a SLAM demos

3. modular and can install components in different format, car, tank, beast with leg, 2 wheel car, omni wheel car

4. can 3D print any mechanical component

## Here comes the Intel RealSense!

1. selling how good their robot platform and develop kit is

2. still selling

3. keeps selling

4. they don't know what Yuneec is

5. GG

## Hardware-ROS

1. a standard hardware interface

2. modular components, including sensors, communicator and actor. all work as different ROS nodes that can connect to ROS network

3. have DDS inside, not bare-metal problem, no core needed.(at least as the speaker told me)

4. interesting, should be a future direction of ROS products.

---
A summery over all:

abstract layer, abstract layer, abstract layers of abstract layers.

everything stays the same since software was invented  LOL

(please read _dreaming in code_ if you haven't, the third chapter(?), as I remember.

## several three-minutes speakings from various organizations

nothing to record

