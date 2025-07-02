# Conf-SLAMMOT：A Confidence-based LiDAR SLAMMOT in Dynamic Environments
We propose a confidence-based SLAMMOT method that tightly couples LiDAR SLAM with confidence-based multi-object tracking. This method can not only optimize the estimated state of both the ego-vehicle and moving objects simultaneously, but also effectively recovers tracking of continuously missed detections based on confidence-based data association, leading to a stable backend and improved estimation performance.

![figure1](https://github.com/user-attachments/assets/3d1ec753-0d8c-4f90-8bf8-f0961150e1eb)
The above figure shows the results of proposed Conf SLAMMOT solution in KITTI Tracking dataset. (b) and (c) denote the generated complete point cloud map and details of the result shown in (a), respectively.

![figure5](https://github.com/user-attachments/assets/ae5f533b-bd27-4352-b515-4c128bfbf69a)
The above figure show the visualization results of different methods in continuous missed detection scenes. (1a-1d), (2a-2d), (3a-3d) represent the visualization results of LIO-SEGMOT at consecutive moments on sequences 00, 02 of KITTI Tracking dataset, and an intersection scene of Waymo Open dataset, respectively; (1a*-1d*), (2a*-2d*), (3a*-3d*) represent the visualization results of the proposed Conf SLAMMOT at consecutive moments on corresponding scenes, respectively. Due to temporary occlusion or distance of objects, there are continuous frame missed detection; these objects are highlighted and enlarged with circles for display. For example, object ID 0 in (1b*-1c*), object ID 11 in (2b*-2c*), and object ID 52 in (3b*-3c*), and as shown in (1d*), (2d*), and (3d*), Conf SLAMMOT can accurately resume tracking without ID switching.

# Code
Will be added soon ...
