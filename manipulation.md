# Todo list

Multi-scale context aggregation by dilated convolutions

Learning synergies between pushing and grasping with self-supervised deep reinforcement learning

Contactnets: Learning discontinuous contact dynamics with smooth, implicit representations.

# embodied-ai-paper

Research paper reading on embodied ai

Learning to Prompt for Vision-Language Models

解读1: https://zhuanlan.zhihu.com/p/422408815
解读2: https://blog.csdn.net/weixin_50917576/article/details/137870975

Neural Discrete Representation Learning (VQ-VAE)

解读1: https://zhuanlan.zhihu.com/p/658095745
解读2: https://zhuanlan.zhihu.com/p/72738517

straight-through estimator
[深度生成模型以及模型不可导问题的处理方法](https://zhuanlan.zhihu.com/p/617116528)


goal-conditioned policies: (involves the user providing a goal-image from the scene)

# End-to-end models(pixels2actions)

S. Levine, C. Finn, T. Darrell, and P. Abbeel. End-to-end training of deep visuomotor policies. The Journal of Machine Learning Research (JMLR), 2016.

D. Kalashnikov, A. Irpan, P. Pastor, J. Ibarz, A. Herzog, E. Jang, D. Quillen, E. Holly, M. Kalakrishnan, V. Vanhoucke, et al. Qt-opt: Scalable deep reinforcement learning for vision-based robotic manipulation. Conference on Robot Learning (CoRL), 2018.

# Object-centric models

## object keypoints

L. Manuelli, W. Gao, P. Florence, and R. Tedrake. kpam: Keypoint affordances for category-level robotic manipulation. International Symposium on Robotics Research (ISRR), 2019.

T. D. Kulkarni, A. Gupta, C. Ionescu, S. Borgeaud, M. Reynolds, A. Zisserman, and V. Mnih. Unsupervised learning of object keypoints for 
perception and control. NeurIPS, 2019.

A. Nagabandi, K. Konolige, S. Levine, and V. Kumar. Deep dynamics models for learning dexterous manipulation. Conference on Robot Learning (CoRL), 2020.

X. Liu, R. Jonschkowski, A. Angelova, and K. Konolige. Keypose: Multi-view 3d labeling and keypoint estimation for transparent objects. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2020.

## embeddings
O. Mees, N. Abdo, M. Mazuran, and W. Burgard. Metric learning for generalizing spatial relations to new objects. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2017.

P. Jund, A. Eitel, N. Abdo, and W. Burgard. Optimization beyond the convolution: Generalizing spatial relations with end-to-end metric learning. IEEE International Conference on Robotics and Automation (ICRA), 2018.

## dense descriptors
P. R. Florence, L. Manuelli, and R. Tedrake. Dense object nets: Learning dense visual object descriptors by and for robotic manipulation. Conference on Robot Learning (CoRL), 2018.

P. Florence, L. Manuelli, and R. Tedrake. Self-supervised correspondence in visuomotor policy learning. IEEE Robotics and Automation Letters (RA-L), 2019.

P. Sundaresan, J. Grannen, B. Thananjeyan, A. Balakrishna, M. Laskey, K. Stone, J. E. Gonzalez, and K. Goldberg. Learning rope manipulation policies using dense object descriptors trained on synthetic depth data. IEEE International Conference on Robotics and Automation (ICRA), 2020.



[2020] Transporter Networks: Rearranging the Visual World for Robotic Manipulation
只考虑immobilizing grasp(suction gripper)，你就会发现pick和place的位置是一个关于pixel的distribution
benefits: 1. handle unseen objects; 2. handle deformable objects; 3.handle uncaountable piles of small objects.
比较适合spatially consistent 的物体，可以简化训练的时候数据增强的难度，对于一些perspective images，外观会随着相机的视角或者lens property而变换，你就需要去重建他的外形