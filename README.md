![RIA_CSM2](https://github.com/DK-HU/impact_detection_datasets/blob/main/asset/RIA_CSM2%2000_00_00-00_00_30.gif)

This is the official dataset of our work "RIA-CSM2: A Real-Time Impact-Aware Correlative Scan Matching Algorithm Using Heterogeneous Multi-Core SoC for Low-Cost Wheeled Robots"

The datasets collected when the robot cleaner moves over obstacles and vibrates are stored in Folder 20230208-080129.

The datasets collected when the robot cleaner is impacted are stored in other folders.

Each line of data in the data.txt file consists of a timestamp (ms), three-axis gyroscope readings, left rotation encoder readings, right rotation encoder readings, three-axis accelerometer measurements, and whether it has been impacted (1: impacted, 0: not impacted).

——How to get the wheel rotation? 
——The difference between two adjacent lines of data is the angle of wheel rotation.

——How to get the change in IMU attitude? 
——The difference between the gyroscope readings of two adjacent lines is the change in IMU attitude (unit: degree).
