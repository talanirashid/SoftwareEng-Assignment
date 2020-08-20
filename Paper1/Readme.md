# PAPER 1 : [Scalable Analysis of Interaction Threats in IoT Systems](./paper1/readme.md "View Submission")

[![Generic badge](https://img.shields.io/badge/Conference-ISSTA%202020-orange.svg)](https://conf.researchr.org/home/issta-2020) [![Generic badge](https://img.shields.io/badge/Track-Technical%20Papers-orange.svg)](https://conf.researchr.org/track/issta-2020/issta-2020-papers) ![Generic badge](https://img.shields.io/badge/When-Tue%2021%20Jul%202020%2013%3A50%20--%2014%3A10-orange.svg)

### **AUTHORS :** Mohannad Alhanahnah, Clay Stevens, Hamid Bagheri


### **Abstract**

The omnipresence of Internet of Things (IoT) and our growing reliance on IoT apps are leaving us more vulnerable to safety and security threats than ever before. This paper presents IoTCOM, an approach to automatically discover hidden and unsafe interaction threats in a compositional and scalable fashion.

### **Introduction**

Internet of Things(IoT) is a network of physical objects or people called "things" that are embedded with software, electronics, network, and sensors that allows these objects to collect and exchange data. The goal of IoT is to extend to internet connectivity from standard devices like computer, mobile, tablet to relatively dumb devices like a toaster.
IoT makes virtually everything "smart," by improving aspects of our life with the power of data collection, AI algorithm, and networks. The thing in IoT can also be a person with a diabetes monitor implant, an animal with tracking devices, etc.
The increased complexity produced by the coordination and interaction of these apps subjects the system to the risk of undesired behavior, whether by misconfiguration, developer error, or malice. For example, an app that unlocks the door when a user returns home may be subverted—either accidentally or intentionally—to unlock the door when the user is not actually present. This risk is exacerbated by the unpredictable nature of IoT environments, as it is not known a priori which apps and devices will be installed in tandem. The increased impact of these physical risks makes identification of risky interactions even 
more important. 
In this context, the safety implications and security risks of IoTs have been a thriving subject of research for the past few years. To address this state of affairs, this paper presents a novel approach and accompanying tool suite, called IotCom, for compositional analysis of such hidden and unsafe interaction threats in a given bundle of cyber and physical components co-located in an IoT environment.


### **RESULTS**

This paper presents a novel approach for compositional analysis of IoT interaction threats. Our approach employs static analysis to automatically derive models that reflect behavior of IoT apps and interactions among them. The approach then leverages these models to detect safety and security violations due to interaction of multiple apps and their embodying physical environment that cannot be detected with prior techniques that concentrate on interactions within the cyber boundary. We formalized the principal elements of our analysis in an analyzable specification language based on relational logic, and developed a prototype implementation, IotCom, on top of our formal analysis framework. The experimental results of evaluating IotCom against prominent IoT safety and security properties, in the context of thousands of real-world apps, corroborates its ability to effectively detect violations triggered through both virtual and physical interactions.
