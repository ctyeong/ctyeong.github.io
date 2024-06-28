---
layout: page
title: Research
permalink: /research/
---

My research centers on the design of innovative machine learning algorithms for practical scenarios with limited datasets and/or constraints on data collection resources.
More specifically, I below describe some of my ongoing interdisciplinary research projects. 
<!-- "sensory" and "motional" behaviors of mobile robots in more "informative" ways for each other.  -->
<!-- In particular, I propose novel *machine learning* approaches to address problems under realistic challenges. 
Several research topics in which I've been directly involved are listed below, but I have a broader interest in improving *autonomy* of *embodied AI systems*. -->

<br />

### Prediction of Unseen Samples
<!-- Synthesis of Realistic Anomalies  -->

I am interested in creating anomaly detectors using "only" normal, typical observations, which are more accessible and cost-effective to obtain. For instance, in the context of automating fruit health monitoring from image data, it can be challenging to collect sufficient samples of unhealthy fruits. Even if you have some examples, completely novel types of disease could arise later, posing new challenges for detection.
To overcome this, I develop methods to leverage the normal samples to *synthesize* hypothetical but realistic examples of anomalies so that these synthetic anomalies can serve as valuable training data for accurate anomaly detection.
In other words, my research aims to enhance monitoring systems by bridging the gap between limited anomaly data and the need for comprehensive anomaly detection solutions.
Specifically, I have shown novel techniques that utilize *self-supervised learning* and *generative adversarial networks* to tackle practical scenarios like *fruit health monitoring* and *ant behavior analysis*. 
<!-- Similarly, taking motions for promoting "outlier" states has also been found useful for speeding-up *robotic learning*! -->

**References:**

- [*Self-supervised Representation Learning for
Reliable Robotic Monitoring of Fruit Anomalies.*](https://arxiv.org/abs/2109.10135){:target="_blank"}
In: Proceedings of the 2022 IEEE International Conference on Robotics and Automation (ICRA 2022).
\[[<span style="color:red">Data</span>](https://github.com/ctyeong/Riseholme-2021){:target="_blank"}\]
\[[<span style="color:red">Code</span>](https://github.com/ctyeong/CH-Rand){:target="_blank"}\].
- [*Beyond Tracking: Using Deep Learning to Discover Novel Interactions in Biological 
Swarms.*](https://link.springer.com/article/10.1007/s10015-022-00753-y){:target="_blank"} 
Journal of Artificial Life and Robotics (AROB). 
\[[<span style="color:red">Data</span>](https://github.com/ctyeong/OpticalFlows_HsAnts){:target="_blank"}\].
- [*Identification of Abnormal States in Videos of Ants Undergoing Social Phase Change.*](https://ojs.aaai.org/index.php/AAAI/article/view/17794){:target="_blank"}
In: Proceedings of the 35th AAAI Conference on Artificial Intelligence (AAAI 2021).
\[[<span style="color:red">Data</span>](https://github.com/ctyeong/OpticalFlows_HsAnts){:target="_blank"}\]
\[[<span style="color:red">Code</span>](https://github.com/ctyeong/IO-GEN){:target="_blank"}\].
<!-- - [*Automatic Discovery of Motion Patterns that Improve Learning Rate in Communication-Limited Multi-Robot Systems.* ](https://ieeexplore.ieee.org/abstract/document/9235218){:target="_blank"}
In: Proceedings of the 2020 IEEE International Conference on Multisensor Fusion and Integration (MFI 2020). -->

<br />

### Active, Informative Sampling

For environmental monitoring, the regular assessment of physical systems is crucial to detect and report changes in air or soil quality, fruit maturity, and more.
To achieve this, embodied agents can serve as valuable tools, but their motions and paths for sensing must be optimized to maximize information gathering while considering operational limitations, such as limited battery life. 
In this project, specifically, I am focused on developing novel *reinforcement learning* algorithms to intelligently guide these agents in selecting the next optimal motions based on current observations. The objective is to collect highly informative data for building accurate models of the environment. 
Through my research, I have achieved promising results, including the development of a path planning method for air-quality mapping. 
In addition, I have created a publicly available agricultural dataset specifically designed to advance the study of *active perception* in fruit monitoring, considering challenging occlusion scenarios. 

<!-- navigate only to most "informative" locations for spatial prediction &mdash; instead of planning to visit every grid cell  &mdash; due to limited resources, such as battery life🔋 and mission time⏰. *Gaussian Process Regression* has been widely used in literature since it enables 1) information-theoretic evaluation of candidate locations and 2) online learning as a new measurement is acquired. My interest lies in integrating such traditional methods with more modern *deep learning* algorithms to better optimise the robotic sampling paths.  -->

**References:**

- [*DAVIS-Ag: A Synthetic Plant Dataset for Prototyping Domain-Inspired Active Vision in Agricultural Robots.*](https://arxiv.org/abs/2303.05764){:target="_blank"} 
In: Proceedings of the 2024 IEEE International Conference on Automation Science and Engineering (CASE 2024).
\[[<span style="color:red">Data</span>](https://github.com/ctyeong/DAVIS-Ag){:target="_blank"}\]

- [*Adaptive Selection of Informative Path Planning Strategies via
Reinforcement Learning.*](https://ieeexplore.ieee.org/document/9568796){:target="_blank"}
In: Proceedings of the 10th European Conference on Mobile Robots (ECMR 2021).

<!-- <br />

## Multi-robot Coordination via Teammate Modeling

A team of robots could do much more than a single robot could. For strategic team maneuvers, *communication* is the key feature for them. What would then be the best way of communication? You can imagine explicit signals of particular messages, but we, as humans, often use "implicit"  communication by, for example, showing some simple gesture👋 with the hope that our co-worker understands what we actually meant by it. For enabling such communication, I've worked on robotic algorithms to model the "mapping" from some *indirect* *observations* to *actual* *motions* of teammates so that individuals after learning could take complementary actions to others'. As an application, I've introduced so-called *Remote Teammate Localization (ReTLo)* problem, in which a robot is to infer poses of distant teammates only from observations of a nearby robot to proactively maneuver for the team. 

**References:**

- [*Learning Local Behavioral Sequences to Better Infer Non-local Properties in Real Multi-robot Systems.*](https://ieeexplore.ieee.org/document/9196728){:target="_blank"} 
In: Proceedings of the 2020 IEEE International Conference on Robotics and Automation (ICRA 2020). 
\[[<span style="color:red">Data</span>](https://github.com/ctyeong/ReTLo){:target="_blank"}\].
- [*Automatic Discovery of Motion Patterns that Improve Learning Rate in Communication-Limited Multi-Robot Systems.* ](https://ieeexplore.ieee.org/abstract/document/9235218){:target="_blank"}
In: Proceedings of the 2020 IEEE International Conference on Multisensor Fusion and Integration (MFI 2020).
- [*Automated Synthesis of Scalable Algorithms for Inferring Non-Local Properties to Assist in Multi-Robot Teaming.*](https://ieeexplore.ieee.org/document/8256320){:target="_blank"} 
In: Proceedings of the 2017 IEEE International Conference on Automation Science and Engineering (CASE 2017).  -->