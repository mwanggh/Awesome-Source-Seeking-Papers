# Awesome Source Seeking Papers

**Gas Source Seeking/Odor Source Localization** refers to the process where autonomous robots actively search for gas leak sources in complex environments using sensor measurements. This repository includes single-robot, multi-robot, and review papers in this field.

## Single-robot



### Controlling a gas/odor plume-tracking robot based on transient responses of gas sensors

Author: Ishida, H.; Nakayama, G.; Nakamoto, T.; Moriizumi, T.

Publication Year: 2005

Publication Title: IEEE Sensors Journal

Abstract: Gas sensors provide an artificial sense of smell for a mobile robot to track an airborne gas/odor plume and locate its source. However, a slow response of gas sensors has been the major factor limiting the development of plume-tracking robots. This paper describes a new control algorithm that breaks the limitation. The basic idea is to detect onsets of gas sensor response and starts of recovery by monitoring the relative change in each sensor output. Fast plume tracking is accomplished by making the robot take appropriate actions immediately when the sensor outputs start changing from one state to another. Growing sensor outputs evoke an increase in the robot speed for further acceleration of plume tracking, whereas insufficient sensor outputs slow down the robot to avoid degrading the search success rate. In contrast to the previous algorithm, based on the absolute sensor output levels, the detection of output change also leads to reliable plume detection, since it is insusceptible to drift in the gas sensor outputs. Experimental results have shown that the robot can track down a gas source within the distance of 2 m in 32 s, even though semiconductor gas sensors with a long recovery time (>60 s) are used.

URL: https://ieeexplore.ieee.org/abstract/document/1430708



### Moth-inspired chemical plume tracing on an autonomous underwater vehicle

Author: Li, Wei; Farrell, J.A.; Pang, Shuo; Arrieta, R.M.

Publication Year: 2006

Publication Title: IEEE Transactions on Robotics

Abstract: This paper presents a behavior-based adaptive mission planner (AMP)to trace a chemical plume to its source and reliably declare the source location. The proposed AMP is implemented on a REMUS autonomous underwater vehicle (AUV)equipped with multiple types of sensors that measure chemical concentration,the flow velocity vector, and AUV position, depth, altitude, attitude, and speed. This paper describes the methods and results from experiments conducted in November 2002 on San Clemente Island, CA, using a plume of Rhodamine dye developed in a turbulent fluid flow (i.e., near-shore ocean conditions). These experiments demonstrated chemical plume tracing over 100 m and source declaration accuracy relative to the nominal source location on the order of tens of meters. The designed maneuvers are divided into four behavior types: finding a plume,tracing the plume, reacquiring the plume, and declaring the source location. The tracing and reacquiring behaviors are inspired by male moths flying up wind along a pheromone plume to locate a sexually receptive female. All behaviors are formulated by perception and action modules and translated into chemical plume-tracing algorithms suitable for implementation on a REMUS AUV. To coordinate the different behaviors, the subsumption architecture is adopted to define and arbitrate the behavior priorities. AUVs capable of such feats would have applicability in searching for environmentally interesting phenomena, unexploded ordnance, undersea wreckage, and sources of hazardous chemicals or pollutants.

URL: https://ieeexplore.ieee.org/abstract/document/1618529



### An artificial moth: Chemical source localization using a robot based neuronal model of moth optomotor anemotactic search

Author: Pyk, Pawel; Bermúdez i Badia, Sergi; Bernardet, Ulysses; Knüsel, Philipp; Carlsson, Mikael; Gu, Jing; Chanie, Eric; Hansson, Bill; Pearce, Tim; Verschure, Paul

Publication Year: 2006

Publication Title: Auton Robot

Abstract: Robots have been used to model nature, while nature in turn can contribute to the real-world artifacts we construct. One particular domain of interest is chemical search where a number of efforts are underway to construct mobile chemical search and localization systems. We report on a project that aims at constructing such a system based on our understanding of the pheromone communication system of the moth. Based on an overview of the peripheral processing of chemical cues by the moth and its role in the organization of behavior we emphasize the multimodal aspects of chemical search, i.e. optomotor anemotactic chemical search. We present a model of this behavior that we test in combination with a novel thin metal oxide sensor and custom build mobile robots. We show that the sensor is able to detect the odor cue, ethanol, under varying flow conditions. Subsequently we show that the standard model of insect chemical search, consisting of a surge and cast phases, provides for robust search and localization performance. The same holds when it is augmented with an optomotor collision avoidance model based on the Lobula Giant Movement Detector (LGMD) neuron of the locust. We compare our results to others who have used the moth as inspiration for the construction of odor robots.

URL: https://link.springer.com/article/10.1007/s10514-006-7101-4



### 'Infotaxis' as a strategy for searching without gradients

Author: Vergassola, Massimo; Villermaux, Emmanuel; Shraiman, Boris I.

Publication Year: 2007

Publication Title: Nature

Abstract: Chemotactic bacteria are guided towards the source of a nutrient by local concentration gradients. That works on the microscopic scale, but at larger scales such local cues are unreliable pointers — for example, wind or water currents may disperse odours sought by foraging animals. Using statistical techniques, Vergassola et al. have developed a general search algorithm for movement strategies based on the detection of sporadic cues and partial information. The strategy, termed 'infotaxis' as it maximizes the expected rate of information gain, could find application in the design of 'sniffer' robots.

URL: https://www.nature.com/articles/nature05464



### SPIRAL: A novel biologically-inspired algorithm for gas/odor source localization in an indoor environment with no strong airflow

Author: Ferri, Gabriele; Caselli, Emanuele; Mattoli, Virgilio; Mondini, Alessio; Mazzolai, Barbara; Dario, Paolo

Publication Year: 2009

Publication Title: Robotics and Autonomous Systems

Abstract: This work describes the design and experimental results of an algorithm, designed to localize a gas source in an indoor environment with no strong airflow by using an autonomous agent. This condition exacerbates the patchiness and intermittency of odor distribution, typical of turbulent flows in the presence of strong mean flows. Furthermore, no information about the wind can be used to detect the position of the source. In the approach proposed here, the robot moves along spirals. A spiral can be reset and a new one started, based on the information acquired about gas distribution. This enables the robot to get close to the ejecting source, without relying on airflow measurements. Results from experiments are also described and discussed, to assess the efficiency of the proposed method.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0921889008001073



### Odor source localization using a mobile robot in outdoor airflow environments with a particle filter algorithm

Author: Li, Ji-Gong; Meng, Qing-Hao; Wang, Yang; Zeng, Ming

Publication Year: 2011

Publication Title: Autonomous Robots

Abstract: This paper discusses odor source localization (OSL) using a mobile robot in an outdoor time-variant airflow environment. A novel OSL algorithm based on particle filters (PF) is proposed. When the odor plume clue is found, the robot performs an exploratory behavior, such as a plume-tracing strategy, to collect more information about the previously unknown odor source. In parallel, the information collected by the robot is exploited by the PF-based OSL algorithm to estimate the location of the odor source in real time. The process of the OSL is terminated if the estimated source locations converge within a given small area. The Bayesian-inference-based method is also performed for comparison. Experimental results indicate that the proposed PF-based OSL algorithm performs better than the Bayesian-inference-based OSL method.

URL: https://link.springer.com/article/10.1007/s10514-011-9219-2



### A study of cognitive strategies for an autonomous search

Author: Ristic, Branko; Skvortsov, Alex; Gunatilaka, Ajith

Publication Year: 2016

Publication Title: Information Fusion

Abstract: Cognitive search is a collective term for search strategies based on information theoretic rewards required in sequential decision making under uncertainty. The paper presents a comparative study of cognitive search strategies for finding an emitting source of unknown strength using sparse sensing cues in the form of occasional non-zero sensor measurements. The study is cast in the context of an emitting source of particles transported by turbulent flow. The search algorithm, which sequentially estimates the source parameters and the reward function for motion control, has been implemented using the sequential Monte Carlo method. The distribution of the search time has been explained by the inverse Gaussian distribution.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1566253515000597



### Entrotaxis as a strategy for autonomous search and source reconstruction in turbulent conditions

Author: Hutchinson, Michael; Oh, Hyondong; Chen, Wen-Hua

Publication Year: 2018

Publication Title: Information Fusion

Abstract: This paper proposes a strategy for performing an efficient autonomous search to find an emitting source of sporadic cues of noisy information. We focus on the search for a source of unknown strength, releasing particles into the atmosphere where turbulence can cause irregular gradients and intermittent patches of sensory cues. Bayesian inference, implemented via the sequential Monte Carlo method, is used to update posterior probability distributions of the source location and strength in response to sensor measurements. Posterior sampling is then used to approximate a reward function, leading to the manoeuvre to where the entropy of the predictive distribution is the greatest. As it is developed based on the maximum entropy sampling principle, the proposed framework is termed as Entrotaxis. We compare the performance and search behaviour of Entrotaxis with the popular Infotaxis algorithm, for searching in sparse and turbulent conditions where typical gradient-based approaches become inefficient or fail. The algorithms are assessed via Monte Carlo simulations with simulated data and an experimental dataset. Whilst outperforming the Infotaxis algorithm in most of our simulated scenarios, by achieving a faster mean search time, the proposed strategy is also more computationally efficient during the decision making process.

URL: https://www.sciencedirect.com/science/article/pii/S1566253517301811



### Design and Performance Evaluation of an Infotaxis-Based Three-Dimensional Algorithm for Odor Source Localization

Author: Ruddick, Julian; Marjovi, Ali; Rahbar, Faezeh; Martinoli, Alcherio

Publication Year: 2018

Publication Title: 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Abstract: In this paper we tackle the problem of finding the source of a gaseous leak with a robot in a three-dimensional (3-D) physical space. The proposed method extends the operational range of the probabilistic Infotaxis algorithm [1] into 3-D and makes multiple improvements in order to increase its performance in such settings. The method has been tested systematically through high-fidelity simulations and in a wind tunnel emulating realistic conditions. The impact of multiple algorithmic and environmental parameters has been studied in the experiments. The algorithm shows good performance in various environmental conditions, particularly in high wind speeds and different source release rates.

URL: https://ieeexplore.ieee.org/abstract/document/8593997



### Design and Performance Evaluation of a Particle Filter-based Algorithm for Smoke Plume Path Tracking

Author: Chen, Xinxing; Huang, Jian

Publication Year: 2019

Publication Title: 2019 IEEE 4th International Conference on Advanced Robotics and Mechatronics (ICARM)

Abstract: We handle the problem of tracing the particulate matter plumes from a smoke source with a mobile robot equipped with a laser particle counter-based smoke sensor in this paper. The proposed method is developed from a particle filter-based chemical odor source localization algorithm and makes a few modifications to adapt it to smoke plumes. Based on the differences between particulate smoke plumes and chemical plumes in terms of distribution, we build a general smoke plume path model used to update particle weight in the particle filter-based algorithm. We also let the algorithm change its observation threshold adaptively according to the robot's history measurement values. The algorithm is evaluated in two different simulation environments, with an uniform airflow field and a space-variant airflow field respectively. The proposed algorithm shows good performance in both environments regardless of the location of the starting position of the robot.

URL: https://ieeexplore.ieee.org/document/8834337



### Particle Source Localization With a Low-Cost Robotic Sensor System: Algorithmic Design and Performance Evaluation

Author: Chen, Xinxing; Marjovi, Ali; Huang, Jian; Martinoli, Alcherio

Publication Year: 2020

Publication Title: IEEE Sensors Journal

Abstract: In this paper we tackle the problem of finding the source of particulate matter with a mobile robot equipped with a low-cost multi-channel optical particle counting sensor. The proposed method is based on the Infotaxis odor source localization algorithm and makes multiple modifications to adapt it to particle plumes. In particular, we propose three simple but efficient ways to fuse multiple probability maps associated with various particle sizes and use the resulted integrated map to guide the robot's movements. A refined measurement data collection is conducted in a wind tunnel to fit the particle plume model. The method with three proposed integration strategies is evaluated in simulation and in the wind tunnel emulating realistic environmental conditions in a repeatable fashion. In particular, we have investigated the impact of two environmental parameters - the wind speed and source release rate on the algorithm performance. The proposed algorithm with the weighted multi-modality map integration strategy outperforms the original Infotaxis and the other two variants. In high wind speed, the proposed algorithm is able on average to estimate the source location with less than 1 meter error in the 80 m2 wind tunnel arena.

URL: https://ieeexplore.ieee.org/abstract/document/9116939



### A Bayesian approach for gas source localization in large indoor environments

Author: Prabowo, Yaqub Aris; Ranasinghe, Ravindra; Dissanayake, Gamini; Riyanto, Bambang; Yuliarto, Brian

Publication Year: 2020

Publication Title: 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Abstract: The main contribution of this paper is a probabilistic estimator that assists a mobile robot to locate a gas source in an indoor environment. The scenario is that a robot equipped with a gas sensor enters a building after the gas is released due to a leak or explosion. The problem is discretized by dividing the environment into a set of regions and time into a set of time intervals. Likelihood functions describing the probability of obtaining a certain gas concentration measurement at a given location at a given time interval are assembled using data generated with GADEN, a three-dimensional gas dispersion simulator([1]). Given a measurement of the gas concentration is available, Bayes's rule is used to compute the joint probability density describing the location of the gas source and the time at which it started spreading. To illustrate the estimation process, a relatively simple motion planner that directs the robot towards the most likely gas source location using a cost function based on the marginal probability of the gas source location is used. The motion plan is periodically revised to reflect the latest posterior probability density. Simulation experiments in a large air-conditioned building with turbulence and wind are presented to demonstrate the effectiveness of the proposed technique.

URL: https://ieeexplore.ieee.org/abstract/document/9341747



### Searching the diffusive source in an unknown obstructed environment by cognitive strategies with forbidden areas

Author: Zhao, Yong; Chen, Bin; Zhu, Zhengqiu; Chen, Feiran; Wang, Yiduo; Ji, Yatai

Publication Year: 2020

Publication Title: Building and Environment

Abstract: Using sensing robots (searchers) to search for the diffusive source in indoor environments is a common and vital task in human society. Such environments, however, are always obstructed by some obstacles, and sometimes the prior information of obstacles is unknown. To solve the source searching problem in the random obstructed environment, this paper formalizes a general model (i.e. the structured map), in which random obstacles are denoted by obstructed cells. Then, we employ cognitive strategies to guide the searcher to perform the search, which are only employed in the environment without obstacles before. To prevent the searcher from being trapped by obstacles, we devise a passive escaping mechanism that marks some explored areas as forbidden areas. Once an area is marked, it cannot be reached by the searcher anymore. Two up-to-date cognitive strategies, i.e. Infotaxis and Entrotaxis are combined with the proposed mechanism to form the hybrid strategies: IWFA (Infotaxis with forbidden areas) and EWFA (Entrotaxis with forbidden areas). Each of them has four variants. The experimental results reveal the superiority of the hybrid strategies: IWFA-II and EWFA-II (two variants) achieve an improvement by a maximum of 28% and 27% in success rate, respectively, compared to their original strategies. The effectiveness of the hybrid strategies is also verified in the obstructed environment generated by the computational fluid dynamics (CFD) software, FLUENT, which considers the effect of obstacles on the diffusion of leaked substances. These findings show important practicality in our proposed hybrid strategies for actual search missions.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132320307186



### Towards Fast Plume Source Estimation with a Mobile Robot

Author: Magalhães, Hugo; Baptista, Rui; Macedo, João; Marques, Lino

Publication Year: 2020

Publication Title: Sensors

Abstract: The estimation of the parameters of an odour source is of high relevance for multiple applications, but it can be a slow and error prone process. This work proposes a fast particle filter-based method for source term estimation with a mobile robot. Two strategies are implemented in order to reduce the computational cost of the filter and increase its accuracy: firstly, the sampling process is adapted by the mobile robot in order to optimise the quality of the data provided to the estimation process; secondly, the filter is initialised only after collecting preliminary data that allow limiting the solution space and use a shorter number of particles than it would be normally necessary. The method assumes a Gaussian plume model for odour dispersion. This models average odour concentrations, but the particle filter was proved adequate to fit instantaneous concentration measurements to that model, while the environment was being sampled. The method was validated in an obstacle free controlled wind tunnel and the validation results show its ability to quickly converge to accurate estimates of the plume’s parameters after a reduced number of plume crossings.

URL: https://www.mdpi.com/1424-8220/20/24/7025



### Combining particle filter algorithm with bio-inspired anemotaxis behavior: A smoke plume tracking method and its robotic experiment validation

Author: Chen, Xinxing; Huang, Jian

Publication Year: 2020

Publication Title: Measurement

Abstract: The smoke source localization robot is a safe substitution of human and animal rescuers in many dangerous search and rescue mission. In this paper, we propose an anemotaxis – particle filter based smoke plume path tracking method and presented a smoke source localization robot. A modified firefly algorithm is applied in the resampling step of particle filter based smoke plume tracking method to mimic anemotaxis behaviors in the odor source searching process of living creatures. The performance of the proposed algorithm is qualitatively evaluated in a simulated wind tunnel environment in Webots, a high-fidelity robotic simulator. The average computation time including plume path estimation, resampling and target evaluation in every step is 35.9974 ms and the average smoke source localization error is 0.7769 m. We also verify the feasibility by running the proposed algorithm on the smoke source localization robot in real experiments.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0263224120300191



### An Evaluation of Gas Source Localization Algorithms for Mobile Robots

Author: Ojeda, Pepe; Monroy, Javier; Gonzalez-Jimenez, Javier

Publication Year: 2020

Publication Title: Proceedings of the 3rd International Conference on Applications of Intelligent Systems

Abstract: This paper presents a comparative evaluation of different approaches to the problem of gas source localization (GSL) with a mobile robot. Concretely, four state-of-the-art algorithms are implemented and evaluated: Surge-Cast, Spiral, Surge-Spiral and a Probabilistic (Particle Filter-based) method. The experiments have been carried out with the gas dispersion simulator GADEN and the robotic tools offered by ROS (Robotic Operating System) under diverse, realistic environments that feature obstacles and turbulent airflows. Our study reveals, among other results, that Surge-Spiral out-performs Surge-Cast under turbulent wind conditions, and the particle filter approach becomes advantageous only when the assumption of a homogeneous wind holds. We believe that these findings can help the research community to decide on the most appropriate GSL method for a given application. Besides, the code that implements these algorithms is made publicly available.

URL: https://dl.acm.org/doi/abs/10.1145/3378184.3378220



### A Deep Q-Network for robotic odor/gas source localization: Modeling, measurement and comparative study

Author: Chen, Xinxing; Fu, Chenglong; Huang, Jian

Publication Year: 2021

Publication Title: Measurement

Abstract: Robotic odor/gas source localization is a widely studied field, but most of the existing works are about rule-based algorithms. In this paper, the Deep Q-Network algorithm is applied to solve the odor source localization problem. An odor hits distribution model is proposed to model the odor concentration distribution in indoor environments, taking the dispersion by airflow, the odor molecular random walk, and the obstacles into account. The Deep Q-Network takes the stacked historic measurement data as the input and outputs the expected cumulative future reward of actions of the robots. The network is trained through 35,000 repeated episodes of random odor source localization tasks. The Deep Q-Network method is evaluated under four different environment settings in a simplified simulator and compared with two widely used odor source localization algorithms. The evaluation results demonstrate the advantages of the proposed algorithm. The algorithm is also validated in more complex indoor environments.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0263224121006862



### A novel plume tracking method in partial 3D diffusive environments using multi-sensor fusion

Author: Shen, Xiangyuan; Yuan, Jie; Shan, Yugang

Publication Year: 2021

Publication Title: Expert Systems with Applications

Abstract: In recent years, dangerous gas leakage has led to serious consequences in social security. Pervious strategies for locating the odor sources were carried out in 2D environments or the gas sensors were installed at a fixed height, ignoring the characteristics of plume distribution in 3D environments. In some cases, strategies developed in 2D environments may be completely ineffective when be applied to 3D environments. To enhance the success rate and rapidity, a novel method of odor source location in partial 3D diffusive environments based on multi-sensor fusion is proposed. Considering the suspected source existed and weak wind environments, machine olfactory and vision information are both employed to track the plumes and identify its source. To enhance the speed of plume searching and the reliability of plume tracking in the early stages, an autonomous mobile robot (AMR) simulates the social mechanism and hunting behaviors of the gray wolf population and tracks the plumes. A technical strategy is also designed to enable the AMR to complete the task of gas source location successfully and the subsumption architecture is adopted to define and arbitrate behavior priorities to coordinate different behaviors in this paper. The on-site test results show that the average positioning error is 0.13 m, the average running time is 147.7 s and the average distance traveled is 21.35 m. The results show that the proposed method is competent to accomplish the task of leakage gas source localization in partial 3D diffusive environments.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0957417421004346



### Information-Driven Gas Source Localization Exploiting Gas and Wind Local Measurements for Autonomous Mobile Robots

Author: Ojeda, Pepe; Monroy, Javier; Gonzalez-Jimenez, Javier

Publication Year: 2021

Publication Title: IEEE Robotics and Automation Letters

Abstract: Gas source localization (GSL) by an olfactory robot is a research field with a great potential for applications but also with numerous unsolved challenges, particularly when the search must take place in realistic, indoor environments that feature obstacles and turbulent airflows. In this work, we present a new probabilistic GSL method for a terrestrial mobile robot that revolves around the propagation of local estimations throughout the environment. By exploiting the geometry of the environment as the basis for this propagation, we avoid relying on analytical dispersion models, eliminating the need to assume controlled environmental conditions. Simulated and real experiments are presented in different indoor environments featuring multiple rooms and turbulent flows, demonstrating the suitability of our approach for locating the emitting gas source.

URL: https://ieeexplore.ieee.org/abstract/document/9347683



### Autonomous Source Search for UAVs Using Gaussian Mixture Model-Based Infotaxis: Algorithm and Flight Experiments

Author: Park, Minkyu; An, Seulbi; Seo, Jaemin; Oh, Hyondong

Publication Year: 2021

Publication Title: IEEE Transactions on Aerospace and Electronic Systems

Abstract: Estimating and searching source information such as the location and release rate, called a source term, have many applications across environmental, medical, and security domains. The Bayesian inference framework is used to estimate the source term. Since the gas dispersion and its measurements in a turbulent environment are highly non-Gaussian and nonlinear, the particle filter, one of sequential Monte Carlo methods, is adopted in this article. For autonomous source term search in a turbulent environment, this article presents an information-theoretic search approach that combines a widely used Infotaxis approach with the Gaussian mixture model (GMM), termed as GMM-Infotaxis. The GMM is used to determine action candidates for the next best informative sampling position in a continuous domain by appropriately clustering possible source locations obtained from the particle filter. This facilitates a better trade-off between exploitation and exploration for autonomous source search. Through the outdoor experiments, on average, the estimation errors for localization and release rate of the source are reduced 74 and 73%, respectively, while the search time step of the mobile agent is decreased around 18%. Real outdoor flight experiments using a multirotor UAV in various experimental setups show the superior performance of the proposed approach compared with the original Infotaxis method.

URL: https://ieeexplore.ieee.org/abstract/document/9492004



### Source searching in unknown obstructed environments through source estimation, target determination, and path planning

Author: Ji, Yatai; Zhao, Yong; Chen, Bin; Zhu, Zhengqiu; Liu, Yu; Zhu, Hai; Qiu, Sihang

Publication Year: 2022

Publication Title: Building and Environment

Abstract: Autonomous mobile robots have been gradually employed to search unknown sources in indoor environments. However, current studies have not fully addressed the source searching problem in unknown obstructed environments with limited sensing abilities. To deal with these problems, we propose an active source searching framework, in which mobile robots can avoid obstacles actively and realize the balance between exploration and exploitation in unknown obstructed environments through an iterative process: source estimation, target determination, and path planning. First, we describe the source searching problem and introduce the environment and sensor models. Then, a novel source searching algorithm based on particle filter, MEGI-taxis, and A-star is proposed. Specifically, the particle filter is used to estimate the source term parameters. The MEGI-taxis algorithm is developed to obtain a globally optimal searching target, which leverages the Gaussian Mixture Model to extract the features of probability information. Based on the heuristic rule, the A-star algorithm is employed to plan a collision-free path for the robot navigating to the target in unknown environments. When compared to state-of-the-art solutions in simulations, our method shows better performance in success rate, mean searching steps, and stability in the source searching process. Moreover, the effectiveness of the proposed framework is verified in the diffusion field generated by the computational fluid dynamics (CFD) model based on an indoor scene. The results reveal the important practicality of our proposed framework for source searching tasks in unknown obstructed environments.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132322005017



### Autonomous Source Term Estimation in Unknown Environments: From a Dual Control Concept to UAV Deployment

Author: Rhodes, Callum; Liu, Cunjia; Chen, Wen-Hua

Publication Year: 2022

Publication Title: IEEE Robotics and Automation Letters

Abstract: In the gas source search and localisation problem, the use of autonomous robots is of increasing interest due to their deployment speed and lack of human interaction with hazardous materials. This letter presents an aerial robotic platform for performing source term estimation of an unknown chemical release in a challenging a-priori unknown and GPS-denied environment. The proposed system forms the search strategy using the state-of-the-art control concept, dual control for exploitation and exploration, and realises such a function in the aforementioned challenging scenario using an RRT* based path planner. A novel downsampling process on the RRT* is also proposed that addresses the computational infeasibility of calculating the utility of a large number of sample states, whilst still maintaining sample state diversity. The proposed algorithm is tested in a high fidelity simulation environment under a number of configurations, and compared against competing algorithms. The system architecture is also brought forward into a bespoke UAV platform and experimentally tested in real-world conditions. The proposed system is shown to be capable of performing source term estimation robustly and efficiently, which provides a step forward in showing the real world application of previously academic functions.

URL: https://ieeexplore.ieee.org/abstract/document/9684970



### A Supervised-Reinforced Successive Training Framework for a Fuzzy Inference System and Its Application in Robotic Odor Source Searching

Author: Chen, Xinxing; Leng, Yuquan; Fu, Chenglong

Publication Year: 2022

Publication Title: Frontiers in Neurorobotics

Abstract: Fuzzy inference systems have been widely applied in robotic control. Previous studies proposed various methods to tune the fuzzy rules and the parameters of the membership functions (MFs). Training the systems with only supervised learning requires a large amount of input-output data, and the performance of the trained system is conﬁned by that of the target system. Training the systems with only reinforcement learning (RL) does not require prior knowledge but is time-consuming, and the initialization of the system remains a problem. In this paper, a supervised-reinforced successive training framework is proposed for a multi-continuous-output fuzzy inference system (MCOFIS). The parameters of the fuzzy inference system are ﬁrst tuned by a limited number of input-output data from an existing controller with supervised training and then are utilized to initialize the system in the reinforcement training stage. The proposed framework is applied in a robotic odor source searching task and the evaluation results demonstrate that the performance of the fuzzy inference system trained by the successive framework is superior to the systems trained by only supervised learning or RL. The system trained by the proposed framework can achieve around a 10% higher success rate compared to the systems trained by only supervised learning or RL.

URL: https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2022.914706/full



### Receding-horizon RRT-Infotaxis for autonomous source search in urban environments

Author: An, Seulbi; Park, Minkyu; Oh, Hyondong

Publication Year: 2022

Publication Title: Aerospace Science and Technology

Abstract: In emergency situations such as hazardous gas leak, search and estimation for identifying source information, known as source term estimation (STE), in a timely and accurate manner is of significant importance. In real world situations, obstacles such as buildings or barriers not only block the path for search but also interfere the flow of the gas source. For autonomous source search and estimation using a mobile sensor in such obstacle-rich environments, this paper proposes an information-theoretic STE approach by combining a widely-used Infotaxis with the rapidly-exploring random trees (RRT). In particular, the proposed strategy utilizes the receding-horizon RRT concept with a newly designed utility function for determining the next maneuver of a mobile agent to get the best information of the source while avoiding obstacles in urban environments. Numerical simulations in various environments show the superior performance of the proposed approach compared with the original Infotaxis method.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1270963821007860



### Searching for a source without gradients: how good is infotaxis and how to beat it

Author: Loisy, Aurore; Eloy, Christophe

Publication Year: 2022

Publication Title: Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences

Abstract: Infotaxis is a popular search algorithm designed to track a source of odor in a turbulent environment using information provided by odor detections. To exemplify its capabilities, the source-tracking task was framed as a partially observable Markov decision process consisting in finding, as fast as possible, a stationary target hidden in a 2D grid using stochastic partial observations of the target location. Here we provide an extended review of infotaxis, together with a toolkit for devising better strategies. We first characterize the performance of infotaxis in domains from 1D to 4D. Our results show that, while being suboptimal, infotaxis is reliable (the probability of not reaching the source approaches zero), efficient (the mean search time scales as expected for the optimal strategy), and safe (the tail of the distribution of search times decays faster than any power law, though subexponentially). We then present three possible ways of beating infotaxis, all inspired by methods used in artificial intelligence: tree search, heuristic approximation of the value function, and deep reinforcement learning. The latter is able to find, without any prior human knowledge, the (near) optimal strategy. Altogether, our results provide evidence that the margin of improvement of infotaxis toward the optimal strategy gets smaller as the dimensionality increases.

URL: https://www.jstor.org/stable/27169634



### Utilizing a Rapidly Exploring Random Tree for Hazardous Gas Exploration in a Large Unknown Area

Author: Prabowo, Yaqub A.; Trilaksono, Bambang R.; Hidayat, Egi M. I.; Yuliarto, Brian

Publication Year: 2022

Publication Title: IEEE Access

Abstract: The use of robotics olfaction for gas source localization or mapping has become a concern given the issues of terrorism or industrial accidents that may cause damage to the environment. A typical scenario is to send a robot to a place where a dangerous gas leak has just occurred. The robot’s task is to map gas concentrations in the region of interest as effectively as possible. This paper addresses how the robot performs gas exploration in a large and unknown environment. One of the issues that needs to be addressed is the fact that the computation time of the path planning, frontier detection, goal decision making and gas distribution mapping is slower if all cells in the occupancy grid map are involved in a large environment. Consequently, the Rapidly-exploring Random Tree (RRT) algorithm is chosen as the main algorithm. The RRT graph guides the robot’s navigation, utilizes the vertices as goal candidates, gas mean and variance value, and searches for a new frontier. A new strategy is proposed to address the frontier exploration and gas exploitation trade-off. Finally, a Robot Operating System (ROS), Gazebo, and a 3D gas simulator are used to compare the proposed strategy performance with the others in a large outdoor environment.

URL: https://ieeexplore.ieee.org/abstract/document/9698065



### Odor Source Localization in Obstacle Regions Using Switching Planning Algorithms with a Switching Framework

Author: Luong, Duc-Nhat; Kurabayashi, Daisuke

Publication Year: 2023

Publication Title: Sensors

Abstract: Odor source localization (OSL) robots are essential for safety and rescue teams to overcome the problem of human exposure to hazardous chemical plumes. However, owing to the complicated geometry of environments, it is almost impossible to construct the dispersion model of the odor plume in practical situations to be used for probabilistic odor source search algorithms. Additionally, as time is crucial in OSL tasks, dynamically modifying the robot’s balance of emphasis between exploration and exploitation is desired. In this study, we addressed both the aforementioned problems by simplifying the environment with an obstacle region into multiple sub-environments with different resolutions. Subsequently, a framework was introduced to switch between the Infotaxis and Dijkstra algorithms to navigate the agent and enable it to reach the source swiftly. One algorithm was used to guide the agent in searching for clues about the source location, whereas the other facilitated the active movement of the agent between sub-environments. The proposed algorithm exhibited improvements in terms of success rate and search time. Furthermore, the implementation of the proposed framework on an autonomous mobile robot verified its effectiveness. Improvements were observed in our experiments with a robot when the success rate increased 3.5 times and the average moving steps of the robot were reduced by nearly 35%.

URL: https://www.mdpi.com/1424-8220/23/3/1140



### Receding Horizon-Based Infotaxis With Random Sampling for Source Search and Estimation in Complex Environments

Author: Park, Minkyu; Ladosz, Pawel; Kim, Jongyun; Oh, Hyondong

Publication Year: 2023

Publication Title: IEEE Transactions on Aerospace and Electronic Systems

Abstract: This article proposes a receding horizon-based information-theoretic source search and estimation strategy for a mobile sensor in an urban environment in which an invisible harmful substance is released into the atmosphere. The mobile sensor estimates the source term including its location and release rate by using sensor observations based on Bayesian inference. The sampling-based sequential Monte Carlo method, particle filter, is employed to estimate the source term state in a highly nonlinear and stochastic system. Infotaxis, the information-theoretic gradient-free search strategy is modified to find the optimal search path that maximizes the reduction of the entropy of the source term distribution. In particular, receding horizon Infotaxis (RHI) is introduced to avoid falling into the local optima and to find more successful information gathering paths in obstacle-rich urban environments. Besides, a random sampling method is introduced to reduce the computational load of the RHI for real-time computation. The random sampling method samples the predicted future measurements based on current estimation of the source term and computes the optimal search path using sampled measurements rather than considering all possible future measurements. To demonstrate the benefit of the proposed approach, comprehensive numerical simulations are performed for various conditions. The proposed algorithm increases the success rate by about 30% and reduces the mean search time by about 40% compared with the existing information-theoretic search strategy.

URL: https://ieeexplore.ieee.org/abstract/document/9802735



### Integration of Bayesian Inference and Anemotaxis for Robotics Gas Source Localization in a Large Cluttered Outdoor Environment

Author: Prabowo, Yaqub A.; Trilaksono, Bambang R.; Hidayat, Egi M. I.; Yuliarto, Brian

Publication Year: 2023

Publication Title: IEEE Access

Abstract: Finding a gas source in a cluttered outdoor environment using autonomous robot is a complex challenge. The gas movement is difficult to predict as it is significantly affected by the wind and the shape of objects in the environment. In this paper, we propose a new probabilistic model and an integration of Bayesian inference and anemotaxis methods used for a robot to find a gas source in a large cluttered outdoor environment. An autonomous robot installed with a gas sensor is expected to find the location of the gas source after the gas leak occurs for a particular time. The advantage of the Bayesian inference technique has been presented previously so that a robot can find the gas source in an isolated indoor building without any significant wind flow. The large environment is divided into some particular regions. A set of probability density function was collected previously from a large amount of gas dispersion simulation to estimate the maximum likelihood of where the gas source is. The challenge gets more extensive if the Bayesian inference method is applied in an outdoor and cluttered environment. Instead of only measuring the gas concentration, the wind angle is also used as the wind profile significantly affects the gas dispersion. Therefore, the probability model is modified to allow the wind direction as a new variable. Moreover, an anemotaxis method is incorporated as the decision-making support as it may be more efficient to direct the robot explicitly to the upwind direction. Evaluations of the proposed method were carried out and its advantage was shown through simulation in a number of different scenarios.

URL: https://ieeexplore.ieee.org/abstract/document/10022312



### An Exploration-Enhanced Search Algorithm for Robot Indoor Source Searching

Author: Wang, Miao; Xin, Bin; Jing, Mengjie; Qu, Yun

Publication Year: 2024

Publication Title: IEEE Transactions on Robotics

Abstract: Chemical, biological, or radioactive substances may be released in accidents, posing a threat to human life and property. Due to the dense obstacles and specific structures of indoor environments, indoor source searching still faces challenges, such as the initial position of the robot cannot be placed freely, the source may not be in the airflow, and most areas indoors lack concentration and airflow clues. This study proposes an exploration-enhanced search algorithm, enabling the robot to search for a source located downstream of the robot or outside the airflow in an indoor environment with a narrow plume without losing the classic upstream search ability. The algorithm equips the robot with the capability to search for a source in complex indoor environments where measurements frequently change. The algorithm is evaluated in the simulated environment to assess the contributions of its components and its performance under different airflow speeds. The algorithm is also compared with the state-of-the-art algorithms and shows superior performance. The effectiveness of the algorithm is further demonstrated in real-world environments.

URL: https://ieeexplore.ieee.org/abstract/document/10665938



### Robotic Gas Source Localization With Probabilistic Mapping and Online Dispersion Simulation

Author: Ojeda, Pepe; Monroy, Javier; Gonzalez-Jimenez, Javier

Publication Year: 2024

Publication Title: IEEE Transactions on Robotics

Abstract: Gas source localization (GSL) with an autonomous robot is a problem with many prospective applications, from finding pipe leaks to emergency-response scenarios. In this work, we present a new method to perform GSL in realistic indoor environments, featuring obstacles, and turbulent flow. Given the highly complex relationship between the source position and the measurements available to the robot (the single-point gas concentration, and the wind vector) we propose an observation model that derives from contrasting the online, real-time simulation of the gas dispersion from any candidate source localization against a gas concentration map built from sensor readings. To account for a convenient and grounded integration of both into a probabilistic estimation framework, we introduce the concept of probabilistic gas-hit maps, which provide a higher level of abstraction to model the time-dependent nature of gas dispersion. Results from both simulated and real experiments show the capabilities of our current proposal to deal with source localization in complex indoor environments.

URL: https://ieeexplore.ieee.org/abstract/document/10592836



### Gas Source Localization in Unknown Indoor Environments Using Dual-Mode Information-Theoretic Search

Author: Kim, Seunghwan; Seo, Jaemin; Jang, Hongro; Kim, Changseung; Kim, Murim; Pyo, Juhyun; Oh, Hyondong

Publication Year: 2025

Publication Title: IEEE Robotics and Automation Letters

Abstract: This letter proposes a dual-mode planner for localizing gas sources using a mobile sensor in unknown indoor spaces. The complexity of indoor environments creates constraints on search paths, leading to situations where no valid paths can be generated, which are termed as dead end in this letter. The proposed dual-mode planner is designed to effectively address the dead end problem while maintaining efficient search paths. In addition, the absence of analytical dispersion models that can be used in unknown indoor environments presents another critical issue for indoor gas source localization (GSL). To address this, we present an indoor Gaussian dispersion model (IGDM) that can analytically model indoor gas dispersion without a complete map. Finally, we establish a GSL framework for indoor environments along with real-time mapping, utilizing the dual-mode planner and IGDM. This framework is validated in indoor scenarios with the realistic gas dispersion simulator. The simulation results show the high success rate of the proposed method, its ability to reduce search time, and its computational efficiency. Furthermore, through real-world experiments, we demonstrate the potential of the proposed approach as a practical solution, evidenced by its satisfactory performance.

URL: https://ieeexplore.ieee.org/abstract/document/10777609



### An Adaptive Robot Search Algorithm for Balancing Exploitation and Exploration in Indoor Intermittent Source Seeking

Author: Wang, Miao; Xin, Bin; Deng, Fang; Chen, Chen; Qu, Yun

Publication Year: 2026

Publication Title: IEEE Transactions on Industrial Electronics

Abstract: The accidental release of chemicals poses significant risks to human life and property, requiring rapid and accurate source seeking. Chemicals released from an intermittent indoor source form narrow, dynamic, and discrete concentration patches, leaving robots with intermittent cues and posing challenges for source seeking. This study proposed an adaptive robot search algorithm that balances exploitation of historical data and exploration of unknown areas. The proposed exploitation strategy utilizes historical data to probabilistically estimate the source location, aiming to guide the robot upstream for faster source localization. The proposed exploration strategy directs the robot to unknown areas, aiming to gather more information by prioritizing points with the highest information gain based on frontier evaluation. A novel time-dependent factor reduces repeated visits to early regions while mitigating exploration bias in later search stages, enabling a dynamic balance between the two strategies when selecting navigation goals. The algorithm was tested in simulated environments with varying airflow speeds, source release cycles, source release duty cycles, and different scenarios. The results demonstrated reliable and excellent performance. The effectiveness of the proposed algorithm was further validated in real-world robot experiments.

URL: https://ieeexplore.ieee.org/abstract/document/11297772



### Adaptive Robotic Source Seeking in Vortical Indoor Environments With Sparse Structural Guidance

Author: Jing, Mengjie; Xin, Bin; Wang, Miao; Bian, Wenjing

Publication Year: 2026

Publication Title: IEEE Transactions on Automation Science and Engineering

Abstract: Indoor source seeking is vital for tasks such as security monitoring and disaster rescue, yet it remains highly challenging in environments characterized by turbulent airflow and sparse structural guidance. In such settings, airflow directions may shift abruptly due to obstacle-induced vortices, while odor cues are often intermittent and spatially sparse. These factors increase the difficulty of crosswind search in sparse space. This paper proposes a perception-guided adaptive search algorithm that fuses short-term odor and wind observations to assess the reliability of perceptual cues and adaptively adjust the robot’s search behavior. By refining the search region based on perceptual cues, the algorithm effectively regulates crosswind motion, thereby enabling timely escape from vortex-induced traps and improving source search efficiency. The proposed algorithm is evaluated across diverse indoor environments and inlet-outlet configurations under different airflow speeds. It is further compared with the representative state-of-the-art algorithms and shows superior performance in simulation experiments. Real-robot experiments are also conducted to verify its practical effectiveness in physical indoor environments. Note to Practitioners—The aim of this study is to propose a robotic search algorithm designed to address the challenges of source seeking in unknown indoor environments. These challenges include obstacle-induced local vortices, intermittent and spatially sparse odor cues, and sparse structural guidance, which can cause the robot to become trapped in local regions, leading to wandering behaviors and degraded efficiency during crosswind search. This study proposes a perception-guided adaptive search algorithm that enhances the robot’s ability to refine its search region, thereby enabling escape from vortex-dominated regions and progress in sparse space. The core idea is to quantify perceptual reliability from short-term airflow stability and recent odor observations, and to leverage this reliability to adaptively switch among different search modes. When perceptual cues are unreliable, the robot activates a frontier-guided spatial exploration method to cover indoor regions with low perceptual reliability. As airflow and odor observations become more reliable, the robot switches to a perception-guided directional source seeking method, where navigation goals are sampled within an adaptive search region aligned with the local airflow. By reshaping the search region based on perceptual reliability, directional sampling is biased toward the upwind sector when confidence is high and toward sectors supported by recent observations otherwise. This mechanism guides the robot away from vortex-dominated areas and enables steady progress toward the source under sparse structural guidance. The algorithm is compared with four representative state-of-the-art algorithms in simulated environments and is further evaluated through real-robot experiments. Results show that the algorithm exhibits outstanding performance in both simulated and real-robot experiments. In addition, a dataset for robotic indoor source seeking is released online to serve as a benchmark for future research.

URL: https://ieeexplore.ieee.org/abstract/document/11625809



## Multi-robot



### Particle swarm-based olfactory guided search

Author: Marques, Lino; Nunes, Urbano; de Almeida, A. T.

Publication Year: 2006

Publication Title: Autonomous Robots

Abstract: This article presents a new algorithm for searching odour sources across large search spaces with groups of mobile robots. The proposed algorithm is inspired in the particle swarm optimization (PSO) method. In this method, the search space is sampled by dynamic particles that use their knowledge about the previous sampled space and share this knowledge with other neighbour searching particles allowing the emergence of efficient local searching behaviours. In this case, chemical searching cues about the potential existence of upwind odour sources are exchanged. By default, the agents tend to avoid each other, leading to the emergence of exploration behaviours when no chemical cue exists in the neighbourhood. This behaviour improves the global searching performance.

URL: https://link.springer.com/article/10.1007/s10514-006-7567-0



### A PSO-based Mobile Sensor Network for Odor Source Localization in Dynamic Environment: Theory, Simulation and Measurement

Author: Jatmiko, W.; Sekiyama, K.; Fukuda, T.

Publication Year: 2006

Publication Title: 2006 IEEE International Conference on Evolutionary Computation

Abstract: This paper presents a problem of odor source localization in a dynamic environment, which means the odor distribution is changing over time. Most work on chemical sensing with mobile robots assume an experimental setup that minimizes the influence of turbulent transport by either minimizing the source-to-sensor distance in trail following or by assuming a strong unidirectional air stream in the environment, including our previous work. However, not much attention has been paid to the natural environment problem. Modification Particle Swarm Optimization is a well-known algorithm, which can continuously track a changing optimum over time. PSO can be improved or adapted by incorporating the change detection and responding mechanisms for solving dynamic problems. Charged PSO, which is another extension of the PSO, has also been applied to solve dynamic problems. Odor source localization is an interesting application in dynamic problems. We will adopt two types of PSO modification concepts to develop a new algorithm in order to control autonomous vehicles. Before applying the algorithm for real implementation, some important hardware conditions must be considered. Firstly, to reduce the possibility of robots leaving the search space, a limit to the value of velocity vector is needed. The value of vector velocity can be clamped to the range [-Vmax, Vmax]; in our case for the MK-01 Robot, the maximum velocity is 0.05 m/s. Secondly, in the standard PSO algorithm there is no collision avoidance mechanism. To avoid the collision among robot we add some collision avoidance functions. Finally, we also add some sensor noise, delay and threshold value to model the sensor response. Then we develop odor localization algorithm, and simulations to show that the new approach can solve such dynamic environment problems.

URL: https://ieeexplore.ieee.org/abstract/document/1688423



### A Mobile Robots PSO-Based for Odor Source Localization in Extreme Dynamic Advection-Diffusion Environment with Obstacle

Author: Jatmiko, Wisnu; Sekiyama, Kosuke; Fukuda, Toshio

Publication Year: 2006

Publication Title: 2006 IEEE SENSORS

Abstract: The odor distribution advection-diffusion environments in obstacle environment have been developed. In real world the odor distribution are changing over time and multi peaks especially in obstacle environments. The purpose of developing this environment is to bridge the gap between the very complex hard to understand real-world problem (odor dispersion model) and all too simple toy problems (dynamic bit matching or moving parabola). Modified particle swarm optimization is a well-known algorithm, which can continuously track a changing optimum over time. We will adopt two types of PSO modification concepts to develop a new algorithm in order to control autonomous vehicles to solve odor source localization in real world environment. Firstly, PSO can be improved or adapted by incorporating the change detection and responding mechanisms for solving dynamic problems. Secondly, charged PSO, which is another extension of the PSO, has also been applied to solve dynamic problems. In order to control autonomous vehicles in more realistic condition from the viewpoint of robotic, where a speed limitation of the robot behavior and collision avoidance mechanism should be taken into consideration as well as the effect of noise and threshold value for the odor sensor response, also positioning error of GPS sensor of robot. Simulations illustrate that the new approach can solve such dynamic environment in advection-diffusion odor model problems even though in obstacle environments.

URL: https://ieeexplore.ieee.org/document/4178673



### A pso-based mobile robot for odor source localization in dynamic advection-diffusion with obstacles environment: theory, simulation and measurement

Author: Jatmiko, Wisnu; Sekiyama, Kosuke; Fukuda, Toshio

Publication Year: 2007

Publication Title: IEEE Computational Intelligence Magazine

Abstract: This paper provides a combination of chemotaxic and anemotaxic modeling, known as odor-gated rheotaxis (OGR), to solve real-world odor source localization problems. Throughout the history of trying to mathematically localize an odor source, two common biometric approaches have been used. The first approach, chemotaxis, describes how particles flow according to local concentration gradients within an odor plume. Chemotaxis is the basis for many algorithms, such as particle swarm optimization (PSO). The second approach is anemotaxis, which measures the direction and velocity of a fluid flow, thus navigating "upstream" within a plume to localize its source. Although both chemotaxic and anemotaxic based algorithms are capable of solving overly-simplified odor localization problems, such as dynamic-bit-matching or moving-parabola problems, neither method by itself is adequate to accurately address real life scenarios. In the real world, odor distribution is multi-peaked due to obstacles in the environment. However, by combining the two approaches within a modified PSO-based algorithm, odors within an obstacle-filled environment can be localized and dynamic advection-diffusion problems can be solved. Thus, robots containing this modified particle swarm optimization algorithm (MPSO) can accurately trace an odor to its source

URL: https://ieeexplore.ieee.org/abstract/document/4168420



### Explorative Particle Swarm Optimization Method for Gas/Odor Source Localization in an Indoor Environment with no Strong Airflow

Author: Ferri, Gabriele; Caselli, Emanuele; Mattoli, Virgilio; Mondini, Alessio; Mazzolai, Barbara; Dario, Paolo

Publication Year: 2007

Publication Title: 2007 IEEE International Conference on Robotics and Biomimetics (ROBIO)

Abstract: This paper presents an algorithm to localize a gas source by using a swarm of robots in a large indoor environment without the presence of a relevant wind. The algorithm is composed of two different phases: an exploration phase aiming at finding a clue of the presence of a gas source and a localization phase to detect the emitting source. We propose a modified version of the particle swarm optimization (PSO) algorithm, called explorative particle swarm optimization (EPSO), as a strategy of movement for the swarm of robots during the localization phase. The introduced modifications point at avoiding multiple gas samplings in nearby locations, in this way increasing the exploration of the area and limiting the possibility for the swarm of being trapped in local maxima. Results from computer simulations are reported and discussed. They show that, in these environmental conditions, the proposed algorithm improves the performance of the standard PSO and can be a viable solution in localizing a chemical source.

URL: https://ieeexplore.ieee.org/abstract/document/4522272



### Localizing Multiple odor Sources in a dynamic environment based on Modified niche Particle Swarm Optimization with flow of wind

Author: Jatmiko, Wisnu; Nugraha, A.; Efendi, Rusdi; Pambuko, W.; Mardian, Rizki; Sekiyama, Kosuke; Fukuda, T.

Publication Year: 2009

Publication Title: WSEAS TRANSACTIONS on SYSTEMS

Abstract: A new algorithm based on Modified Particle Swarm Optimization (MPSO) that follows is a local gradient of a chemical concentration within a plume and follows the direction of the wind velocity is investigated. Moreover, the niche characteristic is adopted to solve the multi-peak and multi-source problem. Simulations results demonstrate that the new approach is reliable for The Advection-Diffusion odor robotic model. Finally, the statistical analysis shows this new approach is technically sound.

URL: https://dl.acm.org/doi/abs/10.5555/1718197.1718199



### Chasing information to search in random environments

Author: Masson, J.-B.; Bechet, M. Bailly; Vergassola, M.

Publication Year: 2009

Publication Title: Journal of Physics A: Mathematical and Theoretical

Abstract: We discuss search strategies for finding sources of particles transported in a random environment and detected by the searcher(s). The mixing of the particles in the environment is supposed to be strong, so that strategies based on concentration-gradient ascent are not viable. These dilute conditions are common in natural environments typical of searches performed by insects and birds. The sparseness of the detections constitutes the major stumbling block in developing efficient olfactory robots to detect mines, chemical leaks, etc. We first discuss a search strategy, ‘infotaxis’, recently introduced for the search of a single source by a single robot. Decisions are made by locally maximizing the rate of acquisition of information on the location of the source and they balance exploration and exploitation. We present numerical simulations demonstrating the efficiency of the method and, most importantly, its robustness to lack of detailed modeling of the transport of particles in the random environment. We then introduce a novel formulation of infotaxis for collective searches where a swarm of robots is available and must be coordinated. Gains in the search time are impressive and the method can be further generalized to deal with conflicts arising in the identification of multiple sources.

URL: https://iopscience.iop.org/article/10.1088/1751-8113/42/43/434009/meta



### Effectiveness and robustness of robot infotaxis for searching in dilute conditions

Author: Martin Moraud, Eduardo; Martinez, Dominique

Publication Year: 2010

Publication Title: Frontiers in Neurorobotics

Abstract: Tracking scents and locating odor sources is a major challenge in robotics. The odor plume is not a continuous cloud but consists of intermittent odor patches dispersed by the wind. Far from the source, the probability of encountering one of these patches vanishes. In such dilute conditions, a good strategy is to first ‘explore’ the environment and gather information, then ‘exploit’ current knowledge and direct toward the estimated source location. Infotactic navigation has been recently proposed to strike the balance between exploration and exploitation. Infotaxis was tested in simulation and produced trajectories similar to those observed in the flight of moths attracted by a sexual pheromone. In this paper, we assess the performance of infotaxis in dilute conditions by combining robotic experiments and simulations. Our results indicate that infotaxis is both effective (seven detections on average were sufficient to reach the source) and robust (the source is found in presence of inaccurate modeling by the searcher). The biomimetic characteristic of infotaxis is also preserved when searching with a robot in a real environment.

URL: https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2010.00001/full



### Optimal spatial formation of swarm robotic gas sensors in odor plume finding

Author: Marjovi, Ali; Marques, Lino

Publication Year: 2013

Publication Title: Autonomous Robots

Abstract: Finding the best spatial formation of stationary gas sensors in detection of odor clues is the first step of searching for olfactory targets in a given space using a swarm of robots. Considering no movement for a network of gas sensors, this paper formulates the problem of odor plume detection and analytically finds the optimal spatial configuration of the sensors for plume detection, given a set of assumptions. This solution was analyzed and verified by simulations and finally experimentally validated in a reduced scale realistic environment using a set of Roomba-based mobile robots.

URL: https://link.springer.com/article/10.1007/s10514-013-9336-1



### A Plume Tracking Algorithm Based on Crosswind Formations

Author: Lochmatter, Thomas; Aydın Göl, Ebru; Navarro, Iñaki; Martinoli, Alcherio

Publication Year: 2013

Publication Title: Distributed Autonomous Robotic Systems

Abstract: We introduce a plume tracking algorithm based on robot formations. The algorithm is inherently designed for multi-robot systems, and requires at least two robots to collaborate. The robots try to keep themselves centered around the plume while moving upwind towards...

URL: https://link.springer.com/chapter/10.1007/978-3-642-32723-0_7



### A niching PSO-based multi-robot cooperation method for localizing odor sources

Author: Zhang, Jianhua; Gong, Dunwei; Zhang, Yong

Publication Year: 2014

Publication Title: Neurocomputing

Abstract: Aiming at the problem of multiple odor sources localization, a multi-robot cooperation method based on niching particle swarm optimization is presented in this study. In this method, a robot is regarded as a particle, particles located at a neighbor form a niche, and different niches are employed to localize different odor sources synchronously. In order to localize more odor sources, the size of each niche is dynamically adjusted based on the aggregation degree of its elements. A niche merging strategy, based on the similarity of optimal particles found by niches, is proposed to prevent particles repeatedly searching for the same region. In addition, some real conditions such as the sampling/recovery time of a sensor and the velocity limit of a robot are considered when updating the position of a particle. Finally, the proposed method is applied to various scenarios of localizing multiple odor sources, and the experimental results confirm its effectiveness.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0925231213007698



### A distributed formation-based odor source localization algorithm - design, implementation, and wind tunnel evaluation

Author: Soares, Jorge M.; Aguiar, A. Pedro; Pascoal, António M.; Martinoli, Alcherio

Publication Year: 2015

Publication Title: 2015 IEEE International Conference on Robotics and Automation (ICRA)

Abstract: Robotic odor source localization is a promising tool with numerous applications in safety, search and rescue, and environmental science. In this paper, we present an algorithm for odor source localization using multiple cooperating robots equipped with chemical sensors. Laplacian feedback is employed to maintain the robots in a formation, introducing spatial diversity that is used to better establish the position of the flock relative to the plume and its source. Robots primarily move upwind but use odor information to adjust their position and spacing so that they are centered on the plume and trace its structure. Real-world experiments were performed with an ethanol plume inside a wind tunnel, and used to both validate the algorithm and assess the impact of different formation shapes.

URL: https://ieeexplore.ieee.org/abstract/document/7139436



### An algorithm for formation-based chemical plume tracing using robotic marine vehicles

Author: Soares, Jorge M.; Aguiar, A. Pedro; Pascoal, António M.; Martinoli, Alcherio

Publication Year: 2016

Publication Title: OCEANS 2016 MTS/IEEE Monterey

Abstract: Robotic chemical plume tracing is a growing area of research, with envisioned real-world applications including pollution tracking, search and rescue, and ecosystem identification. However, following a chemical signal in the water is not an easy task due to the nature of chemical transport and to limitations in sensing and communication. In this paper, we propose an approach for near-surface waterborne plume tracing using a combined team of autonomous surface and underwater vehicles. All vehicles are equipped with appropriate chemical sensors and acoustic modems. The team moves in a triangular formation, while using the flow direction and the samples obtained to steer the group along the plume. Leader vehicles at the surface implement a formation controller based on Laplacian feedback while the underwater vehicle performs acoustic ranging to the leaders. The solution was evaluated using a CFD simulation of a freshwater plume and a calibrated dynamic model of the MEDUSA autonomous marine vehicles. The group is able to move in a stable formation, sample the salinity, and trace the plume to its source.

URL: https://ieeexplore.ieee.org/abstract/document/7761119



### Towards 3-D distributed odor source localization: An extended graph-based formation control algorithm for plume tracking

Author: Soares, Jorge M.; Marjovi, Ali; Giezendanner, Jonathan; Kodiyan, Anil; Aguiar, A. Pedro; Pascoal, António M.; Martinoli, Alcherio

Publication Year: 2016

Publication Title: 2016 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Abstract: The large number of potential applications for robotic odor source localization has motivated the development of a variety of plume tracking algorithms, the majority of which work in restricted two-dimensional scenarios. In this paper, we introduce a distributed algorithm for 3-D plume tracking using a system of ground and aerial robots in formation. We propose an algorithm that takes advantage of spatially distributed measurements to track the plume in 3-D and lead the robots to the source by integrating three behaviors - upwind movement, plume centering, and Laplacian feedback formation control. We evaluate this strategy in simulation and with real robots in a wind tunnel. For a source close to the ground, results show that a team of robots running our algorithm reaches the source with low lateral error while also tracing the horizontal and vertical plume shape.

URL: https://ieeexplore.ieee.org/abstract/document/7759277



### A Graph-Based Formation Algorithm for Odor Plume Tracing

Author: Soares, Jorge M.; Aguiar, A. Pedro; Pascoal, António M.; Martinoli, Alcherio

Publication Year: 2016

Publication Title: Distributed Autonomous Robotic Systems

Abstract: Odor plume tracing is a challenging robotics application, made difficult by the combination of the patchy characteristics of odor distribution and the slow response of the available sensors. This work proposes a graph-based formation control algorithm to coordinate a...

URL: https://link.springer.com/chapter/10.1007/978-4-431-55879-8_18



### Multi-agent search for source localization in a turbulent medium

Author: Hajieghrary, Hadi; Hsieh, M. Ani; Schwartz, Ira B.

Publication Year: 2016

Publication Title: Physics Letters A

Abstract: We extend the gradient-less search strategy referred to as “infotaxis” to a distributed multi-agent system. “Infotaxis” is a search strategy that uses sporadic sensor measurements to determine the source location of materials dispersed in a turbulent medium. In this work, we leverage the spatio-temporal sensing capabilities of a mobile sensing agents to optimize the time spent finding and localizing the position of the source using a multi-agent collaborative search strategy. Our results suggest that the proposed multi-agent collaborative search strategy leverages the team's ability to obtain simultaneous measurements at different locations to speed up the search process. We present a multi-agent collaborative “infotaxis” strategy that uses the relative entropy of the system to synthesize a suitable search strategy for the team. The result is a collaborative information theoretic search strategy that results in control actions that maximize the information gained by the team, and improves estimates of the source position.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0375960116002425



### A PSO-based multi-robot cooperation method for target searching in unknown environments

Author: Dadgar, Masoud; Jafari, Shahram; Hamzeh, Ali

Publication Year: 2016

Publication Title: Neurocomputing

Abstract: In this paper, we study the problem of multi-robot target searching in unknown environments. For target searching, robots need an efficient method with respect to their limitations and characteristics of the workspace. Every robotic search algorithm has several constraints. Our goal is to propose a distributed algorithm based on Particle Swarm Optimization (PSO) for target searching which satisfies the before-mentioned constraints. This extension of PSO is named A-RPSO (Adaptive Robotic PSO). A-RPSO acts as the controlling mechanism for robots. It is similar to PSO with two modifications: firstly it takes into account obstacle avoidance, secondly A-RPSO has a mechanism to escape from local optima. Various experimental results obtained in a simulated environment, show that A-RPSO is able to outperform other state of-the-art techniques in target searching problems. The performance of A-RPSO is much more significant compared with other approaches in two distinctive states particularly: large environments and small number of robots.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0925231215016586



### Using multi-robot active olfaction method to locate time-varying contaminant source in indoor environment

Author: Chen, Yicun; Cai, Hao; Chen, Zhilong; Feng, Qilin

Publication Year: 2017

Publication Title: Building and Environment

Abstract: Prevention of indoor contaminant source leak disasters is becoming an urgent issue in the indoor environment and public safety fields. Quickly locating such a source is a prerequisite for effective implementation of source control, and a key basis for further guidance on evacuation and emergency rescue. Indoor contaminant sources have many forms because of source characteristic variation. The current research focuses on continuous release from a source with constant intensity and instantaneous release from a source with impulse intensity. There are few studies of sources with varying release intensity. The main goal of the present research study was to develop a source localization method for a time-varying source. A computational fluid dynamics model of leakage for an indoor time-varying contaminant source is established, together with a search strategy using multi-robot active olfaction. Based on the time-varying leakage source localization method, the robots are used to verify method effectiveness through indoor two-dimensional ventilation room simulation experiments. The influence of factors such as intensity change, position and obstacles on the localization is analyzed, which provides a foundation for further study of contaminant source identification in an unsteady flow field.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132317301270



### Autonomous Multi-Robot Search for a Hazardous Source in a Turbulent Environment

Author: Ristic, Branko; Angley, Daniel; Moran, Bill; Palmer, Jennifer L.

Publication Year: 2017

Publication Title: Sensors

Abstract: Finding the source of an accidental or deliberate release of a toxic substance into the atmosphere is of great importance for national security. The paper presents a search algorithm for turbulent environments which falls into the class of cognitive (infotaxi) algorithms. Bayesian estimation of the source parameter vector is carried out using the Rao–Blackwell dimension-reduction method, while the robots are controlled autonomously to move in a scalable formation. Estimation and control are carried out in a centralised replicated fusion architecture assuming all-to-all communication. The paper presents a comprehensive numerical analysis of the proposed algorithm, including the search-time and displacement statistics.

URL: https://www.mdpi.com/1424-8220/17/4/918



### Coordinated Bayesian-Based Bioinspired Plume Source Term Estimation and Source Seeking for Mobile Robots

Author: Bourne, Joseph R.; Pardyjak, Eric R.; Leang, Kam K.

Publication Year: 2019

Publication Title: IEEE Transactions on Robotics

Abstract: A new nonparametric Bayesian-based motion planning algorithm for autonomous plume source term estimation (STE) and source seeking (SS) is presented in this paper. The algorithm is designed for mobile robots equipped with gas concentration sensors. Specifically, robots coordinate and utilize a Gaussian-plume likelihood model in a Bayesian-based STE process, then they simultaneously search for and navigate toward the source through model based, bioinspired SS methods such as biased-random-walk and surge-casting. Compared with the state-of-the-art Bayesian- and sensor-based STE/SS motion planners, the strategy described takes advantage of coordination between multiple robots and the estimated plume model for faster and more robust SS, rather than rely on direct or filtered sensor measurements. A set of Monte Carlo simulation studies are conducted to compare the performance between the uncoordinated and coordinated algorithms for different robot team sizes and starting conditions. Additionally, the algorithms are validated experimentally through a laboratory-safe, realistic humid-air plume that behaves similar to a gas plume, to test STE and SS using mobile ground robots equipped with humidity sensors. Simulation and experimental results show consistently that the algorithm involving coordination outperforms traditional bioinspired SS algorithms and it is approximately twice as fast as the uncoordinated case. Finally, the plume source is distorted to study the algorithm's limitations and impact on STE and SS, where results show that even for distorted plumes, useful source localization information can be obtained.

URL: https://ieeexplore.ieee.org/abstract/document/8721123



### An improved particle swarm optimization method for locating time-varying indoor particle sources

Author: Feng, Qilin; Cai, Hao; Li, Fei; Liu, Xiaoran; Liu, Shichao; Xu, Jiheng

Publication Year: 2019

Publication Title: Building and Environment

Abstract: The indoor transmission of airborne particles can spread disease and have health-related and even life-threatening effects on occupants, thus necessitating effective ways to locate indoor particle sources. The identification of particle sources from concentration distributions is a difficult task because particles are often released at a time-varying rate, and particle transport mechanisms are more complex than those of gas. This study proposes an improved multi-robot olfactory search method for locating two types of time-varying indoor particle sources: 1) periodic sources such as occupants’ respiratory activities and 2) decaying sources such as laboratory leaky containers with hazardous chemicals. The method considers both particle concentrations and indoor air velocities by including an upwind term in the standard particle swarm optimization (PSO) algorithm, preventing robots from becoming trapped into a local optimum, which occurs when using other algorithms. We also considered two ventilation types (mixing ventilation and displacement ventilation) when particles are emitted from different source types, comprising four scenarios. For each scenario, particle concentration and air velocity were simulated using computational fluid dynamics (CFD) and then fed to the PSO algorithm for source localization. In addition, we validated the CFD approach for one scenario by comparing experimental data (e.g., velocities and particle concentrations) under laboratory settings. The results showed that the proposed method can locate the two types of particle sources within approximately 55 s, and the success rates of source localization exceeding 96%, which is a much higher level than levels achieved from the standard PSO and wind utilization II algorithms.

URL: https://www.sciencedirect.com/science/article/pii/S0360132318306267



### Pollution Source Localization Based on Multi-UAV Cooperative Communication

Author: Fu, Zhangjie; Chen, Yiming; Ding, Yongjie; He, Daojing

Publication Year: 2019

Publication Title: IEEE Access

Abstract: Harmful gas leakage accidents in chemical plants have occurred from time to time. The application of mobile robots to find odor source has become one of the hottest research topics. Compared to traditional robots, unmanned aerial vehicle (UAV) is more flexible and safer. Therefore, using multi-UAV to solve pollution source tracking is a meaningful study. In this paper, an air pollution source tracking algorithm based on artificial potential field and particle swarm optimization is proposed. The particle swarm optimization algorithm combined with artificial potential field method is used to guide the UAVs to track the plume and avoid the collisions among them. At the same time, adaptive inertia weights are used to help improve the convergence and the searchability of particles. We not only evaluated this algorithm in simulation experiments but also designed a multi-UAV pollution source tracking platform for real-world experiments. The experimental results show that the algorithm can accurately find the pollution source in a short time.

URL: https://ieeexplore.ieee.org/abstract/document/8665856



### Multiple odor source localization using diverse-PSO and group-based strategies in an unknown environment

Author: Jain, Upma; Tiwari, Ritu; Godfrey, W. Wilfred

Publication Year: 2019

Publication Title: Journal of Computational Science

Abstract: This work presents a diverse particle swarm optimization based multi-robot cooperative approach for multiple odor source localization. Major contributions of this paper are with respect to group related tasks and plume following through the introduction of methods for group formation, maintenance of group aggregation, group closeness measurement, group dismantling, and next movement calculation of the robot. Specifically, this paper introduces methods for: (1) localizing multiple odor sources in parallel, (2) maintaining aggregation degree of a group by limiting the maximum number of robots a group can have, (3) measuring the closeness of the formed groups based on which group merging behavior is employed, (4) group dismantling to ensure better resource utilization, and (5) calculating the next move of a robot within the group by diverse- PSO. To bridge the gap between simulation and real-time experiments, sensor odometric error along with localization error in robot positioning is introduced, and the working of the proposed framework is evaluated. Contaminant release is simulated in the 3D indoor environment using Ansys Fluent. Performance of the proposed approach is compared with three state-of-art approaches considering the erroneous and error-free cases. Results validate the effectiveness of the proposed approach.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1877750318308457



### Chemical-Source Localization Using a Swarm of Decentralized Unmanned Aerial Vehicles for Urban/Suburban Environments

Author: Steiner, Jake A.; Bourne, Joseph R.; He, Xiang; Cropek, Donald M.; Leang, Kam K.

Publication Year: 2019

Publication Title: 

Abstract: Abstract. In this paper, a decentralized chemical-source localization method is presented. In a real-world scenario, many challenges arise, including sporadic chemical measurements due to the complex interactions between the unmanned aerial vehicles (UAVs), the ambient air, and obstacles. The localization method is split into two phases: a search phase, where the agents cover the area and look for an initial chemical reading; followed by a convergence phase, where UAV agents utilize a particle swarm optimization (PSO) algorithm to locate the source of the chemical leak. The decentralized source-localization method enables a swarm of UAVs to safely travel in a complex environment and avoid obstacles and other agents while searching for the leaking source. The method is validated in simulation using realistic dynamic chemical plumes and through outdoor flight tests using a swarm of UAVs. The results demonstrate the feasibility of the approach.

URL: https://asmedigitalcollection.asme.org/DSCC/proceedings-abstract/DSCC2019/59162/1070608



### Collaborative infotaxis: Searching for a signal-emitting source based on particle filter and Gaussian fitting

Author: Song, Cheng; He, Yuyao; Ristic, Branko; Lei, Xiaokang

Publication Year: 2020

Publication Title: Robotics and Autonomous Systems

Abstract: To effectively leverage the spatio-temporal sensing capabilities of the team searching for a signal-emitting source, this paper presents a collaborative search method, in which each robot employs the weighted social Bayesian estimation and executes the distributed infotaxis search for the source. Cognition difference between robots, measuring the dissimilarity of probability maps, is specially introduced to obtain the heterogeneous weights of Bayesian estimation. However, the requirement of exchanging the whole probability map presents additional challenges in computation and communication for real-time applications. In this work, a solution for fast low-cost collaborative infotaxis method based on a combination of particle filter and Gaussian fitting is proposed. A particle filter is first employed for the representation of the source probability distribution, which makes the infotaxis strategy computationally tractable for large complex spaces using the limited and tractable amount of randomly drawn particles. By fitting a Gaussian density to the particles, each robot obtains the likelihood weight for social Bayesian estimation by only reporting the mean and the covariance matrix of Gaussian distribution rather than exchanging the whole probability maps. The simulation shows the proposed collaborative infotaxis can achieve an efficient search behavior in complex environments using a small number of particles and a lower communication bandwidth.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0921889019306451



### Decentralized Multi-agent information-theoretic control for target estimation and localization: finding gas leaks

Author: Bourne, Joseph R; Goodell, Matthew N; He, Xiang; Steiner, Jake A; Leang, Kam K

Publication Year: 2020

Publication Title: The International Journal of Robotics Research

Abstract: This article presents a new decentralized multi-agent information-theoretic (DeMAIT) control algorithm for mobile sensors (agents). The algorithm leverages Bayesian estimation and information-theoretic motion planning for efficient and effective estimation and localization of a target, such as a chemical gas leak. The algorithm consists of: (1) a non-parametric Bayesian estimator, (2) an information-theoretic trajectory planner that generates ?informative trajectories? for agents to follow, and (3) a controller and collision avoidance algorithm to ensure that each agent follows its trajectory as closely as possible in a safe manner. Advances include the use of a new information-gain metric and its analytical gradient, which do not depend on an infinite series like prior information metrics. Dynamic programming and multi-threading techniques are applied to efficiently compute the mutual information to minimize measurement uncertainty. The estimation and motion planning processes also take into account the dynamics of the sensors and agents. Extensive simulations are conducted to compare the performance between the DeMAIT algorithm to a traditional raster-scanning method and a clustering method with coordination. The main hypothesis that the DeMAIT algorithm outperforms the other two methods is validated, specifically where the average localization success rate for the DeMAIT algorithm is (a) higher and (b) more robust to changes in the source location, robot team size, and search area size than the raster-scanning and clustering methods. Finally, outdoor field experiments are conducted using a team of custom-built aerial robots equipped with gas concentration sensors to demonstrate efficacy of the DeMAIT algorithm to estimate and find the source of a propane gas leak.

URL: https://journals.sagepub.com/doi/full/10.1177/0278364920957090



### New Strategies Based on Improved Fruit Fly Optimization Algorithm for Unknown Indoor Odor Source Location

Author: Miao, Yanzi; Wang, Yue; Zhang, Jianwei

Publication Year: 2020

Publication Title: 2020 IEEE International Conference on Real-time Computing and Robotics (RCAR)

Abstract: It has great importance to locate the leaked source of hazardous odor in a ventilated indoor environment, for chemical warehouse safety and anti-terrorist explosion, etc. The distribution of odor plume is time-varying and intermittent in the indoor environment, which makes it difficult for single robot to locate the odor source. The multi-robot cooperative location of odor sources can reduce the interference of the above features and achieve high success rate of odor source localization. In this paper, the fruit fly optimization algorithm is applied to the odor source location problem, and a Fixed-step Fruit Fly Optimization Algorithm (FS-FOA) is proposed. To further improve the efficiency of the search and localization in the larger search range, a new strategy with adaptive algorithm for odor source localization is put forward, which is Concentration-Adaptive -Step Fruit Fly Optimization Algorithm (CAS-FOA). And the efficiency of the strategy in dynamic plume environment is validated in our experiments.

URL: https://ieeexplore.ieee.org/abstract/document/9303036



### Improved 'Infotaxis' Algorithm-Based Cooperative Multi-USV Pollution Source Search Approach in Lake Water Environment

Author: Huang, Xiaoci

Publication Year: 2020

Publication Title: Symmetry

Abstract: This paper studies the cooperation method of multi-cooperative Unmanned Surface Vehicles (USVs) for chemical pollution source monitoring in a dynamic water environment. Multiple USVs formed a mobile sensor network in a symmetrical or asymmetrical formation. Based on ‘Infotaxis’ algorithms for multi-USV, an improved shared probability is proposed for solving the problems of low success rate and low efficiency resulting from the cognitive differences of multi-USV in cooperative exploration. By introducing the confidence factor, the cognitive differences between USVs are coordinated. The success rate and the efficiency of exploration are improved. To further optimize the exploration strategy, the particle swarm optimization (PSO) algorithm is introduced into the ‘Infotaxis’ algorithm to plan the USVs’ exploration path. This method is called the ‘PSO-Infotaxis’ algorithm. The effectiveness of the proposed method is verified by simulation and laboratory experiments. A comparison of the test results shows that the ‘PSO-Infotaxis’ algorithm is superior with respect to exploring efficiency. It can reduce the uncertainty of the estimation for source location faster and has lower exploration time, which is most important for the exploration of a large range of water areas.

URL: https://www.mdpi.com/2073-8994/12/4/549



### Decentralised multi-platform search for a hazardous source in a turbulent flow

Author: Ristic, Branko; Gilliam, Christopher; Moran, William; Palmer, Jennifer L.

Publication Year: 2020

Publication Title: Information Fusion

Abstract: The paper presents a cognitive strategy that enables an interconnected group of autonomous vehicles (moving robots) to search and localise a source of hazardous emissions (gas, biochemical particles) in a coordinated manner. Dispersion of the emitted substance is assumed to be affected by turbulence, resulting in the absence of concentration gradients. The key feature of the proposed search strategy is that it can be applied in a completely decentralised manner as long as the communication network of autonomous vehicles forms a connected graph. By decentralised operation we mean that each moving robot performs computations (i.e. source estimation and robot motion control) locally. Coordination is achieved by exchanging the data with the neighbours only, in a manner which does not require global knowledge of the communication network topology.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1566253518303592



### Search and Localization of a Weak Source with a Multi-robot Formation

Author: Renzaglia, Alessandro; Briñón-Arranz, Lara

Publication Year: 2020

Publication Title: Journal of Intelligent & Robotic Systems

Abstract: This paper proposes an algorithm to guide a formation of mobile robots, subject to communication constraints, from an arbitrary position to the location of the source of a physical signal in a planar environment. The information on the signal is only based on noisy measurements of its strength collected during the mission and the signal is considered to be weak and indistinguishable from the noise in a large portion of the environment. The goal of the team is thus to search for a reliable signal and finally converge to the source location. An accurate estimation of the signal gradient is obtained by fusing the data gathered by the robots while moving in a circular formation. The algorithm proposed to steer the formation, called Gradient-biased Correlated Random Walk (GCRW), exploits the gradient estimation to bias a correlated random walk, which ensures an efficient non-oriented search motion when far from the source. The resulting strategy is so able to obtain a suitable trade-off between exploration and exploitation. Results obtained in simulated experiments, including comparisons with possible alternatives, are presented to analyze and evaluate the performance of the proposed approach.

URL: https://link.springer.com/article/10.1007/s10846-019-01014-0



### Cooperative information-driven source search and estimation for multiple agents

Author: Park, Minkyu; Oh, Hyondong

Publication Year: 2020

Publication Title: Information Fusion

Abstract: This paper proposes different levels of coordination methods for information-driven source search and estimation in a stochastic and turbulent atmospheric dispersion event. Multiple mobile sensors are assumed to communicate one another over a wireless network and share the minimal data (e.g. current position, sensor measurements, and control decision) to reduce the communication burden. The particle filter, sampling-based sequential Monte Carlo method, suitable for highly non-linear and non-Gaussian systems and the measurement sensor fusion method are used for the estimation of the source position and release rate. For efficient autonomous search, three coordination methods are introduced based on the Infotaxis algorithm: non-coordination, passive coordination, and negotiated coordination. To demonstrate the benefit of the proposed cooperative multi-mobile sensor system, extensive simulations on simulated and real experimental data are performed for different levels of coordination methods and the number of mobile sensors.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1566253518307656



### Multirobot searching method of natural gas leakage sources on offshore platform using ant colony optimization

Author: Ma, Tao; Liu, Shuhai; Xiao, Huaping

Publication Year: 2020

Publication Title: International Journal of Advanced Robotic Systems

Abstract: Natural gas leakage on offshore platforms has a great impact on safety production, and effective and reasonable leakage detection methods can prevent the harm caused by natural gas leakage. This article proposes a method based on ant colony optimization (ACO) for multirobots to collaboratively search for leaking natural gas sources on offshore platforms. First, analyze the structure and environment of the offshore platform, use Fluent software to simulate the diffusion process of natural gas leaked from the platform, and establish a diffusion model of natural gas leaked from various aspects, such as the layout of different platforms, the number of leaked gas sources, and the concentration of leaked gas sources. In terms of multirobot cooperative control, we analyzed and improved the ant colony algorithm and proposed a multirobot cooperative search strategy for gas search, gas tracking, and gas source positioning. The multirobot search process was simulated using MATLAB software, and the robot on the detection effect of multirobots was analyzed in many aspects, such as quantity, location of leak source, and a number of leak sources, which verified the feasibility and effectiveness of the multirobot control strategy based on optimized ACO. Finally, we analyze and compare the two control algorithms based on ACO and cuckoo search algorithm (CSA). The results show that the ACO-based multirobot air source positioning effect is significantly better than CSA.

URL: https://journals.sagepub.com/doi/full/10.1177/1729881420959012



### Particle swarm optimization for source localization in realistic complex urban environments

Author: Gunawardena, Nipun; Leang, Kam K.; Pardyjak, Eric

Publication Year: 2021

Publication Title: Atmospheric Environment

Abstract: In this work, we present a method to localize a source in complex urban environments using particle swarm optimization (PSO). Instead of using PSO to minimize the difference between a plume model and measurements as is often done, PSO is run such that each particle is modeled by an unmanned aerial vehicle (UAV) that measures and directly finds the global maximum of the concentration field. Several modifications were made to PSO to allow it to perform successfully in this application. The synthetic data used to test PSO were produced using the 3D building resolving Quick Urban & Industrial Complex Dispersion Modeling System (QUIC), and PSO was implemented in Python. Three different domains were tested: (1) a case with no obstacles, (2) a case with four large obstacles, and (3) a real-world case modeled after the Joint Urban 2003 experiment in Oklahoma City. We found that PSO works well in idealized and real cases. In the Oklahoma City simulation, approximately 90% of the PSO runs with 10 particles make it to within 1% of the maximum domain distance to the source, and approximately 98% of the PSO runs with 50 particles make it to within 1% of the maximum domain distance to the source. However, PSO is not completely immune to local maxima, and there is the possibility of convergence to the wrong point in the domain. The insight from this study can be used to inform first responders or create a tool that can be implemented on UAVs to locate a contaminant source.

URL: https://www.sciencedirect.com/science/article/abs/pii/S1352231021004581



### Sniffy Bug: A Fully Autonomous Swarm of Gas-Seeking Nano Quadcopters in Cluttered Environments

Author: Duisterhof, Bardienus P.; Li, Shushuai; Burgués, Javier; Reddi, Vijay Janapa; de Croon, Guido C. H. E.

Publication Year: 2021

Publication Title: 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Abstract: Nano quadcopters are ideal for gas source localization (GSL) as they are safe, agile and inexpensive. However, their extremely restricted sensors and computational resources make GSL a daunting challenge. We propose a novel bug algorithm named ‘Sniffy Bug', which allows a fully autonomous swarm of gas-seeking nano quadcopters to localize a gas source in unknown, cluttered, and GPS-denied environments. The computationally efficient, mapless algorithm foresees in the avoidance of obstacles and other swarm members, while pursuing desired waypoints. The waypoints are first set for exploration, and, when a single swarm member has sensed the gas, by a particle swarm optimization-based (PSO) procedure. We evolve all the parameters of the bug (and PSO) algorithm using our novel simulation pipeline, ‘AutoGDM'. It builds on and expands open source tools in order to enable fully automated end-to-end environment generation and gas dispersion modeling, allowing for learning in simulation. Flight tests show that Sniffy Bug with evolved parameters outperforms manually selected parameters in cluttered, real-world environments. Videos: https://bit.ly/37MmtdL

URL: https://ieeexplore.ieee.org/abstract/document/9636217



### Building synergetic consensus for dynamic gas-plume tracking applications using UAV platforms

Author: Kapoutsis, Athanasios Ch.; Michailidis, Iakovos T.; Boutalis, Yiannis; Kosmatopoulos, Elias B.

Publication Year: 2021

Publication Title: Computers & Electrical Engineering

Abstract: This article investigates the problem of deploying a swarm of UAVs equipped with gas sensors for industrial remote gas-plume sensing. This setup’s objective is to continuously adjust the swarm formation to maximize the combined perception for the dynamically evolved plume’s cloud, focusing around areas with the highest concentration/intensity. Initially, such a setup is formulated into an optimization problem, the solution of which could be acquired by the maximization of an appropriately defined objective function. Due to the model-free approach, this objective function’s analytical form is not available, prohibiting standard gradient descent methodologies. To this end, a tracking algorithm is developed and studied, which operates in a distributed manner and enables the UAV swarm to build a common consensus dynamically, during the evolution of the leakage phenomenon. The overall performance is tested in a simulative yet realistic environment using ANSYS Fluent suite, considering a simultaneous gas-leak incident at two different points. Aside from the standalone evaluation study, the proposed gas-plume tracking scheme is able to outperform a state-of-the-art alternative algorithm, namely Efficient Global Optimization (EGO), in various simulation setups, deploying a different number of UAVs on the field.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0045790621000525



### Tiny Robot Learning (tinyRL) for Source Seeking on a Nano Quadcopter

Author: Duisterhof, Bardienus P.; Krishnan, Srivatsan; Cruz, Jonathan J.; Banbury, Colby R.; Fu, William; Faust, Aleksandra; de Croon, Guido C. H. E.; Janapa Reddi, Vijay

Publication Year: 2021

Publication Title: 2021 IEEE International Conference on Robotics and Automation (ICRA)

Abstract: We present fully autonomous source seeking onboard a highly constrained nano quadcopter, by contributing application-specific system and observation feature design to enable inference of a deep-RL policy onboard a nano quadcopter. Our deep-RL algorithm finds a high-performance solution to a challenging problem, even in presence of high noise levels and generalizes across real and simulation environments with different obstacle configurations. We verify our approach with simulation and in-field testing on a Bitcraze CrazyFlie using only the cheap and ubiquitous Cortex-M4 microcontroller unit. The results show that by end-to-end application-specific system design, our contribution consumes almost three times less additional power, as compared to a competitive learning-based navigation approach onboard a nano quadcopter. Thanks to our observation space, which we carefully design within the resource constraints, our solution achieves a 94% success rate in cluttered and randomized test environments, as compared to the previously achieved 80%. We also compare our strategy to a simple finite state machine (FSM), geared towards efficient exploration, and demonstrate that our policy is more robust and resilient at obstacle avoidance as well as up to 70% more efficient in source seeking. To this end, we contribute a cheap and lightweight end- to-end tiny robot learning (tinyRL) solution, running onboard a nano quadcopter, that proves to be robust and efficient in a challenging task.

URL: https://ieeexplore.ieee.org/abstract/document/9561590



### Source Seeking by Dynamic Source Location Estimation

Author: Zhang, Tianpeng; Qin, Victor; Tang, Yujie; Li, Na

Publication Year: 2021

Publication Title: 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Abstract: This paper focuses on the problem of multi-robot source-seeking, where a group of mobile sensors localizes and moves close to a single source using only local measurements. Drawing inspiration from the optimal sensor placement research, we develop an algorithm that estimates the source location while approaches the source following gradient descent steps on a loss function defined on the Fisher information. We show that exploiting Fisher information gives a higher chance of obtaining an accurate source location estimate and naturally leads the sensors to the source. Our numerical experiments demonstrate the advantages of our algorithm, including faster convergence to the source than other algorithms, flexibility in the choice of the loss function, and robustness to measurement modeling errors. Moreover, the performance improves as the number of sensors increases, showing the advantage of using multi-robots in our source-seeking algorithm. We also implement physical experiments to test the algorithm on small ground vehicles with light sensors, demonstrating success in seeking a moving light source.

URL: https://ieeexplore.ieee.org/abstract/document/9636841



### Locating a time-varying contaminant source in naturally ventilated indoor environments: An experimental study to find effective multi-robot olfaction methods

Author: Zhou, Suwan; Zhang, Canxin; Cai, Hao; Zhang, Biao; Feng, Qilin; Feng, Lihang; Li, Fei; Zhou, Bin

Publication Year: 2022

Publication Title: Building and Environment

Abstract: The multi-robot olfaction method is critical to ensure the health and safety of indoor environments. This research aims to find effective multi-robot olfaction methods for locating time-varying sources in naturally ventilated indoor environments. A source positioning system composed of three mobile robots was developed for locating two types of time-varying sources (periodic source and decaying source). A total of 120 validation experiments were first conducted in real natural ventilation environments. In these experiments, the average success rates of the proposed IPSO and IWOA methods reached 81.68% and 80.00%, respectively. In addition, these two methods only required approximately 30% of the source localization time compared with the two typical scanning methods. For a fair comparison of different methods, another 120 experiments were then conducted in imitated natural ventilation environments. In these experiments, the success rates of the IPSO and IWOA methods varied between 80% and 86.7%, while those of the SPSO and WUII methods ranged between 20% and 33.3%. The experimental results indicated that the IPSO and IWOA methods were far superior to the SPSO and WUII methods in locating a time-varying source in naturally ventilated indoor environments due to their strong robustness and high efficiency.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132322001962



### Behavior Composition for Marine Pollution Source Localization Using a Mobile Sensor Network

Author: Cao, Mengli; Bie, Haofan; Hu, Xiong

Publication Year: 2022

Publication Title: Applied Sciences

Abstract: Marine pollution, which can cause damage to marine ecosystems, cut fishery production, and even harm human health, has aroused worldwide interest in recent years. Marine pollution reduction operations can stagnate in the case that the source of the pollution is unknown or hidden. In this paper, we present a novel method for marine pollution source localization using a network of mobile sensor nodes, such as autonomous underwater vehicles equipped with chemical sensors. Traditional reactive control methods can respond quickly to the shape dynamics of a chemical plume; however, they can hardly achieve intelligent cooperation unlike deliberative methods. In this study, we present a behavior composition method that attempts to combine the advantages of reactive and deliberative methods. An upwind-customized crossover operation based on the genetic algorithm was formulated as one of the elementary behaviors. The upwind sprint and movement away from the centroid of the sensor nodes were also modeled as another two elementary behaviors. Different sensor nodes are capable of different simultaneous elementary behaviors, enabling behavior composition in the mobile sensor network during plume source localization. The proposed method was evaluated using a widely used filamentous plume simulation platform, which has been used to facilitate field experiments in real marine environments. Simulation results indicate that the proposed method achieved high time-efficiency and localization accuracy during plume source localization in marine environments.

URL: https://www.mdpi.com/2076-3417/12/12/5767



### Improvement of optimization methods in indoor time-variant source parameters estimation combining unsteady adjoint equations and flow field information

Author: Wang, Fuyu; Zhou, Xuanyi; Kikumoto, Hideki

Publication Year: 2022

Publication Title: Building and Environment

Abstract: When hazardous gas leaks, accurate and prompt identification of leakage location and leakage rate is essential for ensuring indoor air quality and environmental safety. In the process of source parameters estimation, precise establishment of source-detector relationship is critical. Although computational fluid dynamics (CFD) simulation has high accuracy, it demands massive computing time. Prior studies mainly concentrate on estimating constant release sources, and few of them focus on time-variant sources peculiarly under indoor complex flow. Therefore, this paper further develops optimization methods based on fixed-detector networks by combining unsteady adjoint equations and flow field information. With only three fixed detectors, the effectiveness of proposed method is tested by estimating three time-variant source parameters under complex indoor flow. The results indicate that the application of unsteady adjoint equations not only saves a huge amount of computation but also preserves the high accuracy of CFD simulation, making it possible to estimate time-variant sources promptly and accurately under indoor complex flow. For the convenience of practical application, performances of five commonly used optimization methods and three common cost functions are compared carefully. The results show that the cost function gradient determines their different estimation performances. In addition, the reason for the formation of local optimal areas is analyzed and the flow field information is utilized to avoid the problem that optimization methods may converge to local optimal values, which improves the accuracy of estimated results significantly.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132322009404



### An experimental study on locating time-varying pollutant sources in a dynamic indoor environment with mechanical ventilation based on multi-robot cooperation

Author: Liao, Yu; Chen, Axiang; Cai, Hao; Lu, Jingyu; Zhang, Wei; Lin, Bencheng; Guo, Xun; Wei, Ling; Tong, Yan

Publication Year: 2023

Publication Title: Journal of Building Engineering

Abstract: Using robots to locate indoor pollutant sources has attracted increasing attention in recent years, which is important for securing people's health and safety indoors. However, few studies have addressed the common scenarios for locating a time-varying source (release rate varies over time) in dynamic indoor environments with mechanical ventilation (condition of supply airflow varies over time). In such scenarios, the coupling effect of indoor dynamic airflow and time-varying source pose great challenges to robots locating the source. To address these challenges, in this study, a mobile robot olfaction system equipped with three robots was developed and 180 experiments in a laboratory were performed. Two methods, namely, the improved particle swarm optimization (IPSO) method and the improved whale swarm algorithm (IWOA) method, were first validated, followed by comparisons with two other methods, the standard particle swarm optimization (SPSO) method and wind utilization II (WUII) method. Both the IPSO and IWOA methods show potential for practical application due to their high success rates (averaging 78.33% and 88.33%, respectively) and localization efficiency, while the success rates of the SPSO and WUII methods (less than 50%) are insufficient for practical application.

URL: https://www.sciencedirect.com/science/article/abs/pii/S2352710223001419



### Distributed Information-Based Source Seeking

Author: Zhang, Tianpeng; Qin, Victor; Tang, Yujie; Li, Na

Publication Year: 2023

Publication Title: IEEE Transactions on Robotics

Abstract: In this article, we design an information-based multirobot source seeking algorithm where a group of mobile sensors localizes and moves close to a single source using only local range-based measurements. In the algorithm, the mobile sensors perform source identification/localization to estimate the source location; meanwhile, they move to new locations to maximize the Fisher information about the source contained in the sensor measurements. In doing so, they improve the source location estimate and move closer to the source. Our algorithm is superior in convergence speed compared with traditional field climbing algorithms, is flexible in the measurement model and the choice of information metric, and is robust to measurement model errors. Moreover, we provide a fully distributed version of our algorithm, where each sensor decides its own actions and only shares information with its neighbors through a sparse communication network. We perform extensive simulation experiments to test our algorithms on large-scale systems and implement physical experiments on small ground vehicles with light sensors, demonstrating success in seeking a light source.

URL: https://ieeexplore.ieee.org/abstract/document/10250987



### Regression-enhanced Entrotaxis as an autonomous search algorithm for seeking an unknown gas leakage source

Author: Zhao, Xiangyu; Zhou, Wang; Cheng, Kuang; Cao, Yi; Yang, Shuang-Hua

Publication Year: 2024

Publication Title: Expert Systems with Applications

Abstract: Rapid localization of hazardous gas leak sources is a vital task regarding the security of human society. Over the past few decades, autonomous search using mobile sensing devices equipped with gas sensors has become a promising field. Cognitive search strategies, such as Infotaxis and Entrotaxis, have been successfully used to search an unknown source autonomously in turbulence. However, they are time-consuming and may not be efficient because all source parameters (locations and strength) are estimated via particle filtering, especially when the prior information of source strength is rarely known. To address this inefficiency, this paper proposes a hybrid autonomous source searching approach, named as regression-enhanced Entrotaxis, which incorporates the Entrotaxis algorithm with the regression methods. Only the position of leak source is inferred by particle filtering, while the strength is estimated by the least squares based on the historical measurements. Through this way, the searching space in particle filtering is converted from 3-dimensions (source position in x–y plane and source strength) to 2-dimensions (source position in x–y plane), speeding up the computation significantly. Then, the reward function according to maximum entropy sampling principles is utilized to guide the robot’s next move. The performance of the proposed method is compared to that of the Entrotaxis algorithm. The results of Monte Carlo simulations demonstrate that fewer particles will be used to reach a specific success rate, saving time in the search process. Besides, the proposed strategy relies on less prior information regarding source strength, which is more in line with the actual scenario. In addition, the proposed approach is adaptable to a broader search region.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0957417423030713



### Multiple source tracking and identifications in urban regions with unstable wind flows: Particle swarm optimization methodologies and their benchmark solutions

Author: Zhang, Hong-Liang; Chen, Jun-Hao; Li, Bin; Wang, Wei-Wei; Zhao, Fu-Yun

Publication Year: 2024

Publication Title: Building and Environment

Abstract: The prompt and accurate identification of transient pollution sources in urban regions is imperative for effective pollutant control and the mitigation to public health risks. Depending on sparse concentration distributions, multiple pollution sources identification is inherently complex and difficult, particularly when the pollutant sources exhibit time-varying release rates and are located in urban environments subject to dynamic wind flows. In this research, two niche-based Particle Swarm Optimization (PSO) algorithms, Niche-DPSO (niche pso for dynamic systems) and RSNM-DPSO (ranged subgroup pso with nelder mead for dynamic systems), were simultaneously proposed, aiming to localize multiple pollution sources under the background of unsteady wind flow fields. The MUST experiment, characterized by its complex layout replete with densely arranged obstacles, was adopted as the application scenario. Computational Fluid Dynamics (CFD) was employed to simulate the release of pollutant concentration at (−25.8 m, 0 m, 1.6 m) and (24.2 m, 41.6 m, 1.6 m), with flow velocities ranges from 1.8 to 7.6 m/s. Representative performance-influencing factors, including niche radius, population size, sensor response time, and sensor errors, were systematically evaluated. The results suggested that both Niche-DPSO and RSNM-DPSO algorithms were generally effective in positioning multiple pollution sources. Comparative analysis revealed that Niche-DPSO consistently outperformed RSNM-DPSO in terms of localization success rates, achieving a peak performance of approximately 98 %. Furthermore, Niche-DPSO could maintain its robust performance even under time-spatial-varying environmental and operational conditions, albeit at the expense of requiring more search steps and longer CPU processing time.

URL: https://www.sciencedirect.com/science/article/abs/pii/S0360132323010892



### Virtual-Source and Virtual-Swarm-Based Particle Swarm Optimizer for Large-Scale Multi-Source Location via Robot Swarm

Author: Zhang, JunQi; Lin, YuXuan; Zhou, MengChu

Publication Year: 2024

Publication Title: IEEE Transactions on Evolutionary Computation

Abstract: Multi-source location is a significant application in the field of robot swarm and is required to find all sources whose number and distribution are unknown in advance. With few parameters and fast search, Particle Swarm Optimizer (PSO) variants that have certain grouping capability have been applied to address multi-source location problems by dividing a swarm such that every source has robots to locate. However, they are difficult to predetermine the exact number of groups, require a big number of robots, and are easily trapped in the no-signal areas when the proportion of no-signal areas is high. This work proposes a Virtual-source and Virtual-swarm-based PSO (VVPSO) to divide a search area into multiple cells equally, each of which has a virtual source in its center. Then, instead of robots grouping, only one group of robots is employed to traverse all virtual sources, and search their corresponding cells to locate real sources by a new PSO called Real-virtual mapping PSO (RMPSO). RMPSO asymmetrically maps a robot into a particle swarm with multiple virtual particles to perform PSO, which greatly reduces the requirements for the number of robots. Experimental results show that VVPSO has great search scalability and can solve large-scale multi-source location problems than two state-of-the-art grouping methods and three representative multimodal PSO variants, even with only one robot. Hence, this work greatly advances the field of multi-source location by using mobile robot swarm.

URL: https://ieeexplore.ieee.org/abstract/document/10517352



### A Priority-Based Multi-Robot Search Algorithm for Indoor Source Searching

Author: Wang, Miao; Xin, Bin; Jing, Mengjie; Qu, Yun

Publication Year: 2025

Publication Title: IEEE Transactions on Automation Science and Engineering

Abstract: It is extremely important to quickly locate the source of a hazardous substance leak in order to reduce damage to life and property. Multi-robot source localization faces challenges in unknown indoor environments, such as navigating through dense environments, encountering large areas without airflow or concentration clues, experiencing frequent changes in robot measurements, and managing clusters of robots in confined spaces. This study proposes a priority-based multi-robot search algorithm to tackle these challenges. The algorithm consists of a priority-based search strategy, an exploration method based on frontier and Voronoi diagram, an airflow tracking method based on Rapidly-exploring Random Trees Star (RRT*), and a multi-robot collaborative method. The algorithm was compared with three other state-of-the-art algorithms in simulated environments, assessing varying team sizes, airflow speeds, and diverse scenarios. The algorithm was also evaluated in real-robots experiments. The evaluation results demonstrate that the algorithm exhibits outstanding performance in both simulated and real-robots experiments. Note to Practitioners—The aim of this study is to propose a multi-robot search algorithm designed to address the challenges encountered in source searching within unknown indoor environments. These challenges include navigating through dense environments, large areas without airflow and concentration clues, frequent changes in robot measurements, and the clusters of robots in confined spaces. This study proposes a priority-based multi-robot search algorithm. The core idea of the algorithm is to enable robots to adopt different search methods depending on their measurements. When lacking valid airflow and concentration measurements, robots engage in spatial exploration using an exploration method based on frontier and Voronoi diagram to increase the likelihood of encountering the plume. When robots are within a plume, they rely on an RRT*-based airflow tracking method to move towards the source. The RRT* also provides robots with reachable navigation goals in environments with dense obstacles. The multi-robot collaborative method operates based on the priority levels assigned to the robots. On one hand, it directs robots towards the global best to reduce search time. On the other hand, robots ignore global bests that are not of a higher priority than their own, preventing the clustering of multiple robots at the same location. The algorithm was compared with three other state-of-the-art algorithms in simulated environments. It was also evaluated in real-robots experiments. The evaluation results show that the algorithm exhibits outstanding performance in both simulated and real-robots experiments. To further aid research in this field, a dataset for multi-robot indoor source searching has been created and made available online to provide a benchmark for related research.

URL: https://ieeexplore.ieee.org/abstract/document/10832132



## Review



### An Evaluation of Gas Source Localization Algorithms for Mobile Robots

Author: Ojeda, Pepe; Monroy, Javier; Gonzalez-Jimenez, Javier

Publication Year: 2020

Publication Title: Proceedings of the 3rd International Conference on Applications of Intelligent Systems

Abstract: This paper presents a comparative evaluation of different approaches to the problem of gas source localization (GSL) with a mobile robot. Concretely, four state-of-the-art algorithms are implemented and evaluated: Surge-Cast, Spiral, Surge-Spiral and a Probabilistic (Particle Filter-based) method. The experiments have been carried out with the gas dispersion simulator GADEN and the robotic tools offered by ROS (Robotic Operating System) under diverse, realistic environments that feature obstacles and turbulent airflows. Our study reveals, among other results, that Surge-Spiral out-performs Surge-Cast under turbulent wind conditions, and the particle filter approach becomes advantageous only when the assumption of a homogeneous wind holds. We believe that these findings can help the research community to decide on the most appropriate GSL method for a given application. Besides, the code that implements these algorithms is made publicly available.

URL: https://dl.acm.org/doi/abs/10.1145/3378184.3378220



### Odor source localization of multi-robots with swarm intelligence algorithms: A review

Author: Wang, Junhan; Lin, Yuezhang; Liu, Ruirui; Fu, Jun

Publication Year: 2022

Publication Title: Frontiers in Neurorobotics

Abstract: The use of robot swarms for odor source localization (OSL) can better adapt to the reality of unstable turbulence and find chemical contamination or hazard sources faster. Inspired by the collective behavior in nature, swarm intelligence (SI) is recognized as an appropriate algorithm framework for multi-robot system due to its parallelism, scalability and robustness. Applications of SI-based multi-robots for OSL problems have attracted great interest over the last two decades. In this review, we firstly summarize the trending issues in general robot OSL field through comparing some basic counterpart concepts, and then provide a detailed survey of various representative SI algorithms in multi-robot system for odor source localization. The research field originates from the first introduction of the standard particle swarm optimization (PSO) and flourishes in applying ever-increasing quantity of its variants as modified PSOs and hybrid PSOs. Moreover, other nature-inspired SI algorithms have also demonstrated the diversity and exploration of this field. The computer simulations and real-world applications reported in the literatures show that those algorithms could well solve the main problems of odor source localization but still retain the potential for further development. Lastly, we provide an outlook on possible future research directions.

URL: https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2022.949888/full



### Gas source localization and mapping with mobile robots: A review

Author: Francis, Adam; Li, Shuai; Griffiths, Christian; Sienz, Johann

Publication Year: 2022

Publication Title: Journal of Field Robotics

Abstract: Within the last couple of decades, there has been increasing research into the use of mobile robots for gas sensing applications. This has led to many different branches of research, most notably on the topics of gas distribution mapping and source localization. This paper aims to provide an up to date and comprehensive overview of the research on these topics for both controlled and uncontrolled environments with ground-based or aerial robots. To complement other review papers, a greater focus is placed on recent probabilistic algorithms developed for both single robot and multirobot applications.

URL: https://onlinelibrary.wiley.com/doi/full/10.1002/rob.22109

