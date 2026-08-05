# LiDAR-Based-SLAM-with-ICP-Scan-Matching-and-Pose-Graph-Optimization

Implemented a LiDAR-based SLAM pipeline for indoor robot mapping using encoder, IMU, LiDAR, and RGB-D sensor data. The system first performed dead reckoning from wheel encoder and IMU measurements, then reduced local drift using ICP-based LiDAR scan matching. I further built 2D occupancy grid maps and RGB-D floor texture maps, and improved global consistency using GTSAM pose graph optimization with loop-closure constraints.
