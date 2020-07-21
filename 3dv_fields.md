# 我们关注的三维视觉研究方向
徐玉华
2020年7月21日
<font color=red size=3>（以下列出的文献，只是一小部分，需要你自己去阅读大量的文献）</font>
### 双目深度估计
自2015年以来，用深度学习做双目深度估计的工作非常多，每年都有重要的进步，关注CVPR/ICCV/ECCV等顶会上的论文。
- Xu H, Zhang J. AANet: Adaptive Aggregation Network for Efficient Stereo Matching. CVPR 2020.
- Žbontar J, LeCun Y. Stereo matching by training a convolutional neural network to compare image patches. The journal of machine learning research, 2016, 17(1): 2287-2318.
- Chang J R, Chen Y S. Pyramid stereo matching network. CVPR 2018: 5410-5418.
- Laga H, Jospin L V, Boussaid F, et al. A Survey on Deep Learning Techniques for Stereo-based Depth Estimation[J]. arXiv preprint arXiv:2006.02535, 2020.
- Tonioni A, Tosi F, Poggi M, et al. Real-time self-adaptive deep stereo. CVPR 2019: 195-204.
- Xu H, Zhang J. AANet: Adaptive Aggregation Network for Efficient Stereo Matching. CVPR 2020: 1959-1968.

### 结构光三维成像
包括散斑结构光和条纹结构光。
条纹结构光关注张松老师的工作（https://scholar.google.com.hk/citations?user=lj9IGg8AAAAJ&hl=zh-CN&oi=ao）。
条纹结构光方面，基于二值条纹图的高速三维成像是近几年的研究热点。

- Fanello S R, Valentin J, Rhemann C, et al. Ultrastereo: Efficient learning-based matching for active stereo systems. CVPR 2017.
- Fanello S R, Valentin J, Kowdle A, et al. Low compute and fully parallel computer vision with hashmatch. ICCV 2017: 3894-3903.
- Bao W, Xiao X, Xu Y, et al. Reference image based phase unwrapping framework for a structured light system[J]. Optics express, 2018, 26(22): 29588-29599.
- S Zhang, PS Huang. Novel method for structured light system calibration. Optical Engineering 45, 083601
- J Xu, S Zhang. Status, challenges, and future perspectives of fringe projection profilometry. Optics and Lasers in Engineering, 2020.


### 实时三维建模
2011年微软的KinectFusion，开启了实时三维场景重建的时代。贝壳找房里面就有三维室内场景重建（据说是用奥比中光的深度传感器做的），这是三维场景的一个成功的应用。
除了几何的重建，还有纹理映射。

- Newcombe R A, Izadi S, Hilliges O, et al. KinectFusion: Real-time dense surface mapping and tracking[C]//2011 10th IEEE International Symposium on Mixed and Augmented Reality. IEEE, 2011: 127-136.
- Dai A, Nießner M, Zollhöfer M, et al. Bundlefusion: Real-time globally consistent 3d reconstruction using on-the-fly surface reintegration[J]. ACM Transactions on Graphics (ToG), 2017, 36(4): 1.
- Zollhöfer M, Stotko P, Görlitz A, et al. State of the Art on 3D Reconstruction with RGB‐D Cameras[C]//Computer graphics forum. 2018, 37(2): 625-652.
- Avetisyan A, Dahnert M, Dai A, et al. Scan2cad: Learning cad model alignment in rgb-d scans[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019: 2614-2623.
- Lee J H, Ha H, Dong Y, et al. TextureFusion: High-Quality Texture Acquisition for Real-Time RGB-D Scanning. CVPR 2020: 1272-1280.

### 三维人体姿态估计
2010年，微软发布XBOX体感游戏机，其中的基于随机森林的三维人体姿态估计做的很好（放在2020年来，仍然是很好）。在国内的企业界，迄今似乎仍无人超越。
现在，可以用深度学习的方法，用RGB/RGB-D/depth图像去做三维姿态估计。
- Shotton J, Fitzgibbon A, Cook M, et al. Real-time human pose recognition in parts from single depth images. CVPR 2011. Ieee, 2011: 1297-1304.
- Martinez J, Hossain R, Romero J, et al. A simple yet effective baseline for 3d human pose estimation. ICCV 2017: 2640-2649.
- Yang W, Ouyang W, Wang X, et al. 3d human pose estimation in the wild by adversarial learning. CVPR 2018.

### 实时非刚性人体重建
非刚性人体重建，清华大学刘烨斌研究组做的很好（http://www.liuyebin.com/）。

### 三维手势估计与跟踪
- Cheng H, Yang L, Liu Z. Survey on 3D hand gesture recognition[J]. IEEE transactions on circuits and systems for video technology, 2015, 26(9): 1659-1673.
- Zimmermann C, Brox T. Learning to estimate 3d hand pose from single rgb images. ICCV 2017.
- Ge L, Ren Z, Li Y, et al. 3d hand shape and pose estimation from a single rgb image. CVPR 2019: 10833-10842.

最后，推荐一个做学术的利器：https://scholar.google.com