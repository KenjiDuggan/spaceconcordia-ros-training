# spaceconcordia-ros-training

## ROS Robot Programming Key Notes


### Chapter 2
#### 2.1 - Intro. to ROS

ROS is open-source, meta-operating system for your robot. Hardware abstraction, low-level device control, implementation of commonly-used functionality, 
message-passing through processes, package management, etc. like an OS.


#### 2.2 - Meta-Operating System

OS for general-purpose computers include Windows (XP, 7, 8, 10), Linux (Linux Mint, Ubuntu, Fedora, Gentoo) and Mac (OS X Mavericks, Yosemite, El Capitan).
OS for smartphones include Android, iOS, Symbian, RiMO, Tizen, etc.

ROS is not actually an OS. However it is capable of many features an OS would be tasked with, a system that performs processes such as scheduling, loading, 
monitoring and error handling by using virtualization layer between applications and distributed computing resources.

ROS is a supporting system for controlling a robot and sensor with a hardware abstraction and developing robot application based on an existing conventional operating systems.


#### 2.3 - Objectives of ROS

ROS characteristics:
* Distributed process: It is programmed in the form of the minimum units of executable processes (nodes), and each process runs independantly and exchanges data systematically
* Package management: Multiple processes having the same purpose are managed as a package so that it is easy to use and develop, as well as convenient to share, modify and redistribute
* Public repository: Each package is made public to the developer’s preferred public repository (e.g., GitHub) and specifies their license
* API: ROS is designed to call an API when you are using it. Not much difference from Python and C++.
* Supporting various programming languages: Python, C++, Lisp, JAVA, C#, Lua, Ruby


#### 2.4 - Components of ROS

Refer to textbook figure...


#### 2.5 - ROS Ecosystem

App, ROS, ROBOT and Sensors
Refer to textbook figure...


#### 2.6 - History of ROS

May 2007, Dr. Morgan Quigley by the Stanford Artificial Intelligence Lab in Support of Stanford AI Robot STAIR project
November 2007, Willow Garage (US robot company) succeeded the development of ROS
ROS is based on BSD 3-clause License and Apache License 2.0, allowing anyone to edit and use


#### 2.7 ROS Versions

There's a shitton of versions:

Dec 08, 2017 - Release of ROS 2.0
■ Sep 21, 2017 - ROSCon2017 (Canada)
■ May 23, 2017 - Release of Lunar Loggerhead
■ May 16, 2017 - Changed name from OSRF to Open Robotics
■ Oct 8, 2016 - ROSCon2016 (South Korea)
■ May 23, 2016 - Release of Kinetic Kame
■ Oct 3, 2015 - ROSCon2015 (Germany)
■ May 23, 2015 - Release of Jade Turtle
■ Sep 12, 2014 - ROSCon2014 Conference (U.S.)
■ Jul 22, 2014 - Release of Indigo Igloo
■ Jun 6, 2014 - ROS Kong 2014 Conference (Hong Kong)
■ Sep 4, 2013 - Release of Hydro Medusa
■ May 11, 2013 - ROSCon2013 Conference (Germany)
■ Feb 11, 2013 - Open Source Robotics Foundation takes on development/management
■ Dec 31, 2012 - Release of Groovy Galapagos
■ May 19, 2012 - ROSCon2012 Conference (U.S.)
■ Apr 23, 2012 - Release of Fuerte
■ Aug 30, 2011 - Release of Electric Emys
■ Mar 2, 2011 - Release of Diamondback
■ Aug 2, 2010 - Release of C Turtle
■ Mar 2, 2010 - Release of Box Turtle
■ Jan 22, 2010 - Release of ROS 1.0
■ Nov 1, 2007 - Willow Garage starts development under the name ‘ROS’
■ May 1, 2007 - Switchyard Project, Morgan Quigley, Stanford AI LAB, Stanford University
■ 2000 - Player/Stage Project, Brian Gerkey, University of Southern California (USC)


##### 2.7.1 Version Rules

Apart from version 1.0, versions start in alphabetical order. Also, each version has an illustration in the form of a poster and a turtle icon


##### 2.7.2 Version Release Period

ROS versions get updated twice a year(April and October), same as release period of ROS supporting operating system.

##### 2.7.3 Selecting a Version

...Choose based on your OS: Ubuntu, Linux Mint, Debian Versions
