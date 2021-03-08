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
Autonomous navigation requires a wide-range of engineering expertise and a well-developed technological architecture in order to operate. The focus of this project is to illustrate the significance of data visualizations and an interactive interface with regards to autonomous navigation in a racing environment. In order to yield the best results in an autonomous navigation race, the users must be able to understand the behavior of the vehicle when training navigation models and during the live race. To address these concerns, teams working on autonomous navigation must be able to visualize and interact with the robot. Different algorithms such as A* search and RRT* (Rapidly-exploring random tree) are implemented to create path planning and obstacle avoidance. Visualizations of these respective navigation algorithms and a user interface that allows the user to navigate the robot and view real-time sensory data will help to enhance model testing, debug unexpected behavior, and improve upon existing autonomous navigation models. Simulations with the most optimal navigation algorithm will also be run to demonstrate the functionality of the interactive interface. 


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
Below, a demonstration video of the interface is displayed: <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/nUsRP3SFIew" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Below, a demonstration video of interface demo (input position) is displayed: <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/GzUygh2_3e4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## <a name = "Results" />Results & Impact: 
Due to the restrictions of the pandemic, our group is testing path planning algorithms using an on-line simulator called Gazebo. The Gazebo simulator allows us to create robots and racetracks that can be used to simulate different path planning algorithms. The path planning algorithms we are using is based on GMapping, which is a lidar-based simultaneous locazliation and mapping method that creates a 2-D grid map of the given simulated track. After the grid map is created, our group tested a sampling-based algorithm called RRT*, and a search-based algorithm called A*. Testing out different algorithms are important, because different race tracks have unique characteristics, and one algorithm may be more advantageous than another. Along with the python visualizations and Gazebo simulated algorithms, our group is currently creating an interactive interface that allows the users to to choose what algorithn they believe is the most efficient using this interface. The interface will display metrics that will help determine the user what the best-fit algorithm is, along with visualiztions of the algorithms through the Gazebo simulator and python visualizer shown above.


## <a name = "Conclusion" />Conclusion:
Our team's final goal is to create an interactive interface that will allow the user to view different visualizations and metrics of unique algorithms that will be used for autonomous navigation in different unique race tracks. This interactive interface will allow the user to choose the most efficient algorithm. Much more progress is needed to complete different autonomous navigation as well as visualizing these navigation algorithms, but our group is on the correct track to achieve our set goals. 


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
