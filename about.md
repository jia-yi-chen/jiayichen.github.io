---
layout: page
title: About
permalink: /about/
---



<a name="proj"></a>
## **Projects (ML/AI directions)**

<!-- Overview -->


<!-- <p style="padding-left: 35px;"> <b>Since 2018</b>:</p> -->

<!-- #### **Since 2018**: -->
<!-- - **Learning from Multimodal, Multi-view, and Heterogeneous Data** 
  - Work1: Heterogeneous **graph neural network**  for incomplete multimodal data analysis.
  - Work2: Context-guided task-heterogeneous meta-learning approach to solve **few-shot learning** across modalities. 
  - Work3: Dealing with few-shot tasks with a hybrid of data structures, and propose graph-based semi-supervised meta-learner to generalize and specialize the underlying geometric structure of few-shot data alignment task. -->
- **Disentanglement for Partially-observed Multimodal Spatiotemporal Interactions** (08/2022-Present)
  - *Keywords*: *Deep Generative Models*, Longititude Temporal *Variational Autoencoders*, Disentangled Representation Learning, Gaussian Processes, Spatiotemporal, Latent Space Graph, Human Motion Understanding ([Mocap](http://mocap.cs.cmu.edu/])), Partial Observations, Imputation
  - *Publication*: under review
- **Privacy-preserving Few-shot learning with Hetergeneous Domain Shifts across Different Modalities** (11/2021-05/2022)
  - *Keywords*: Multiple Modalities, *Federated* Multitask Learning, On-device Training, Server-client Interaction, *Domain Shifts*, Small Dataset, Partial Observations, Model Transferability 
  - *Publication*: **Jiayi Chen**, Aidong Zhang. "FedMSplit: Correlation Adaptive Federated Multitask Learning over Multimodal Split Networks". The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD**), 2022. (research track) (acceptance rate: 254/1695=14.99%) [[PDF](https://doi.org/10.1145/3534678.3539384)]
- **Heterogeneous Graph Neural Network for Incomplete Multimodal Data Analysis** (09/2019-05/2020)
  - *Keywords*: Multimedia (Video, Language, and Audio), Graph Neural Networks, Partial Observations 
  - *Publication*: **Jiayi Chen**, Aidong Zhang. "HGMF: Heterogeneous Graph-based Fusion for Multimodal Data with Incompleteness". ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD**), 2020. (research track) (acceptance rate: 216/1279=16.89%) [[PDF](https://doi.org/10.1145/3394486.3403182)]
- **Context-guided Meta-Learning Approach for Few-shot Learning Across Modalities** (05/2020-02/2021)
  - *Keywords*: Multiple Modalities, Knowledge distillation, Model Transferability, Few-shot Learning, Meta-learning, Domain Shifts, Partial Observations
  - *Publication*: **Jiayi Chen**, Aidong Zhang. "HetMAML: Task-heterogeneous Model-agnostic Meta-learning for Few-shot Learning Across Modalities". ACM International Conference on Information and Knowledge Management (**CIKM**), 2021. (full paper) (acceptance rate: 271/1251=21.66%) 
- **Generalizing Topological Structure of Task in Hybrid Few-shot Classification** (08/2020-07/2021)
  - *Keywords*: Multiple Modalities, Graph Neural Networks, Few-shot Learning, Meta-learning, Domain Shifts, Partial Observations, Semi-supervised Learning
  - *Publication*: **Jiayi Chen**, Aidong Zhang. "Adaptive Topological Transduction for Hybrid Few-shot Learning". The ACM International World Wide Web Conference (**WWW**) 2022. 
- **Deep Reinforcement Learning for Human-like Car-Following System** 
  - Built an actor-critic reinforcement learning framework to learn an optimal car-following behavior from empirical data; implemented deep deterministic policy gradient algorithm to learn the continuous-control policy network.
  - *Tools*: Python, PyTorch
- **GNNMutation: A Mutation Tool for Graph Neural Networks** 
  - Proposed a novel mutator to inject faults into GNN models, including eight node/edge-level mutation operators.
  - *Tools*: Python, PyTorch
- **Controllable Text Generation via Generative Adversarial Network** 
  - *Keywords*: Natural Language Generation, conditional GANs, VAEs, Reinforcement Learning
  - Implemented a conditional GAN to generate realistic-looking sentences whose attributes (e.g., emotion in sentences) can be controlled; collected social media texts and split them by emotion annotations; trained the RNN-based generator and discriminator adversarially, using the idea of reinforcement learning to maximize the rewards from discriminator.
  - *Tools*: Python, PyTorch, Tensorflow

<div class="masthead" style="margin-top: -25px;margin-bottom: -15;"> </div>
<!-- <p style="padding-left: 35px;"> <b>Before 2018</b>:</p> -->
<!-- #### **Before 2018**: -->
## **Projects (CV/CG directions)**

- **Artwork Generation for 3D Scene Models based on Computer Vision & Graphics** 
  - Studied human knowledge-guided *Neural Style Transfer*, focusing on improving the illusion of space in generated images by simulating how artists use their skills to observe and reproduce a 3D scene (e.g., geometric structures, lighting and shallow); also studied 3D non-photorealistic rendering based on the neural style transfer paradigm.
  - Created a 3D-2D dataset, including 3D models rendered by multiple types of lighting (using Autodesk Maya), 2D photos annotated by lighting and segmentation (by Photoshop and Matlab), and a hand-drawn stylistic material for testing (by CorelPainter).
  - Proposed an illumination-guided deep alignment method based on CNN, Lighting Path Expression, and PatchMatch (Keras, Python).
- **Traffic-scene Image Enhancement** 
  - Proposed a fast, detail-enhanced, and halo-free method to simultaneously correct the over- and under-exposure problem in LDR images, which widely exists in traffic-scene images in our smart-vehicle vision system.
- **Efficient Human Action Recognition based on Video-Compression Domain** 
  - Extracted motion vectors (MV) and DCT from MPEG-4 video bitstreams.
  - Proposed to fast detect Spatial-Temporal Interest Points from video bitstream using MV and DCT, instead of from the decoded video, and then formed action features using BoW and GMM.
  - Trained traditional ML classifiers-decision tree, Naive Bayes, and SVM.
  - *Tools*: Matlab, C++, OpenCV, ffmpeg, Linux.



<div class="masthead" style="margin-top: -25px;margin-bottom: -15;"> </div>

## **Projects (Robotics direction)**

- **TurtleBot Autonomous Security Guard** 
  - Built an autonomous framework on TurtleBot to act as a human security guard—wandering, finding AprilTag targets, approaching each target, aiming and then shooting the target with a motorized toy gun installed on TurtleBot. 
  - Developed the target searching/ranking, goal-position and gun-pitch calculation, and go-to-goal functions.
  - *Tools*: Robotic Operating System (ROS), C++,  Python, Linux


- **Drone Vision-guided Autonomous Navigation & Search-and-rescue System** 
  - Centered around a mission making the drone to complete a search-and-rescue task. Participants are tasked with building an app that enables a drone to autonomously take-off from a moving vehicle, collect data in a survivors searching area, and finally track and land on the moving vehicle.
  - Developed a real-time vision-based module on drone system for Object Detection and 3D Localization, computing the 3D poses of objects from 2D images using real-time camera gimbal, Homography and 3D Transformation (C++).
  - Developed a PID-based autonomous tracking-and-landing module for landing on a moving vehicle, and developed the workflow module to manage the multiple modules simultaneously running on the drone (ROS, Python, Linux).
  - Won the 4th place from 130+ international teams in “2016 DJI Developer Challenge”, NY, USA (as a team of three).
  - *Tools*: Robotic Operating System (ROS), C++,  Python, Linux

<div class="masthead" style="margin-top: -25px;margin-bottom: -15;"> </div>


<!-- *Back to [CV](/CV#proj).* -->

<!-- *Go to [Homepage](/#award).* -->

