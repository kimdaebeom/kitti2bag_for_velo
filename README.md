# kitti2bag_for_velo
Added support for velodyne-only odometry type. It will generate a rosbag file with pointcloud-only topic with timestamp, and the bag filename will be kitti_data_odometry_velo_sequence_XX.bag for the selected sequence number XX.

## How to use
- Install kitti2bag.
```bash
sudo pip install kitti2bag
```
- Update kitti2bag.
```bash
cd /usr/local/bin
sudo gedit kitti2bag
```
- Run kitti2bag with odom_velo mode.
```bash
kitti2bag odom_velo . -s 00
```
