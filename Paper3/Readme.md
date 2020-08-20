# PAPER 3 : Understanding What Software Engineers Are Working on — The Work-Item Prediction Challenge

[![Generic badge](https://img.shields.io/badge/Conference-ICSE%202020-orange.svg)](https://conf.researchr.org/home/icpc-2020) [![Generic badge](https://img.shields.io/badge/Track-ICPC%20Industry-orange.svg)](https://conf.researchr.org/track/icpc-2020/icpc-2020-industry?track=ICPC%20Industry) ![Generic badge](https://img.shields.io/badge/When-Tue%2014%20Jul%202020%2015%3A48%20--%2016%3A00-orange.svg)

### **AUTHORS :** Ralf Lämmel, Alvin Kerber and Liane Praza

### **Introduction**

Understanding what a software engineer (a developer, an incident responder, a production engineer, etc.) is working on is a challenging problem – especially when considering the more complex software engineering workflows in software-intensive organizations: i) engineers rely on a multitude (perhaps hundreds) of loosely integrated tools; ii) engineers engage in concurrent and relatively long running workflows; ii) infrastructure (such as logging) is not fully aware of work items; iv) engineering processes (e.g., for incident response) are not explicitly modelled. In this paper, the corresponding ‘work-item prediction challenge’ is explained on the grounds of representative scenarios, report on related efforts at Facebook, discuss some lessons learned, and review related work to call to arms to leverage, advance, and combine techniques from program comprehension, mining software repositories, process mining, and machine learning.


### **Conclusion**

In this paper, we have established the work-item prediction challenge, as it applies to software engineering workflows in softwareintensive organizations.
The defining characteristics of the challenge are these: i) engineers rely on a multitude (perhaps hundreds) of loosely integrated tools; ii) engineers engage in concurrent and relatively long running workflows; ii) infrastructure (such as logging) is not fully aware of work items; iv) engineering processes (e.g., for incident response) are not explicitly modeled.
In practice, an ensemble of heuristic- and ML-based components is needed to predict work items on the timelines of employees. We have described related efforts at Facebook, where diffs (system changes), as a type of work item, are predicted. Such prediction is readily useful in the context of incident response in engineering (with relevance for reliability, integrity, privacy, and security) or the aggregation of key performance indicators for engineering processes.
We have provided an extended related work discussion which connects the work-item prediction challenge to research in the areas of program comprehension, mining software repositories, process mining, and machine learning. This discussion documents the need for and the potential of leveraging, advancing, and combining existing techniques to tackle the work-item prediction challenge more efficiently in practice.

