# The Nurse Rostering Problem during lack of nurses


The spread of COVID-19 is requiring an unprecedented effort by healthcare facilities to assist patients with critical conditions. The healthcare system in the North of Italy is collapsing and many other centers might end up in similar conditions very soon. The steep increase of patients with critical conditions who need particular care is difficult to be satisfied by the medical staff. Resources are limited and hospitals are not ready to deal with a similar pandemic scenario. While machines such as ventilators can be purchased or built, an even more scarce resource is represented by physicians and nurses able to take care of infected patients. Besides, the lack of sufficient protective equipment to keep them safe is causing healthcare personnel to get sick while taking care of infected patients. Those who are infected must stay away from work for at least 14 days, depleting the already exhausted workforce. According to the International Council of Nurses, up to the 20th of March, healthcare workers made up 9\% of Italy’s COVID-19 cases.  In order to take care of all the infected patients, more and more often __nurses are asked to work overtime__.

The __Nurse Rostering Problem__ (NRP), also called Nurse Scheduling Problem (NSP), is the problem of assigning nurses to shifts so to satisfy some constraints such as guaranteeing the minimum level of assistance required to patients while optimizing an objective function such as the overall number of hours worked by each nurse. However, standard scheduling formulations are not thought to consider the possibility for nurses to work overtime since it is out of the scope of scheduling in ordinary scenarios.


## Scope of the repository
This repository has the scope to provide healthcare facilities with a flexible and easy-to-adopt scheduling tool that, by taking into account the possibility for nurses to work overtime, will __help them in dealing with the NRP problem by balancing the workload required to each worker while trying to satisfy shift and ward's constraint as much as possible__. This work represents a general framework to include overtime shifts within standard NRP formulations and many other complexities can be included which are not extensively treated here for the sake of clearness.


## Files in the repository

The repository is made up of the following files:
- _Scheduling-nurses-shifts.pdf_: scientific report where the problem is introduced, different formulations are described and some numerical results are shown (to read it you must download the repository)
- _Nurses shifts - Version 1.ipynb_: notebook where we define the basic scheduling problem under normal conditions which will be used as a basis for extending the model to the overtime shifts scenario
- _Nurses shifts - Version 2.ipynb_: we include in the previous model the possibility that the number of nurses is not enough to guarantee the minimum level of assistance 
- _Nurses shifts - Version 3.ipynb_: further modification of the scheduling problem where we introduce the possibility for nurses to work more than one shift per day

Note that the jupyter files are written by leveraging open source libraries with the exception of the optimization routine, which is implemented thoguh the IBM Decision Optimization _docplex_ APIs, using IBM ILOG CPLEX 12.9. Docplex has a free version wihch however cannot solve problems with more than 500 variables. For free version, have a look at the [IBM academic initiative](https://developer.ibm.com/docloud/blog/2019/07/04/cplex-optimization-studio-for-students-and-academics/)

## Contacts
This repository borns from my feeling to help somehow during this difficult situation. Here I reported only some of the possibilities we can address for improving nurses' scheduling. If you are interested in the topic, if you would like to implement it somewhere and/or add some modifications to the formulation, do not hesitate to get in contact with me.
