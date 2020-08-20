# PAPER 2 : How Graduate Computing Students Search When Using an Unfamiliar Programming Language

[![Generic badge](https://img.shields.io/badge/Conference-ICSE%202020-orange.svg)](https://2020.icse-conferences.org/) [![Generic badge](https://img.shields.io/badge/Track-ICPC%20Research-orange.svg)](https://conf.researchr.org/track/icpc-2020/icpc-2020-research?track=ICPC%20Research) ![Generic badge](https://img.shields.io/badge/When-Tue%2014%20Jul%202020%2015%3A00%20--%2015%3A12-orange.svg)

### **AUTHORS :** Gina Bai, Joshua Kayani and Kathryn Stolee

### **Abstract**

Developers and computing students are usually expected to master multiple programming languages. To learn a new language, developers often turn to online search to find information and code examples. However, insights on how learners perform code search when working with an unfamiliar language are lacking. This research is about how computing students search for code in an unfamiliar programming language.

### **INTRODUCTION**

Software is written using multiple programming languages, which expects the developers to master multiple programming languages. Recent research has shown that knowledge of one language can interfere with learning a new language. When learning a new language, developers use an opportunistic learning strategy, relating concepts in a new language to their previous languages. As the terminology between languages often differs drastically, this makes code search especially difficult. Yet, developers frequently turning to code search to find code examples to learn from and improve their productivity during development activities. Studies on code search in software engineering seek to understand how and why developers search when performing their daily work, introduce new code search tools or propose potential improvement of existing code search tools, and suggest effective code search strategies. The code search studies are most often performed in the wild, so to observe developers during their normal activity.
As prior work has observed difficulties when developers search for concepts in a new language, we have reason to believe that code search for subsequent language learners is different than code search during normal development activities. Consider the following scenario:
> *A Computer Science student gets an internship at a bank. Their team manager is happy that they have several years of programming experience, and expects them to program with Visual Basic for Applications (VBA) and create macros in spreadsheets. However, the student has never been taught VBA at school, and now they have to learn this new language on their own.
The intern gets their first task, and decides to search online for how to perform it in VBA, but the keywords are specific to the language they know, such as “dictionary” from Java paired with their new context, VBA. This leads to results that are either in VBA but with information not relevant to the task at hand, or results in Java that are relevant, but in the wrong language. The intern wonders, “is there any way to improve the search success? What online sources should be consulted?”*

In this scenario, the intern cannot find the resources they want due to mismatched terminology between the language they know, Java, and the language they need, VBA. This common situation is observed in prior research; in this exploratory work on code search, we target students learning a new language.


### **RESEARCH METHODOLOGY**

Methodology circulates around logging search and browser activity and how periodically serve each participant about their current task and activity. Highlighted points of methodology are given below:
• To seek on the factors that make a query successful.
• To provide better understanding of the code search results of related languages learners. 
• Suggestions on improving the success of searches when learners working with an unfamiliar language.


They have covered 3 questions:
RQ1: why do subsequent languages learn search?
RQ2: what does a typical session entail for subsequent language learner?
RQ3: what are the factors that impact the success of each query for subsequent language learner?

They choose VBA (virtual basic for application) because it is very popular learning language 
With many online usage. But it is not commonly used by in the first graduate in computer science.
The five tasks which are given to learners are given below:
1.Provide participants a list of numbers in a column and ask participants to record a macro and create a button that return the average value of numbers.
2.Require participants to create button that creates a message “Hello world” on it once clicked.
3.Provide participants a list of source in a column called Grade, ranging from 43 to 100, and ask participants to create button that populates column called P/F with p or f for pass or fail.
4.Provide participants a list of phone numbers, in the format of (XXX) XXX-XXX and ask participants to create a button that populate a column called area code with unique area code and their associated count in a column called unit. They collect data by developing Google chrome extension to monitor students searches and prepare them searches in a research survey. They reformulate those search which they found relevant to VBA  they compile them to make survey.


**RESULT:**

RQ1: why do subsequent leaner search?
Ans: leaner most frequently code and potential ways to resolve bugs or errors in their programme.

RQ2: what does a typical search  session entail?
Ans: Each query was followed by a 3 results click on average. An average participant spent about five minutes before reformulating a query. Learners generated more verbose query than professional did. (5.6 words vs 1.9 words) and required longer time to scanthe search results.

RQ3: what are the factors impact the success of search queries?
Ans: when looking for APIs or implementations, 71 to 106 (66.4%) searches were successful. In addition to consulting documentation and tutorials led to more successful searches than Q&A sites. Learners frequently borrowed terms from languages with which they are familiar when compositing queries, these queries were more successful on average than the typical query.

### **Conclusion**

In this research paper we studied how graduate students search when solving programming tasks in a new language. We find that subsequent programming language learners search with the purposes of exploring for example code, designing new features and understanding why code performs as it does. Learners composed more verbose queries, and required longer time to scan through the search result than professional developers did. Consulting colleagues/friends in person could improve the chance to solve a problem. Consulting documentation and tutorials is more indicative of success in a search than consulting Q&A sites. Queries that focus on how something works are more likely to succeed when being composed with the structure, “How to do... ”. Learns frequently borrowed terms from languages with which they are familiar when searching for examples in an unfamiliar language. The term borrowing queries were more likely to success than the typical query on average.
For future work, a replication study with a more diverse and larger set of subsequent programming language learners is suggested to better generalize how learners search. Techniques that can determine the relative APIs/libraries based on the context in the queries, provide query reformulation suggestions according to the search goals, map APIs between programming languages and present sample code are suggested to support more programming languages. Another suggestion for future work is to explore how to detect and correct the term mismatch in queries during the language migration.

