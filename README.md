# Traffic Simulator for Multibeam Satellite Communication Systems
These dataset packages are related to the follow article:
Hayder Al-Hraishawi, Eva Lagunas, Symeon Chatzinotas, "Traffic Simulator for Multibeam Satellite Communication Systems," Available:https://arxiv.org/abs/2007.07148

# Abstract of the article
Assume that a multibeam satellite communication system is designed from scratch to serve a particular area with maximal resource utilization and to satisfactorily accommodate the expected traffic demand. The main design challenge here is setting optimal system parameters such as number of serving beams, beam directions and sizes, and transmit power. This paper aims at developing a tool, multibeam satellite traffic simulator, that helps addressing these fundamental challenges, and more importantly, provides an understanding to the spatial-temporal traffic pattern of satellite networks in large-scale environments. Specifically, traffic demand distribution is investigated by processing credible datasets included three major input categories of information: (i) population distribution for broadband Fixed Satellite Services (FSS), (ii) aeronautical satellite communications, and (iii) vessel distribution for maritime services. This traffic simulator combines this three-dimensional information in addition to time, locations of terminals, and traffic demand. Moreover, realistic satellite beam patterns have been considered in this work, and thus, an algorithm has been proposed to delimit the coverage boundaries of each satellite beam, and then compute the heterogeneous traffic demand at the footprint of each beam. Furthermore, another algorithm has been developed to capture the inherent attributes of satellite channels and the effects of multibeam interference. Data-driven modeling for satellite traffic is crucial nowadays to design innovative communication systems, e.g. precoding and beam hopping, and to devise efficient resource management algorithms.

# Content of data package
The Satellite Traffic Simulator provides the geographical traffic distribution over Europe considering broadband consumer users combined with maritime broadband traffic. Here you can find samples of the outputs that can be delivered by this simulator. Specifically, the attached MAT files contain 24 traffic demand instances for a whole day on an hourly basis. Each file is a table where each row is a user and the four columns labeled as follows: Beam Number, Latitude, Longitude, and Traffic Demand in Mbps. 

# Acknowledgements
This work was supported in part by Luxembourg National Research Fund (FNR) under the projects FlexSAT (C19/IS/13696663) and IPBG INSTRUCT.

# Referencing
If you in any way use this data for research that results in publications, please cite our article shown above.
