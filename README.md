# DRL-based-long-term-resource-management-in-MEC-network

![image](https://user-images.githubusercontent.com/82140899/202213539-acadf116-4cfd-422b-99df-1ea56b622a94.png)

A Pytorch implementation of deep reinforcement learning algorithm to manage long term resource scheduling between Multi-access edge servers (MECs)

Paper is publised in Transactions on Network and Service Management entitled "DRL-Based Long-Term Resource Planning for Task Offloading Policies in Multi-Server Edge Computing Networks". You can find it at https://ieeexplore.ieee.org/document/9831431. This work is supported by European Commission's Horizon 2020 research and innovation program under grant agreement No 871428, 5G-CLARITY project.

You may cite it via \
@article{li2022drl,\
  title={DRL-Based Long-Term Resource Planning for Task Offloading Policies in Multi-Server Edge Computing Networks},\
  author={Li, Haiyuan and Assis, Karcius DR and Yan, Shuangyi and Simeonidou, Dimitra},\
  journal={IEEE Transactions on Network and Service Management},\
  year={2022},\
  publisher={IEEE}\
}\

"Multi-access edge computing (MEC) has been regarded as one of the essential technologies for mobile networks, by providing computing resources and services close to users, thereby, avoiding extra energy consumption and fitting the low-latency ultra-reliable requirements for emerging 5G applications. Task offloading policy plays a pivotal role in handling offloading requests and maximizing the network computing performance. Most recently developed offloading solutions are designed for instant rewards, therefore, neglecting the long-term computing resource optimization at the edge, which fail to deliver optimized network performance when a significant increase of computing requests appears. In this paper, with the objective of maximizing long-term offloading benefits on delay and energy consumption, task offloading policies are proposed to firstly avoid resource over-distribution through deep reinforcement learning (DRL) based resource reservation and server cooperation, and secondly maximize the average instant reward and the utilization of reserved resources by an optimization-based joint policy consisting of offloading decision, transmission power allocation and resource distribution. The DRL-based joint policy is evaluated in a simulated multi-server edge computing network. Compared to previous solutions, the DRL-based algorithms achieve higher and more reliable overall rewards. Of the implemented three DRL-based algorithms, fully cooperative multi-agent DRL accounts for cooperation between servers, achieving a 70.5\% reduction in reward variance and a 13.4\% increase in average rewards over 500 continuous operations. Resource balanced policies on long-term rewards help edge networks handle the explosive growth of 5G computing-intensive applications in the future."

Contact info: \
Shuangyi Yan (shuangyi.yan@bristol.ac.uk)\
Haiyuan Li (ocean.h.li.2018@bristol.ac.uk)\
University of Bristol

