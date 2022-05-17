# Spontaneous Facial Expression Recognition on Video Sequences and 3-D Point Clouds using Spatiotemporal Convolutional Neural Networks

Facial expressions are the facial changes in response to a person’s internal emotional state, intention. It is also a 
way of non-verbal communication. Automatic facial expression recognition (FER) is a challenging problem that impacts
essential applications in areas like human–computer interaction (HCI) and data driven animation. 
FER is solved using computer vision and artificial intelligence (AI). 2-D based solutions for FER present difficulties
due to self-occlusion and pose variation. Thus, they are not satisfactory for real-world applications. 3-D data based 
solutions solve the problems that arise with 2-D data. In recent times, 3-D facial data, both 3-D point clouds and video 
sequences have become increasingly available. This report is concerned with facial expression recognition for two types of data: 
1) Videos 
2) 3-D point clouds, using 3-D convolutional neural networks (3-D CNN).

## Data
### BAUM1-s Video Data
<img src="https://github.com/anerip98/spontaneous-facial-expression-recognition/blob/main/images/baum1s.png" width=800>

### 3-D Point Clouds

<img src="https://github.com/anerip98/spontaneous-facial-expression-recognition/blob/main/images/voxel.png" width=800>

## Results - Confusion Matrices

### BAUM1-s Video Data

<img src="https://github.com/anerip98/spontaneous-facial-expression-recognition/blob/main/images/video_conf.png" width=600>

### 3-D Point Clouds
<img src="https://github.com/anerip98/spontaneous-facial-expression-recognition/blob/main/images/point_cloud_conf.png" width=600>

## Conclusions

Experimental results on the BAUM-1s database show that FER under unconstrained situations is quite challenging.
To reduce the computation and memory costs of using 3-D data, 3-D FER can be performed by mapping the 3-D facial
surface onto a 2-D plane. The depth image from the point cloud is computed. A depth image is one where the value
of each pixel in the x − y plane is set to the corresponding z co-ordinate of the 3-D co-ordinate in the point cloud.
Existing 3-D CNN architectures and methods are unable to completely exploit and assimilate the information in 3-D
data [45]. Despite the advance in 3-D algorithms, uni-modal solutions still have drawbacks that make pure 3-D approaches
satisfactory only for some applications. These limitations can be overcome by implementing multi-modal 2D+3D analysis
Most FER research has been conducted on the six basic facial expressions: anger, disgust, fear, happiness,
sadness, and surprise. Other emotions also need to be considered to develop algorithms that can generalize better.

## References:
[1] H. Li, J. Sun, Z. Xu, and L. Chen, “Multimodal 2d+ 3d facial expres-
sion recognition with deep fusion convolutional neural network,” IEEE
Transactions on Multimedia, vol. 19, no. 12, pp. 2816–2831, 2017.

[2] F. Nonis, N. Dagnes, F. Marcolin, and E. Vezzetti, “3d approaches
and challenges in facial expression recognition algorithms—a literature
review,” Applied Sciences, vol. 9, no. 18, p. 3904, 2019.

[3] S. Zhalehpour, O. Onder, Z. Akhtar, and C. E. Erdem, “Baum-1: A
spontaneous audio-visual face database of affective and mental states,”
IEEE Transactions on Affective Computing, vol. 8, no. 3, pp. 300–313,
2016

[4] D. Tran, L. Bourdev, R. Fergus, L. Torresani, and M. Paluri, “Learning
spatiotemporal features with 3d convolutional networks,” in Proceedings
of the IEEE international conference on computer vision, 2015, pp.
4489–4497.
