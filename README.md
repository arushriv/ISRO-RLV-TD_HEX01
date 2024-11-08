# Dynamic Investigation Propulsion for Free Flying Bot for Space Applications

Our Research And Development team at ISRO is currently working on a project to develop a dynamic propulsion system for an autonomous free-flying robot for space applications. The objective is to create a robotic system that can freely navigate and maneuver in space to assist with various tasks. Key aspects of the project include: Dynamic modeling of the propulsion module to understand its behavior and performance in the space environment. Investigation of different propulsion technologies suitable for a free-flying robot in space. Design and development of the propulsion system, including thrusters, fuel systems, and control mechanisms. Integration of the propulsion module with the robotic platform and other subsystems. Testing and validation of the integrated system to ensure reliable and safe operation in space

The free-flying robot is envisioned to have applications in areas such as: Inspection and maintenance of spacecraft and space stations. Assisting astronauts during extravehicular activities (EVAs). Performing experiments and collecting data in microgravity environments. Demonstrating advanced robotic capabilities for future space missions.
By developing this autonomous free-flying robot with a robust propulsion system, Our team at ISRO aims to enhance the capabilities of space robotics and support various space exploration and research activities.

**MATLAB/C++ Libraries for the kinematic and dynamic analysis and simulation of space robots**

![movx.gif](./docs/media/movx.gif) ![ets3x4.gif](./docs/media/ets3x4.gif)

Author(s) and maintainer(s): [Space Robotics Lab.](http://www.astro.mech.tohoku.ac.jp/e/index.html)

[![srl-logo-original.jpg](./docs/media/srl-logo-original.jpg)](http://www.astro.mech.tohoku.ac.jp/e/index.html)

**This GitHub page is made based on the [original webpage of the Spacedyn](http://www.astro.mech.tohoku.ac.jp/spacedyn/) by current SRL member.** Please, always refer to the original webpage for more information.


## Overview
The RLV_HEX_ISRO's MATLAB/C++ library for the kinematic and dynamic analysis and simulation of articulated multi-body systems with a moving base. Examples of such systems are a satellite with mechanical appendages, a free-flying space robot, a wheeled mobile robot, and a walking robot, all of which makes motions in the environment with or without gravity.

This toolbox can handle open chain systems with topological tree configuration. A parallel manipulator, for example, then cannot be supported directly. A walking robot contacting on the ground with more than two legs or limbs at a time seems to form a closed chain including the ground, however, we can handle such a system with a proper model of ground contact at each contact point. Parallel manipulators can be treated with virtual cut of a kinematic chain and a corresponding virtual force model.

Some academic papers regarding this toolbox is published by Kazuya Yoshida and his co-author(s) [1]. For the technical points of this software, please consult these papers as well as the following chapters of the document.

We hope that you could find this toolbox useful.


## Notice
* Now, the Space_RLV_ISRO is Version 2, Release 0.
* The Spacedyn is a free software.
* You can download and use it freely for your academic purpose.
* Any of commercial use is kindly refused.
* There is no warranty for any damages caused by this software.
* If you intend to modify and re-distribute the Spacedyn, please consult us.
* The Spacedyn requires MATLAB 5.0 or higher. ( It uses functions that are not supported in 4.0 or lower )


## Reference Publication
[1] Kazuya Yoshida et. al., "[The SpaceDyn: a MATLAB toolbox for space and mobile robots](https://ieeexplore.ieee.org/document/811712)", Proceedings of the 1999 IEEE/RSJ International Conference on Intelligent Robots and Systems. Human and Environment Friendly Robots with High Intelligence and Emotional Quotients (Cat. No.99CH36289), Kyongju, South Korea, 1999, pp. 1633-1638 vol.3, [doi: 10.1109/IROS.1999.811712](https://doi.org/10.1109/IROS.1999.811712).


## Release Note
* Sep. 17th, 2020, SpaceDyn version 2 release 0 is released in GitHub.
* Oct. 16th, 2020, SpaceDyn C++ is released.
* May. 31th, 2024, SpaceDyn version 2 release 1 is released in GitHub.
    * Debug integral of base orientation (fixed `f_dyn_rk2` and `dc2qtn`, added `qtn2dc` and `w2dQtn`)


