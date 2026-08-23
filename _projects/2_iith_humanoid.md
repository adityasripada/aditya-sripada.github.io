---
layout: page
title: IITH Full-Sized Humanoid
description: Human-scale humanoid robot built from scratch at IIT Hyderabad — 1.72 m, 26 DoF
img: assets/img/google-sites/iith-humanoid-with-naos.jpg
importance: 2
category: work
---

At the **Robotics and Intelligent Systems Lab, IIT Hyderabad**, I independently engineered a full-sized humanoid robot from scratch under the mentorship of Prof. R. Prasanth Kumar. Working alone on a project this size meant taking every role at once — mechanical designer, electrical engineer, control engineer, and programmer. I designed the robot in SolidWorks, ran the stress analysis, fabricated and assembled it, laid out the electronics to deliver power to every actuator and acquire data from every sensor, and developed its walking algorithm.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/google-sites/iith-humanoid-with-naos.jpg" title="The IITH humanoid alongside NAO robots" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/google-sites/iith-humanoid-aditya-2.jpg" title="The humanoid under construction" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: the 1.72 m humanoid alongside NAO robots in the IITH lab. Right: an earlier build phase.
</div>

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/google-sites/iith-humanoid-aditya.jpg" title="With the completed humanoid" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Specifications

- **Height:** 172.2 cm (human-scale)
- **Weight:** 39 kg
- **Degrees of freedom:** 26
- **Actuators:** Dynamixel Pro H54-200-S500-R, Dynamixel RX-64
- **Sensors:** Hokuyo UTM-30LX-EW LiDAR, Stereolabs ZED, Analog Devices ADIS16485 6-DoF IMU
- **Budget:** INR 7 million (approx. USD 100K)

### Capabilities developed

- Static and dynamic walking, with active balance control
- Push recovery
- Vertical jumping (presented at ROBIO 2018)
- Real-time teleoperation with full-body motion imitation from a human operator (presented at ICARM 2018)

<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/google-sites/iith-sensor-head-zed-lidar.jpg" title="Sensor head: Stereolabs ZED over a scanning LiDAR" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The sensor head — Stereolabs ZED stereo camera above a scanning LiDAR.
</div>

### Other work in the same lab

- **Five-bar parallel manipulator** — a design in which all four links are of equal length, which introduces additional parallel singularities. I developed a control strategy to pass through them, significantly enlarging the usable workspace, and validated it on a prototype with micron-level precision control.
- **Full-sized quadruped** — gait development for a cheetah-sized 12-DoF quadruped targeting 30 m/min at a 15 cm step length.
- **Push recovery by sliding** — recovering from pushes by continuously reconfiguring posture and initiating a controlled slide once the zero-moment point reaches a set position under the foot.

### Related publications

- **Biped Robot Vertical Jumping with Control Constraints** — *ROBIO 2018*
- **Real-Time Teleoperation of a Humanoid Robot with Motion Imitation and Legged Locomotion** — *ICARM 2018*
- **Push Recovery of Biped Robots by Sliding** — *Preprint*
- **Towards a Flying and Leaping Humanoid Robot** — *IROS 2018 (poster)*
