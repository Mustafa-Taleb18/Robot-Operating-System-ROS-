#### **The objective**:
Providing a guide to create two nodes and how they communicate. 

#### **Requarements**:

* Linux OS
* install ROS

#### **The explenation**:
There are three main steps to implement the objective:

* **First**:create ROS workplace
* **Seconde**:create package
* **Third**: Creat publisher & subscriber nodes


 First:create ROS workplace:
* 1-Create folder at any directory.	(catkin_ws)
* 2-Create another folder within it. 	(src).
* 3-activate the workplace.
* 4-overlayed workplace.
* 5-check if workplace overplayed.

 Seconde: create package:
* 1-change directory to src
* 2-create your package
* 3-create other packages (if need it)
* 4-activate the workplace. (as step 3 in first)
* 5-overlayed workplace (as step 4 in first)

 Third:Creat publisher & subscriber nodes
* 1-write a python code in file text (publisher.py) 
* 2-write a python code in file text (subscriber.py)
* 3-change directory to catkin_ws
* 4-run rosrun with package name and file (publisher.py)
* 5-open another terminal widow
* 6-change directory to your package
* 7-add the workspace to your ROS environment
* 8-run rosrun with package name and file (subscriber.py)

**Refrences**:
-http://wiki.ros.org/catkin/Tutorials/CreatingPackage
-http://wiki.ros.org/rospy_tutorials/Tutorials/WritingPublisherSubscriber
