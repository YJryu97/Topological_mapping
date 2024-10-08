# Topological_mapping
Generating multi-trajectory topological map utilizing unsupervised learning "Growing Neural Gas". 
GNG is a type of artificial neural network that grows both in terms of the number of nodes and the edges between them, which makes it quite flexible and useful for organizing complex data structures. 
It's particularly useful for tasks such as clustering without the need for predefined cluster numbers and can adapt to the data structure over time.
Point Cloud data(csv) was extracted by 3D Lidar attached to mobile robot, and its localization has been optimized through scan-matching the relative pose from graph-SLAM. 
Traversable polygons, representing areas where the robot can move freely without collisions, are generated as grid cells. These grid cells are then used as training data for the GNG algorithm to perform feature mapping.

Conference paper

Nonomura Rikudai, Young Jae Ryu, Yasukazu Tasaki, Hikaru Nagano, and Yasuyoshi Yokokoji. ”Construction of Topo-
logical Maps of Outdoor Environments Based on Growing Neural Gas.”, 41st Annual Conference of the Robotics Society of Japan(RSJ), Session 1H4-05, 2023
