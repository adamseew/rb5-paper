
# A Low-Cost Energy-Efficient Approach for Long-Term Autonomous Exploration 

This is an early version of our long-term autonomous exploration [paper](rb5-paper.pdf). The paper is currently under review, it is **not** peer-reviewed. Furthermore, <ins>the manuscript is not for distribution</ins>. 

[![Watch the video](https://raw.githubusercontent.com/adamseew/rb5/master/rb5_video_gif.gif)](https://youtu.be/Vflmh6LTo6A)

---

## Reference

To reference the paper, it is sufficient to use the following BibTeX entry:
```bibtex
@inproceedings{seewald2023rb5,
  title={A low-cost energy-efficient approach for long-term autonomous exploration},
  author={Seewald, Adam and Chanc{\'a}n, Marvin and McCann, Connor M. and Noh, Seonghoon and Fallahi, Omeed and Castillo, Hector and Abraham, Ian and Dollar, Aaron M.},
  pages={7},
  year={2023},
  url={https://adamseewald.cc/short/rb52023},
  note={Submitted for publication}
}
```

## Supplementary material

You can find the code for the approach [here](https://github.com/adamseew/rb5). It is split in multiple repositories:

|Repository|Function|
|---|---|
|[**ground robot**](https://github.com/adamseew/rb5)|`rb5-ground-robot` ROS2 package, which contains the code that runs on the companion computer onboard RB5, i.e., an [NVIDIA (R) Jetson NX (TM)](https://www.seeedstudio.com/reComputer-J2021-p-5438.html)|
|[**ground navigation**](https://github.com/adamseew/rb5-ground-navigation)|`rb5-ground-nav` ROS package, which contains the code that collects point clouds from an RGB-D camera and other data from the SLAM algorithm and ports them into ROS2|
|[**base server**](https://github.com/adamseew/rb5-base-server)|PHP- and JavaScript-based remote control base station that implements the necessary functionality for remote human intervention|
