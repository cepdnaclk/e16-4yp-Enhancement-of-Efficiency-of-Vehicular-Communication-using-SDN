---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e16-4yp-Enhancement-of-Efficiency-of-Vehicular-Communication-using-SDN
title:
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Enhancement of the Efficiency of Vehicular Communication using SDN

#### Team

- E/16/055, S.Bragadeeshan, [email](mailto:e16055@eng.pdn.ac.lk)
- E/16/115, S.Girishikan, [email](mailto:e16115@eng.pdn.ac.lk)
- E/16/172, V.Karikaran, [email](mailto:e16172@eng.pdn.ac.lk)

#### Supervisors

- Dr. Suneth Namal, [email](mailto:namal@eng.pdn.ac.lk)

#### Table of content

1. [Abstract](#abstract)
2. [Related works](#related-works)
3. [Methodology](#methodology)
4. [Experiment Setup and Implementation](#experiment-setup-and-implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)
7. [Publications](#publications)
8. [Links](#links)
9. [Reference](#reference)

---

<!-- This is a sample image, to show how to add images to your page. To learn more options, please refer [this](https://projects.ce.pdn.ac.lk/docs/faq/how-to-add-an-image/)

![Sample Image](./images/sample.png) -->

## Abstract
This research article explores software-defined networking (SDN) in vehicular ad hoc networks (VANET), which are networks formed by vehicles communicating with each other. Mobility is a key factor that can impact network performance in VANET, and traditional network architectures can struggle to handle the frequent changes in network topology caused by vehicle movement.
The study focuses on using the reactive routing protocol Ad hoc On-Demand Distance Vector (AODV) in an SDN architecture for VANET. The performance of this setup was analyzed based on essential quality of service (QoS) metrics, including packet delay and transfer rate. The results of the study showed that the highest packet delay in VANET using SDN was lower than that of traditional network architectures, and the packet transfer rate was higher.
The use of SDN in VANET enables a more adaptable and dynamic network architecture that can respond quickly to changes in network conditions caused by vehicle mobility. By separating the control plane from the data plane, SDN enables centralized management of the network, making it easier to adjust network configurations to accommodate changes in network topology dynamically. This research suggests that SDN can be an effective solution for improving network performance in mobile environments such as VANET and that the use of reactive routing protocols like AODV can further enhance this performance.


## Related works
In recent years, numerous studies have been conducted to analyze the performance of various VANET protocols under different conditions and parameters. For instance, Peng et al. [1] compared the performance of the Proactive routing protocol in a more realistic city scenario based on the average packet ratio and average end delay. Their findings indicate that AODV is more suitable for VANET and DSR.

Similarly, Fang et al. [2] compared AODV and DSR in a VANET city scenario in terms of throughput and end-to-end delay with varying densities. They concluded that AODV is better than DSR, particularly when the number of vehicles is increased, providing sufficient throughput with lower delay.

Moreover, Shukla et al. [3] observed the performance of reactive routing protocols in VANET using a realistic mobility model. They used NS2 to measure the performance and found that AODV outperformed other routing protocols in VANET.

In another study, V. Rajeshkumar and P. Sivakumar [4] analyzed the performance of AODV, DSDV, and DSR routing protocols in MANET. Their results showed that AODV performed the best, especially in maintaining connection by periodic exchange of data. Furthermore, AODV and DSR demonstrated better performance than DSDV, particularly when the network has a large number of nodes.

Recently, Habib and Rutuja [5] implemented the DSDV routing protocol in SDN and analyzed its performance. Their study found that DSDV performed better in SDN than other traditional network architectures. Theoretically, SDN gives the best performance compared to other network architectures since the data plane and control plane are separated in SDN. Additionally, their work showed that the AODV routing protocol outperformed other routing protocols like DSR and DSDV in SDN. They implemented the AODV routing protocol in SDN and analyzed the performance using quality of service (QoS) metrics.

For instance, in [6], AODV, DSDV, and AOMDV were simulated and compared in a realistic environment. Similarly, a study in [7] analyzed the performance of AODV, DSR, and Swarm. Moreover, the performance of AODV, DSR, and DSDV in freeway environments was discussed in [8]. In [9], OLSR and AODV were compared in an urban realistic environment, while in a highly fading environment, their performance was evaluated in [10]. In a city traffic scenario, a study in [11] evaluated FSR, AODV, DSR, and TORA. These studies provide valuable insights into the performance of different routing protocols under various conditions and parameters, which can be used to enhance the overall performance of VANETs.


## SDN and VANET
In traditional network infrastructures, maintenance can be expensive due to the variety and complexity of network elements [12]. Frequent network failures also decrease the reliability of the underlying infrastructure. Overall network implementation, configuration, and troubleshooting require highly skilled network technicians. In SDN, however, networking elements such as routers, switches, and access points are separated from the data plane, which makes routing and forwarding decisions. This separation allows for programmability, centralized control, network flexibility, efficient configuration, and enhanced management.

The centralized control operation of SDN dictates network policies. Many open-source controller platforms are available for SDN, including Floodlight [13], OpenDayLight, and Beacon. The network is managed by different layers, including the application, control, and data plane. The application layer provides resources to customers, the control plane changes network policies and logical entities, and the data plane sets up physical network elements.

VANET technology is a wireless network for vehicles that merges the facilities of wireless networks. It creates a robust Ad-Hoc network between roadside units and vehicles and is part of the MANET family. VANETs use some ad-hoc networking tools, such as IEEE 802.11 bg (Wifi), IEEE 802.10 (WiMAX), and Bluetooth, to create a network between moving nodes. The goal of VANET is to provide safety-related information, monitor traffic, and communicate speed. VANET allows two moving vehicles to communicate with each other on the road. However, maintaining handoff can be challenging due to high-speed nodes.


## Methodology
The performance of the AODV routing protocol in an SDN-based wireless network is evaluated using Mininet-WiFi and the ONOS controller. Mininet-WiFi is a popular network emulator that allows for the simulation of wireless networks, while ONOS is a popular open-source SDN controller.The simulation setup consists of a wireless network with multiple Access Points (APs) and mobile nodes. The APs are connected to the ONOS controller, which is responsible for managing the network topology and routing decisions. The mobile nodes move randomly within the network, generating traffic and sending packets to each other.The performance of the AODV routing protocol is evaluated based on various Quality of Service (QoS) metrics such as packet delivery ratio. The experiments are conducted with varying network parameters such as the number of nodes, traffic load, and mobility patterns.The simulation results are collected and analyzed to compare the performance of AODV with other routing protocols. The performance of AODV is also evaluated with different network topologies, including scenarios with a varying number of APs and mobile nodes.To ensure the reliability of the results, each experiment is run multiple times, and the average value of the QoS metrics is calculated. The results are presented in the form of graphs and tables, showing the comparative performance of AODV with other routing protocols.Overall, the methodology involves simulating a wireless network using Mininet-WiFi with the ONOS controller and evaluating the performance of the AODV routing protocol based on various QoS metrics. The simulation results are used to compare the performance of AODV with other routing protocols and to evaluate the impact of network parameters on the performance of AODV.
### Architecture
![Architecture image text]([https://someurl/imagelocation/image.png](https://github.com/cepdnaclk/e16-4yp-Enhancement-of-Efficiency-of-Vehicular-Communication-using-SDN/blob/main/docs/images/arch.png))

In this hierarchical SDN controller architecture for SDN VANET, there are two levels of controllers. The first level of controllers is responsible for managing the SDN switches that are directly connected to the roadside units (RSUs). These controllers are referred to as local controllers and are in charge of handling the communication between the SDN switches and the second level of controllers.

The second level of controllers, known as the global controllers, is responsible for managing the overall VANET network. These controllers receive information from the local controllers and make global decisions on network policies, security, and mobility management. The global controllers are connected to the local controllers through a dedicated communication network.

The figure shows that the local controllers are connected to the SDN switches through a local control network, while the global controllers are connected to the local controllers through a global control network. This architecture provides a scalable solution for managing large-scale VANET networks. It allows for efficient management of network resources and enables centralized control of network policies while also enabling distributed decision-making.

### Network Design and Implementation
In this study, we used the Mininet-wifi simulator to implement the AODV routing protocol in an SDN network. Mininet-wifi is a widely used SDN network emulator that allows for the simulation of wireless networks. To capture simulation results, we used Wireshark and Iperf tools. To set up the environment, we used the Linux 14.04 operating system, as it provides the best support for running Mininet projects. The simulation area was defined as 100*100m. We designed a network for three cars, and then sequentially created networks for four, five, seven, and nine cars to analyze the performance. Table 1 shows the parameters and corresponding specifications used for the environment setup. In this study, we used the ONOS controller instead of the default OpenFlow controller to control the SDN network. The use of ONOS provides additional functionality, including support for multiple network topologies and device types. The performance of the AODV routing protocol was evaluated using metrics such as throughput, end-to-end delay, and packet delivery ratio.

| Parameters      | Specifications |
| ----------- | ----------- |
| OS  	| Linux 22.04  	|
| Network Simulator  	| Mininet-wifi 	|
| Controller  	| Onos   | 
| Simulation Area  	| 100m*100m 	|
| Number of vehicles  	| 3-12 cars  	|
| Transmission Range  	|250m 	|
| MAC Protocol  	| IEEE 802.11b  	|
| Channel type	|Wireless	|

### Performance Metrics
Maximum packet delay is a performance metric used to evaluate the effectiveness of the AODV routing protocol in the simulated SDN-based VANET. The maximum packet delay is calculated using the following formula [14]:

d = max(tr - tt) for i = 0 to n

where d is the maximum delay, n is the number of transmitted packets, tr is the time when the packet is received, and tt is the time when the packet is transmitted. This metric is used to compare the performance of the SDN-based VANET with a traditional network.


## Results and Analysis
In this study, we aimed to compare the performance of a software-defined network (SDN) architecture and traditional network architecture in a vehicular ad hoc network (VANET) environment using maximum packet delay as the performance metric. We also tested the seamless connectivity between access points when a vehicle moved from one access point to another in our proposed architecture.

To conduct the comparison, we used Mininet-wifi as the network simulator and AODV as the routing protocol, as AODV is commonly used in traditional VANET environments. We implemented and tested two different setups: VANET with SDN and AODV, and VANET with AODV only, without SDN.

The simulation was run for a fixed duration of 10 seconds in a predefined simulation area with varying numbers of nodes (3, 4, 5, 7, 9, and 11). The simulation results were analyzed to determine the maximum packet delay for both network architectures.

### Reachability
Figure 1 illustrates the process of vehicles communicating with each other through a controller. The network area is established by access points, while each car is referred to as a node or station (STA). When the destination car is within the network area, communication can be established. Figure 2 displays the response message generated after the ping operation is performed. If the destination car is not located within any access point, it will not be reachable. Figure 3 demonstrates the unreliability of the car in the communication process.


### Maximum Packet Delay
The performance of SDN is compared with the traditional network architecture [21] using Maximum Packet Delay as the performance metric. The comparison results between SDN and traditional network architecture for AODV are shown in Figure 4. It can be observed from the figure that SDN consistently outperforms traditional networks as the number of nodes increases.
![Alternate image text](https://github.com/cepdnaclk/e16-4yp-Enhancement-of-Efficiency-of-Vehicular-Communication-using-SDN/blob/main/docs/images/graph.png)

### Seamless Connectivity Test
To test the seamless connectivity between access points when a vehicle moved from one access point to another in our proposed architecture, we conducted a reliability test. We found that the proposed architecture provided seamless connectivity between access points as expected. However, when we checked the Maximum Packet Delay, we found that it was slightly higher than the Maximum Packet Delay in a single access point VANET environment.

To investigate this issue, we performed a root cause analysis and identified that the access point authentication delay was the probable cause of the higher Maximum Packet Delay. While the delay was minor, it did have a measurable impact on the overall performance of the proposed architecture.

Overall, our findings indicate that the SDN-based VANET architecture outperforms the traditional VANET architecture in terms of maximum packet delay. However, the seamless connectivity between access points can lead to a slightly higher maximum packet delay due to access point authentication delays. Further research can focus on optimizing the access point authentication process to minimize delays and enhance the overall performance of the proposed architecture.



## Conclusion
In conclusion, the deployment of Software-Defined Networking (SDN) in vehicular ad hoc networks (VANETs) offers significant benefits, including increased manageability, adaptability, and programmability. The separation of the control plane from the data plane and the programmable nature of the control plane makes SDN an ideal solution for handling the dynamic and unpredictable network topology that arises from vehicle mobility in VANETs.

This article has demonstrated the practical steps involved in deploying SDN in VANETs, including the use of the Mininet-WiFi emulator to create a car node for realistic experimentation. The results of the experiment showed that SDN/OpenFlow programmability offers new degrees of wireless and wired resource management in dynamic vehicular environments.

Furthermore, ongoing work in the Open Networking Foundation (ONF) Wireless and Mobile Working Group (WMWG) is exploring more complex scenarios with OpenFlow wireless extensions to evaluate the actual potential of SDN in wireless realms. The use of hybrid physical-virtual experimental environments is also being considered.

In terms of network performance, implementing Ad hoc On-Demand Distance Vector (AODV) as a reactive routing protocol in SDN architecture was found to have a lower maximum packet delay and faster packet transfer rates than traditional network architectures. This highlights the potential of SDN to improve network performance in mobile environments such as VANETs.

Overall, the practical validation of SDN in VANETs has shown promise, and further research and development in this area have the potential to lead to significant improvements in vehicular communication and safety.


## Publications
1. [Semester 7 report](mailto:e16055@eng.pdn.ac.lk)
2. [Semester 7 slides](https://drive.google.com/file/d/1qNPMzzCQkq7bm19bFe8Um0pGLGj1mxFt/view?usp=sharing)
3. [Semester 8 report](./)
4. [Semester 8 slides](https://docs.google.com/presentation/d/1w5GcJTS9TH5v161wV5eW_38iunlxY_XI/edit?usp=sharing&ouid=118043054665956893788&rtpof=true&sd=true)
5. Karikaran V, Bragadeeshan S and Girishikan S "Research paper title" (2021). [PDF](./).


## Links

[//]: # ( NOTE: EDIT THIS LINKS WITH YOUR REPO DETAILS )

- [Project Repository](https://github.com/cepdnaclk/e16-4yp-Enhancement-of-Efficiency-of-Vehicular-Communication-using-SDN)
- [Project Page](https://cepdnaclk.github.io/e16-4yp-Enhancement-of-Efficiency-of-Vehicular-Communication-using-SDN/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


## Reference
[1] P. Lv, B. Zheng, and Z. Zhou, “Simulation of vanet in a more realistic scenario,” in Wireless Communications, 
Networking and Mobile Computing (WiCOM), 2011 7th International Conference on. IEEE, 2011, pp. 1–3.

[2] X. Fang, K. Chai, Y. Alfadhl, and Y. Sun, “Evaluation of ad-hoc routing protocols in vehicular ad-hoc network using opnet,” in ITS Telecommunications (ITST), 2011 11th International Conference on. IEEE, 2011, pp. 39–44.

[3] R. S. Shukla and N. Tyagi, “Performance evaluation of mobility model and routing protocols for inter vehicular communication system,” in Emerging Trends in Networks and Computer Communications (ETNCC), 2011 International Conference on. IEEE, 2011, pp. 263–266.

[4] V. Rajeshkumar and P. Sivakumar, “Comparative study of aodv, dsdv and dsr routing protocols in manet using network simulator-2,” International Journal of Advanced Research in Computer and Communication Engineering, vol. 2, no. 12, pp. 2278–1021, 2013.

[5] R. K. Habib M, “A survey: Use of sdn on dsdv routing protocol in vanet,” International Journal of Scientific Engineering and Science, vol. 1, no. 11, pp. 53–57, 2017.

[6] Bhushan Vidhale and S.S. Dorle, “Performance Analysis of Routing Protocols in Realistic Environment for Vehicular Ad Hoc Networks”, 2011 21st International Conference on Systems Engineering.

[7] S. S. Manvi, M. S. Kakkasageri, C. V. Mahapurush, “Performance Analysis of AODV, DSR, and Swarm Intelligence Routing Protocols In Vehicular Ad hoc Network Environment”, 2009 International Conference on Future Computer and Communication. 

[8] Niansheng Liu, Huihuan Qian, Jingyu Yan, and Yangsheng Xu “Performance Analysis of Routing Protocols for Vehicle Safety Communications on the Freeway”, 3rd International Conference on Anticounterfeiting, Security, and Identification in Communication, 2009. ASID 2009.

[9] J´erome Haerri, Fethi Filali, and Christian Bonnet, “Performance Comparison of AODV and OLSR in VANETs Urban Environments under Realistic Mobility Patterns”, 5th IFIP Mediterranean Ad-Hoc Networking Workshop, June 14-17, 2006.

[10] Imran Khan and Amir Qayyum, “Performance Evaluation of AODV and OLSR in Highly Fading Vehicular Ad hoc Network Environments”, IEEE International Multitopic Conference, 2008. INMIC 2008.

[11] Sven Jaap, Marc Bechler and Lars Wolf, “Evaluation of Routing Protocols for Vehicular Ad Hoc Networks in City Traffic Scenarios”, 5th International Conference on Intelligent Transportation Systems (ITS) Telecommunications, 2005.

[12] B. K, “Software-defined networking (sdn): a survey, security and communication networks,” vol. 9, no. 18, pp. 5803–5833, 2016.

[13] “Floodlight controller, floodlight documentation, for developers, architecture. [online]. retrieved from: http://www.projectfloodlight.org/floodlight/.” 

[14] G. Z. Santoso and M. Kang, “Performance analysis of aodv, dsdv and olsr in a vanets safety application scenario,” in Advanced communication technology (ICACT), 2012 14th international conference on. IEEE, 2012, pp.





[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
