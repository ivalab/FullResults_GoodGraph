### Devices
- Desktop (passmark 2584, 95W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i7-7700K+%40+4.20GHz&id=2874
- Jetson TX2 (-, 7.5W) https://www.phoronix.com/scan.php?page=article&item=march-2017-arm&num=2

### Benchmark
- EuRoC Stereo-Inertial https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets
- UZH FPV Stereo-Inertial http://rpg.ifi.uzh.ch/uzh-fpv.html

### VO/VSLAM/VINS Systems Assessed

Vision-only Systems:
- GF-ORB-SLAM Stereo with Good Graph BA [https://github.com/ivalab/gf_orb_slam2]
- GF-ORB-SLAM Stereo with sliding window BA [same as above]
- GF-ORB-SLAM Stereo with co-visiblity BA [same as above]
- GF-ORB-SLAM Stereo with Canonical Local BA [same as above]
- ORB-SLAM Stereo with Canonical Local BA [same as above]
- SVO Stereo https://github.com/YipuZhao/rpg_svo

Visual-Inertial Systems:
- VINS-Fusion https://github.com/YipuZhao/VINS-Fusion
- ICE-BA https://github.com/YipuZhao/ICE-BA
- MSCKF Stereo https://github.com/YipuZhao/msckf_vio

Compared to the official repos, the baseline methods in my repo are with explicit logging on pose tracking and time cost.


## References

	@article{zhao2019graph,
	  title={Good Graph to Optimize: Cost-Effective, Budget-Aware Bundle Adjustment in Visual SLAM},
	  author={Zhao, Yipu and Vela, Patricio A.},
	  journal={submitted to IEEE Transactions on Robotics},
	  year={2020}
	}	

## Contact information

- Yipu Zhao		yipu.zhao@gatech.edu
- Patricio A. Vela	pvela@gatech.edu
