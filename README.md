# go1_kb
AATB's Unitree Go1 Knowledge Base. In any case first check [MAVProxyUser](https://github.com/MAVProxyUser/YushuTechUnitreeGo1) and [maggusscheppi](https://github.com/maggusscheppi/Go1) repos, this is additional findings and notes we've collected while working and developing on the Go1 platform. These are things we are in the process of documenting so listed here but not obviously published yet.

# ROS
- setup internet access on the Pi & Jetsons for easy install and update of external packages and repositories
- setup the dog's network to autojoin an existing Wifi network to remotely access the Pi
- setup the dog's network to access wirelessly all devices from an external ROS machine and be able to use RViz remotely.
- disable default Unitree services to free up lot of CPU time and wasted power
- publish `/imu` and `/odom` topics and tf from the motion controller
- publish `/image_raw` and `/image_rect` camera feeds for each stereo pairs

# Quirks & Repairs
- repair plastic tubing sleeves cracking at the base of the motor's strain relief
