---
title: "Hesai-Pandar 40P support in lidar camera calibration tool"
collection: projects
permalink: /projects/lidar_cam_calibration
excerpt: 'A merged update to [lidar_camera_calibration](https://github.com/ankitdhall/lidar_camera_calibration) that adds support for Hesai-Pandar 40P lidar.'
date: 2019-9-6
# venue: 'IEEE Robotics and Automation Letters (RA-L) (In Review)'
# paperurl: 'https://arxiv.org/abs/1909.07843'
# authors: '**Rui Chen**'
# image: 'auto_gen_map_pitts.png'
# archive_image: 'auto_gen_map_pitts.png' 
# video: 'https://www.youtube.com/embed/DuCVeBRDr7E'
# archive_video: 'https://www.youtube.com/embed/DuCVeBRDr7E'
codeurl: 'https://github.com/ruichen-v/lidar_camera_calibration'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
## Add Hesai-Pandar 40P lidar support
1. Add parser for /pandar_points provided by [Hesai Lidar Driver](https://github.com/HesaiTechnology/HesaiLidar-ros).
2. Add option in `config_file.txt` to select between Velodyne lidar and Hesai lidar
3. Updated README.md. Add a note about fixing synchronization between Hesai lidar driver and aruco mapping node.
 
<!-- [Download paper here](https://arxiv.org/abs/1909.07843) -->
