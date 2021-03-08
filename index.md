The contents of this project can be found in the following github repo: <br/>
[https://github.com/dannyluo12/Autonomous_robot_data_visualization_and_interface](https://github.com/dannyluo12/Autonomous_robot_data_visualization_and_interface)


## Catalog
* [Project Goals](#goal)
* [Context](#Context)
* [Visualizations](#Visualizations)
* [Simulations & Interface](#Interface)
* [Results & Impact](#Results)
* [Conclusion](#Conclusion)
* [References](#References)

## <a name = "goal" />Project Goals:
The goal of this project is to create visualizations and an interactive interface to enable users to be successful in autonomous navigation applications. By doing so, we hope to enhance the users racing performance and debugging capabilities when working with autonomous vehicles. 


## <a name = "Context" />Context:
Autonomous navigation requires a wide-range of engineering expertise and a well-developed technological architecture in order to operate. The focus of this project is to illustrate the significance of data visualizations and an interactive interface with regards to autonomous navigation in a racing environment. In order to yield the best results in an autonomous navigation race, the users must be able to understand the behavior of the vehicle when training navigation models and during the live race. To address these concerns, teams working on autonomous navigation must be able to visualize and interact with the robot. Different algorithms such as A* search and RRT* (Rapidly-exploring random tree) will be implemented to create path planning and obstacle avoidance. Visualizations of these respective navigation algorithms through a user interface will help to enhance model testing, debug unexpected behavior, and improve upon existing autonomous navigation models. Simulations with the most optimal navigation algorithm will also be constructed to demonstrate the functionality of the interactive interface. 


## <a name = "Visualizations" />Visualizations:
Below, an image of the test track utilized to test navigation algorithms is displayed:
<div class="row">
  <div class="column">
    <img src="images/test_track.PNG" style="width:75%; height=75%">
  </div>
</div>

Below, a gif is provided to visualize how the RRT* algorithm will navigate from one point to another:
<div class="row">
  <div class="column">
    <img src="images/A_star_test_track.gif" style="width:75%; height=75%">
  </div>
</div>

Below, an image of the Thunderhill track utilized to run RRT* navigation algorithm is displayed:
<div class="row">
  <div class="column">
    <img src="images/thunderhill_cropped_map.PNG" style="width:75%; height=75%">
  </div>
</div>

Below, a gif is provided to visualize how the RRT* algorithm will navigate from one point to another on the Thunderhill track:
<div class="row">
  <div class="column">
    <img src="images/rrt_star_thunderhill_cropped_gif.gif" style="width:75%; height=75%">
  </div>
</div>


## <a name = "Interface" />Simulations & Interface:
Live navigation sensors such as vehicle's speed, camera image, current position are displayed for the user as well as the visualization of the RRT* algorithm that shows the most efficient navigation path for the vehicle. If the user inputs destination coordinates inside the interface, it will autonomously navigate the vehicle with the RRT* algorithm.<br />
Below, a demonstration video of the interface is displayed.<br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/nUsRP3SFIew" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Below, a demonstration video of interface demo (input position) is displayed: <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/GzUygh2_3e4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## <a name = "Results" />Results & Impact: 
In this project, our group successfuly integrated a racing track simulation using the Gazebo Simulator that mirrors a real-life track. By using the depth camera and lidar navigation sensors, we were able to implement two path planning and obstacle avoidance algorithms in A* and RRT* inside the simulated track. The performance of these algorithms were tested based on different metrics, and these algorithms were also able to visualize their performance on real-life racing track images. We also implemented an interactive interface that will allow the user to control the vehicle and view significant sensory information obtained from the vehicle during autonomous navigation while also allowing the user to move the vehicle from its initial position to the final desination with a press of a button. This was achieved by displaying different real-time sensory data, creating a platform for the user to montor the path planning algorithm, and thus allowing the user to autonomously navigate the vehicle with ease.

## <a name = "Conclusion" />Conclusion:
Future improvements to the interactive interface currently include optimizing visualizations to be more clear, subscribe to more nodes to receive more input data, and test potential latency with larger datasets or streams of data. Currently, several plots and tools on the interactive interface contain data that is self generated on a small scale, often referred to as ‘dummy data’. Future ambitions include implementing the interface with more advanced datasets and streams of live input data.


## <a name = "References" />References:
* [Gazebo Simulator] <br/>
* [TurtleBot Robots] <br/>
* [UCSD Racing Track] <br/>
* [G-Mapping] <br/>
* [RViz] <br/>
* [Python] <br/>
* [CV2] <br/>
* [Rosbridge] <br/>
* [HTML] <br/>
* [Javascript] <br/>
* [Thunderhill Racing Track] <br/>
* [F1 Tenth Racing Track] <br/>
* [Web Video Server] <br/>
* [Adaptive Monte Carlo Localization (AMCL)] <br/>
* [A. A. Zhilenkov and I. R. Epifantsev. "Problems of a trajectory planning in autonomous navigation systems based on technical vision and AI." 2018] <br/>
* [Motion Planning for Urban Driving using RRT] <br/>
* [D. Ma and N. Zhou. “Web-Based Robot Control and Monitoring.” 2019]  <br/>
* [Calisi, Daniele and Nardi, Daniele. “Performance   evaluation of pure-motion tasks for mobile robots with respect to world models.” 2009] <br/>

[Gazebo Simulator]: http://gazebosim.org/tutorials?tut=ros_overview
[TurtleBot Robots]:http://wiki.ros.org/Robots/TurtleBot
[UCSD Racing Track]: http://github.com/garrettgibo/ucsd_f1tenth_simulator
[G-Mapping]: http://wiki.ros.org/gmapping
[RViz]: http://wiki.ros.org/rviz
[Python]: https://www.python.org/
[CV2]: https://pypi.org/project/opencv-python/
[Rosbridge]: http://wiki.ros.org/rosbridge_suite
[HTML]: https://html.spec.whatwg.org/
[Javascript]: https://www.javascript.com/
[Thunderhill Racing Track]: http://selfracingcars.com/
[F1 Tenth Racing Track]: https://f1tenth.org/
[Web Video Server]: http://wiki.ros.org/web_video_server
[Adaptive Monte Carlo Localization (AMCL)]: http://wiki.ros.org/amcl
[A. A. Zhilenkov and I. R. Epifantsev. "Problems of a trajectory planning in autonomous navigation systems based on technical vision and AI." 2018]: https://ieeexplore.ieee.org/abstract/document/8317265
[Motion Planning for Urban Driving using RRT]: http://acl.mit.edu/papers/KuwataIROS08.pdf
[D. Ma and N. Zhou. “Web-Based Robot Control and Monitoring.” 2019]: http://www.cs.binghamton.edu/~szhang/teaching/18spring/reports/Luo-Ma-Zhou.pdf
[Calisi, Daniele and Nardi, Daniele. “Performance   evaluation of pure-motion tasks for mobile robots with respect to world models.” 2009]: https://www.researchgate.net/publication/200744624_Performance_evaluation_of_pure-motion_tasks_for_mobile_robots_with_respect_to_world_models
