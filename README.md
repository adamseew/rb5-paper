
# RB5 Low-Cost Explorer: Implementing Autonomous Long-Term Exploration on Low-Cost Robotic Hardware 

This is the preprint of our long-term autonomous exploration [paper](rb5-paper.pdf). The paper is currently accepted for publication at [ICRA'24](https://2024.ieee-icra.org/). 

---

## Reference

To reference the paper, it is sufficient to use the following BibTeX entry:
```bibtex
@inproceedings{seewald2023rb5,
  title={{RB5} Low-cost explorer: Implementing autonomous long-term exploration on low-cost robotic hardware},
  author={Seewald, Adam and Chanc{\'a}n, Marvin and McCann, Connor M. and Noh, Seonghoon and Fallahi, Omeed and Castillo, Hector and Abraham, Ian and Dollar, Aaron M.},
  booktitle={Proceedings of the IEEE International Conference on Robotics and Automation (ICRA'24)},
  pages={7},
  year={2024},
  organization={IEEE},
  url={https://adamseewald.cc/short/rb52023},
  note={to appear}
}
```

## Supplementary material

You can find the code for the approach [here](https://github.com/adamseew/rb5). It is split in multiple repositories:

|Repository|Function|
|---|---|
|[**ground robot**](https://github.com/adamseew/rb5)|`rb5-ground-robot` ROS2 package, which contains the code that runs on the companion computer onboard RB5, i.e., an [NVIDIA (R) Jetson NX (TM)](https://www.seeedstudio.com/reComputer-J2021-p-5438.html)|
|[**ground navigation**](https://github.com/adamseew/rb5-ground-navigation)|`rb5-ground-nav` ROS package, which contains the code that collects point clouds from an RGB-D camera and other data from the SLAM algorithm and ports them into ROS2|
|[**base server**](https://github.com/adamseew/rb5-base-server)|PHP- and JavaScript-based remote control base station that implements the necessary functionality for remote human intervention|
