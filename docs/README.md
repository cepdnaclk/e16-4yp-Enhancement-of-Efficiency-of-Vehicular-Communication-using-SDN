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


## Methodology

## Experiment Setup and Implementation

## Results and Analysis

## Conclusion
In conclusion, the deployment of Software-Defined Networking (SDN) in vehicular ad hoc networks (VANETs) offers significant benefits, including increased manageability, adaptability, and programmability. The separation of the control plane from the data plane and the programmable nature of the control plane makes SDN an ideal solution for handling the dynamic and unpredictable network topology that arises from vehicle mobility in VANETs.

This article has demonstrated the practical steps involved in deploying SDN in VANETs, including the use of the Mininet-WiFi emulator to create a car node for realistic experimentation. The results of the experiment showed that SDN/OpenFlow programmability offers new degrees of wireless and wired resource management in dynamic vehicular environments.

Furthermore, ongoing work in the Open Networking Foundation (ONF) Wireless and Mobile Working Group (WMWG) is exploring more complex scenarios with OpenFlow wireless extensions to evaluate the actual potential of SDN in wireless realms. The use of hybrid physical-virtual experimental environments is also being considered.

In terms of network performance, implementing Ad hoc On-Demand Distance Vector (AODV) as a reactive routing protocol in SDN architecture was found to have a lower maximum packet delay and faster packet transfer rates than traditional network architectures. This highlights the potential of SDN to improve network performance in mobile environments such as VANETs.

Overall, the practical validation of SDN in VANETs has shown promise, and further research and development in this area have the potential to lead to significant improvements in vehicular communication and safety.


## Publications
1. [Semester 7 report](./)
2. [Semester 7 slides](./)
3. [Semester 8 report](./)
4. [Semester 8 slides](./)
5. Author 1, Author 2 and Author 3 "Research paper title" (2021). [PDF](./).


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



[//]: # "Please refer this to learn more about Markdown syntax"
[//]: # "https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet"
