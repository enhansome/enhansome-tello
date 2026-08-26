# awesome-tello with stars

[Tello drone](https://www.wikidata.org/wiki/Q105554279) is a wifi controlled RTF drone, developed by  by RYZE Robotics Shenzen in cooperation and sold by DJI technology. This features different models: [Tello](https://www.ryzerobotics.com/en/tello), [Tello EDU](https://www.ryzerobotics.com/en/tello-edu), RoboMaster TelloTalent, and extended kits like [battery Booster](https://m.dji.com/de/product/tello?vid=45701) or 4x drone swarm.

This is a list of Free Software that can be used esp. with this drone. Get closed source [official downloads](https://www.ryzerobotics.com/de/tello/downloads) like docs, apps, ... .

## Cockpits

Alternatives to official Android Tello apps

* [Drone-keyboard](https://github.com/dnomak/drone-keyboard) ⚠️ Archived - controll & videostream, `#nodejs`
* [Telloterm](https://github.com/SMerrony/telloterm) ⭐ 46 | 🐛 0 | 🌐 Go | 📅 2023-04-11 - controll & videostram & gamepad (fka. tello-desktop), `#Go`
* [Drone-control](https://github.com/socketbind/drone-control/) ⭐ 27 | 🐛 3 | 🌐 Go | 📅 2020-02-15 - `#Go`
* [Tellodesk…](https://github.com/SMerrony/tellodesk) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2019-03-13 - controll & videostream & gamepad & map, `#Go`
* [Tello](https://tellopilots.com/threads/new-app-for-linux.5692/) - Linux GTK App, `#C`
* [Kirogi](https://invent.kde.org/utilities/kirogi/)- KDE App, different types of drones

## Scripting

Alternatives to official Android Tello Edu app or [Droneblocks](https://www.droneblocks.io/) to design batch or interactive automation for the drone.

* [Node-Red-Tello-Control](https://github.com/johnwalicki/Node-RED-Tello-Control) ⭐ 127 | 🐛 8 | 📅 2021-02-05
* [Scratch3-tello](https://github.com/kebhr/scratch3-tello) ⭐ 98 | 🐛 5 | 🌐 JavaScript | 📅 2026-03-11
* [Node-Red-DroneViewer](https://github.com/johnwalicki/Node-RED-DroneViewer) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2019-12-16
* [Scratch explained](https://hackaday.com/2018/05/22/scratch-your-itch-to-fly/) with the official extension

## SDK Wrappers

Tello features official interfaces to develop applications for control & video streaming:

* [SDK 1.3](https://terra-1-g.djicdn.com/2d4dce68897a46b19fc717f3576b7c6a/Tello%20%E7%BC%96%E7%A8%8B%E7%9B%B8%E5%85%B3/For%20Tello/Tello%20SDK%20Documentation%20EN_1.3_1122.pdf),
* [SDK 2.0](https://dl-cdn.ryzerobotics.com/downloads/Tello/Tello%20SDK%202.0%20User%20Guide.pdf) - supports mission pads, wifi-client mode but only for Tello EDU

Undocumented details on the wifi protocoll are listed at [Tello Pilots Wiki - Protocol](https://tellopilots.com/wiki/protocol/).

There are libraries which implement featuresets in different languages and bindings to other frameworks.

* [DJITelloPy](https://github.com/damiafuentes/DJITelloPy) ⭐ 1,482 | 🐛 42 | 🌐 Python | 📅 2025-01-27 - `#Python` swarm, mission pads, CV2
* [Tello-Python](https://github.com/dji-sdk/Tello-Python) ⭐ 1,451 | 🐛 70 | 🌐 Python | 📅 2023-12-29 Official SDK, `#Python2`
* [TelloPy](https://github.com/hanyazou/TelloPy) ⭐ 716 | 🐛 43 | 🌐 Python | 📅 2024-07-23 - `#Python`, unmaintained, SDK 1.3 and lowlevel, pretty pythonic with examples, only inline docs
  * [Fork](https://github.com/shortstheory/TelloPy/tree/F310/tellopy) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2019-06-30 - Logitech F310 gamepad support
* [Tello\_ROS](https://github.com/clydemcqueen/tello_ros) ⚠️ Archived `#ROS` (Robot Operrating system)
* [TelloLib](https://github.com/Kragrathea/TelloLib) ⭐ 140 | 🐛 14 | 🌐 C# | 📅 2019-01-07 - `#C#`, Apps for Android and CLI
* [Tello-nodejs](https://github.com/jsolderitsch/tello-nodejs) ⭐ 94 | 🐛 4 | 🌐 JavaScript | 📅 2019-06-19
* <https://github.com/SMerrony/tello> ⭐ 85 | 🐛 0 | 🌐 Go | 📅 2021-11-14
* [EasyTello](https://github.com/Virodroid/easyTello) ⚠️ Archived - `#Python`, unmaintained
* [Flock2](https://github.com/clydemcqueen/flock2) ⚠️ Archived `#ROS` (Robot Operrating system) for swarms
* [TelloJS](https://github.com/kanekotic/tellojs) ⚠️ Archived
* [TelloAPI-SDK-2.0](https://github.com/marklauter/TelloAPI-SDK-2.0) ⭐ 31 | 🐛 0 | 🌐 C# | 📅 2026-07-14 - `#C#`
* [Tello](https://github.com/vss2sn/tello) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2021-02-19 - `#C++`
  * [Tello](https://github.com/LucaRitz/tello) ⭐ 2 | 🐛 1 | 🌐 C++ | 📅 2020-10-02 - `#C++`
* [Tello Ruby Gem](https://github.com/blacktm/tello) ⭐ 27 | 🐛 3 | 🌐 Ruby | 📅 2021-12-02 `#Ruby`
* [dji-ryze-tello](https://github.com/m6c7l/dji-ryze-tello) ⭐ 21 | 🐛 0 | 📅 2019-09-14 - `#Python`
* [DJI-tello](https://github.com/grofattila/dji-tello) ⭐ 20 | 🐛 0 | 🌐 Java | 📅 2020-11-16 - `#Java`
* [TelloSwift](https://github.com/liuxuan30/TelloSwift) ⭐ 20 | 🐛 0 | 🌐 Swift | 📅 2026-06-23 - `#Swift`
* [TelloPython](https://github.com/jaqxues/TelloPython) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2021-03-14 - `#Python` flip, reverse engenierd
* [KTello](https://github.com/ivanocj/ktello) ⭐ 12 | 🐛 0 | 🌐 Kotlin | 📅 2020-09-19 - `#Kotlin`
* [tello\_edu.py](https://github.com/tariq86/tello_edu.py) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2019-12-23 - `#Python` swarms
* [Tello](https://github.com/muety/tello) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2019-10-01 - `#Go` (Gobot framework)
* [TelloSwift](https://github.com/tranchis/TelloSwift) ⭐ 11 | 🐛 0 | 🌐 Swift | 📅 2018-08-26 - `#Swift`
* [Tello4J](https://github.com/FriwiDev/Tello4J) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2020-01-24 - `#Java`
* [TelloCommander](https://github.com/davewalker5/TelloCommander) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2025-12-07 - `#C#`
* [Tello-Processing](https://github.com/f41ardu/TelloProcessing) ⭐ 8 | 🐛 0 | 🌐 Processing | 📅 2020-01-03 - `#processing`, SDK 1.3
* [TelloKt](https://github.com/JakeJMattson/TelloKt) ⭐ 6 | 🐛 0 | 🌐 Kotlin | 📅 2020-11-16 - `#Kotlin`
* [DJI-Tello-Dart-Package](https://github.com/mateustoin/DJI-Tello-Dart-Package) ⭐ 4 | 🐛 2 | 🌐 Dart | 📅 2024-06-09 - `#dart`
* [DJITello-Cpp](https://github.com/shalinirago/DJITello-Cpp) ⭐ 3 | 🐛 1 | 🌐 C++ | 📅 2021-02-09 - `#C++`
* [TelloTS](https://github.com/siokas/tellots) ⭐ 1 | 🐛 7 | 🌐 TypeScript | 📅 2022-12-30 - `#typescript`
* [RyzeTelloSDK](https://github.com/Eloncase/RyzeTelloSDK) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2021-02-05 - `#C#`
* [pytello](https://bitbucket.org/PingguSoft/pytello/src/master/) - `#Python`
* [Tello-drone-matlab](https://ww2.mathworks.cn/hardware-support/tello-drone-matlab.html) - `#Matlab`
* [Tello Rust package](https://docs.rs/tello/0.3.0/tello/) `#Rust`

## Hardware

* [RyzeTelloFirmware](https://github.com/MrJabu/RyzeTelloFirmware) ⭐ 80 | 🐛 0 | 🌐 Standard ML | 📅 2018-04-11 - hardware details and firmware binaries
* [raspberrypi-controlled-tello](https://github.com/erviveksoni/raspberrypi-controlled-tello) ⭐ 56 | 🐛 2 | 🌐 Python | 📅 2019-12-21Control via RPI
* [telloArduino](https://github.com/akshayvernekar/telloArduino) ⭐ 36 | 🐛 5 | 🌐 C++ | 📅 2020-12-08 - Control via ESP32
* [hack\_GamesirT1d](https://github.com/Diallomm/hack_GamesirT1d) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2021-05-03 Read original drone gamepad controller
* [m5stickcUartUdpBridge](https://github.com/EiichiroIto/m5stickcUartUdpBridge) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2020-08-05 Control via micro:bit with radio-UART and `#micropython`
* [m5-block-dji-tello-drone-control](https://www.hackster.io/gperrella/m5-block-dji-tello-drone-control-c2646f) ESP32 M5Stack control with `#micropython`
* [Tello Pilots Wiki - Protocol](https://tellopilots.com/wiki/protocol/) Reverse engineered (extended) control protocol with all features of the Android App
* [Tello Pilots Forum - Tello PCB and antenna to help fellow crazy modders](https://tellopilots.com/threads/tello-pcb-and-antenna-reference-to-help-fellow-crazy-modders.2985/) - PCB
* [FCC 2AOOE-WM0041801](https://fccid.io/2AOOE-WM0041801/Internal-Photos/Internal-Photos-3731020) - PCB, components

## Forums

* [DJI Tello Forum](https://forum.dji.com/forum-127-1.html) - general support
* [tellopilots.com Forum](https://tellopilots.com) - Forum & wiki discussing mods, coding, reverse-engineering

## Examples

Applications which show integration and mashups using the Tello.

* [Tello-openpose](https://github.com/geaxgx/tello-openpose) ⭐ 305 | 🐛 16 | 🌐 Python | 📅 2021-12-13
* [Tello ROS ORBSLAM](https://github.com/tau-adl/Tello_ROS_ORBSLAM) ⭐ 195 | 🐛 15 | 🌐 C++ | 📅 2022-05-17 - Global positioning
* [Hallo](https://github.com/GalBrandwine/HalloPy) ⭐ 67 | 🐛 1 | 🌐 Python | 📅 2021-11-09 - Hand gesture controlled
* [DJITelloOpticalControl](https://github.com/TamasSzepessy/DJITelloOpticalControl) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2021-07-31 - Autonomous flight via markers
* [Yello](https://github.com/adriacabeza/Yello) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2020-10-06 - CV and ML using offboard Yolo v3
* [Pose Recognition Tello](https://github.com/houdinisparks/pose_recognition_tello) ⭐ 16 | 🐛 14 | 🌐 Python | 📅 2023-02-15 - Control via human body poses
* [Tello AI features](https://github.com/carlo98/tello-ai-features) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-05-12 - Face and obstacles detection
* [Alexa controlled drone](https://github.com/erviveksoni/alexa-controlled-drone) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2020-01-18 - Control via Alexa using a RPI gateway
* [Eye in the sky](https://github.com/sushansapaliga/Eye-In-The-Sky) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-09-03 - Face detection and follow-me
* [Tello Laser Shot](https://github.com/Keleas/Tello_Laser_Shot) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2020-03-28 - Find targets and point them with a laser
* [Autonomous Indoor Control and Mapping Sistem](https://github.com/juanmill4/Indoor-Autonomous-Tello) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-10-22 - This project provides an system for autonomous navigation and mapping, leveraging various technologies like ARUCO markers, Webots simulation, and deep learning object detection through Yolov5 + [API Tello Webots](https://github.com/juanmill4/API-Tello-tellopy-Webots) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-09-05 - To Simulation like TelloPy library.
* [CoviDrone](https://github.com/altaga/CoviDrone) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-09-05 - Cleaning Bot with UV lamps
* [Autonomous Navigation via Deep Reinforcement Learning for Resource Constraint Edge Nodes using Transfer Learning](https://arxiv.org/pdf/1910.05547.pdf) - Autonomous flight trained by virtual 3D levels
* [CV 3D Tracking of a person in lock mode no yaw](https://tellopilots.com/threads/computer-vision-3d-tracking-of-a-person-in-lock-mode-no-yaw.4330/) Person 3D tracking and follow-me
* [CNN based dense monocular visual SLAM forindoor mapping and autonomous exploration](http://essay.utwente.nl/81420/1/__ad.utwente.nl_Org_BA_Bibliotheek_Documentfiles_Afstudeerverslagen_Nieuw_Master%20Thesis%20Anne%20Steenbeek.pdf) - Indoor mapping
* [Object Detection using Ryze Tello Drone with Help of Mask-RCNN](https://www.researchgate.net/publication/340887697_Object_Detection_using_Ryze_Tello_Drone_with_Help_of_Mask-RCNN) - Object detection
* [Tello-drone](https://github.com/yushulx/tello-drone) - Barcode scanner

## Security

* [Drone hacking tool analysis - dronesploit](https://dronesec.com/blogs/articles/drone-hacking-tool-analysis-dronesploit) - Hijacking using [dronesploit-framework](https://github.com/dhondta/dronesploit) ⭐ 2,156 | 🐛 2 | 🌐 Python | 📅 2024-11-23

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
