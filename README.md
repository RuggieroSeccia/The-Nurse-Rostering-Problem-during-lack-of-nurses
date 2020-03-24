# Scheduling-nurses-shifts

The spread of COVID-19 is requiring an unpredictable effort by healthcare facilities to assist serious patients in recovering. The healthcare system in the North of Italy is collapsing and many other centers might end up in similar conditions very soon. The steep increase of serious patients who need particular care is difficult to be satisfied by the medical staff. Resources are limited and hospitals are not ready to deal with a similar pandemic scenario. While machines such as ventilators can be purchased (assumed their availability), the resource more scarce is represented by highly skilled personnel such as doctors and nurses able to take care of infected patients. In this optic, Operations Research comes to the rescue by offering automated systems for scheduling nurses' shifts. 

This repository has the scope to provide healthcare facilities with some simple mathematical formulations for scheduling the nurses' shifts within a department so to __improve efficiency and reduce stress for the healthcare personnel__.


If you are interested in the topic, if you would like to implement it somewhere and/or add some modifications to the problem, do not hesitate to get in contact with me.


The repository is made up of the following files:
- _Scheduling-nurses-shifts.pdf_: PDF file where the problem is introduced, different formulations are described and some numerical results are shown, as a scientific work
- _Nurses shifts - Version 1.ipynb_: notebook where the first, simple, mathematical model is introduced and defined
- _Nurses shifts - Version 2.ipynb_: modification of the mathematical model
- _Nurses shifts - Version 2.ipynb_: further modification of the mathematical model

Note that the jupyter files are written by leveraging open source libraries with the exception of the optimization routine, which is implemented thoguh the IBM Decision Optimization _docplex_ APIs, using IBM ILOG CPLEX 12.9. Docplex has a free version wihch however cannot solve problems with more than 500 variables. For the full version of docplex, have a look at the [IBM academic initiative](https://developer.ibm.com/docloud/blog/2019/07/04/cplex-optimization-studio-for-students-and-academics/)