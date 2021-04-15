# Federico Taschin
My main interest is Reinforcement Learning, with particular focus on Distributional RL, Goal-Conditioned RL, and Hierarchical RL. My goal is to become a researcher in the field, and I am currently looking for PhD opportunities. My life in brief:

- 2019 - Today: **Machine Learning** Master student at [KTH Royal Institute of Technology](https://www.kth.se/en). Research-oriented Master program where I first met and fell in love with Reinforcement Learning. Particular focus of the program is on Deep Learning, and I developed several implementations of deep architectures such as CNNs, RNNs, and [HGNs](https://github.com/CampusAI/Hamiltonian-Generative-Networks)), as well as Deep RL algorithms like [ACER](https://github.com/fedetask/ACER-torch) and [Categorical DQN](https://github.com/fedetask/categorical-dqn).
- 2019 - Today: **Driverless Engineer** at [KTH Formula Student](https://www.kthformulastudent.se/). The goal of KTH Formula Student is to develop an autonomous electric racing car. I joined at the beginning of my Master studies in the SLAM (Simultaneous Localisation and Mapping) subgroup. After an initial study of SLAM algorithms, my first contribution was a core implementation of [GraphSLAM](http://robots.stanford.edu/papers/thrun.graphslam.pdf). Having gained a good knowledge of the SLAM software and of the overall driverless system, I had a substantial part in the recruiting process of new members for the driverless team in early 2020, interviewing > 15 candidates with responsibilities in the decisional process, and oversighted the integration of new members in the SLAM group. From February 2020 to February 2021 I covered the role of **Technical Integrator** of the Driverless team, supervising integration of software modules developed by subgroups in the racing car.  Currently, I am working on improving the legacy implementation of [FastSLAM](http://robots.stanford.edu/papers/Montemerlo03a.pdf), and I developed a Python library to compute evaluation metrics of the SLAM performances in order to track the level of improvement of new features.
- 2018 - 2019: **Embedded Software Developer Intern** at [Profitap](https://www.profitap.com/). During the internship I gained a lot of valuable experience in C and C++ developing, as well as best practices of development such as documentation, testing, version control, and continuous integration. I developed a PAM authentication module in C and a SNMP protocol implementation in C++ for network devices. I developed a Bash library for Continuous Integration to efficiently handle dependencies and versioning in several projects.
- 2015 - 2018: Bachelor Degree in **Computer Engineering** at [Università degli Studi di Padova](https://www.unipd.it/). 


## Publications
2021, **[Re] Hamiltonian Generative Networks**, *Carles Balsells Rodas, Oleguer Canal, Federico Taschin*, Accepted for publication in Re Science C. [OpenReview page](https://openreview.net/forum?id=Zszk4rXgesL) 


## Non published works and projects
 - 2020 [[Re] Hamiltonian Generative Networks](https://github.com/CampusAI/Hamiltonian-Generative-Networks): Implementation of the paper "[Hamiltonian Generative Networks](https://iclr.cc/virtual_2020/poster_HJenn6VFvB.html)". Learning Hamiltonian dynamics from videos of simulated physical systems. We provided the first open-source implementation of the algorithm, reproduced the original experiments, performed additional experiments on new environments, and proposed a baseline comparison.
- 2020 [Self-learned vehicle control using PPO](https://github.com/fedetask/my-works/tree/main/self-driving): Learn to control a car and a drone in simulation using Reinforcement Learning (PPO). We perform path planning on the visibility graph and make the vehicles learn to follow the waypoints as fast as possible. Our code won the competition against other 15 groups.
- 2020 [Neural Network Surgery in Deep Reinforcement Learning](https://campusai.github.io/experiments/nn_surgery): Extensive analysis and evaluation of performing weight transfer in Deep RL models when the model changes, for example, when actions, observations, or hidden layers are added. This avoids re-training a model when the we apply modifications to it, resulting in better performances and less training time.  
- 2019 [[Re] Gaussian Process Latent Variable Model](https://github.com/OleguerCanal/GPLVM): Implementation of the paper [Gaussian process models for visualisation of high dimensional data](https://proceedings.neurips.cc/paper/2003/file/9657c1fffd38824e5ab0472e022e577e-Paper.pdf). We implement the GPLVM model and evaluate it on the paper's datasets plus some additional ones. We perform an extensive comparison of the model against other dimensionality reduction techniques such as PCA and Kernel PCA.
- 2019 [Cooperative Multi-Agent AI](https://github.com/fedetask/my-works/tree/main/cooperative-agents): We deal with multi-agent tasks such as search, vehicle routing, and formation sweeping. We exploit a combination of classic spanning tree, routing, and formation algorithms and improve on them with efficient evolutionary algorithms. Overall, our group performed best on the 4 benchmark tasks among the 12 participant groups. 
- 2018 [Analysis of a Dermatoscopic Dataset](https://github.com/fedetask/my-works/tree/main/analysis-dermatoscopic), **Bachelor Thesis**: Application of Image Segmentation techniques to images of melanocytic lesions, extrcting their shape and size and analyzing the data.

## Website
[CampusAI](https://campusai.github.io/): Created with [Oleguer Canal](https://github.com/OleguerCanal), we publish content related to Machine Learning and Reinforcement Learning.
