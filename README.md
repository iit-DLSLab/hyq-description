hyq-description
=======

Introduction
=======
This package contains the description (mechanical, kinematic, visual, etc.) of the different HyQ robots. The files in this package are parsed and used by a variety of other components. Most users will not interact directly with this package.

Build
=======
```bash
catkin_make
source devel/setup.bash
```

Usage
=======
### Show the HyQ robot
```bash
roslaunch hyq_description rviz.launch
```

### Show the world map
```bash
roslaunch hyq_description world.launch
```
This package requires the dependency on the ros_impedance_control package.
world launch file still have a lot of issues.

Citation
=======
An overview of the theoretiacl and implementation details has been published in [https://journals.sagepub.com/doi/10.1177/0959651811402275]. To cite hyq-description in your academic research you can use the following BibTex entry:

	@ARTICLE{semini11hyqdesignjsce,
		AUTHOR = {Semini, Claudio and Tsagarakis, Nikos G. and Guglielmino, Emanuele and Focchi, Michele and Cannella, Ferdinando and Caldwell, Darwin G.},
		TITLE = {Design of HyQ - a Hydraulically and Electrically Actuated Quadruped Robot},
		JOURNAL = {IMechE Part I: Journal of Systems and Control Engineering},
		YEAR = {2011},
		VOLUME = {225},
		PAGES = {831-849},
		NUMBER = {6},
		OWNER = {CSemini},
		TIMESTAMP = {2011.02.20},
		DOI = {10.1177/0959651811402275},
	}
