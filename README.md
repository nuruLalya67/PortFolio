# PortFolio

## ABOUT ME:

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/photo_2023-02-01_20-24-42.jpg" width="200" height="260"/>

hi there! i'm Nurul alya :wave:

  :woman_with_headscarf: My name is Nurul Alya Najeba Bt Shahrudin (270136)
 
   :woman_student: Universiti Utara Malaysia 
    
   :woman_student: Bachelor of Science with Honours (Decision Science) 
    
   :computer: Minor in Web Application
    
   :office: My course in School Of Quantitative Science(SQS) under College of Art and Science(CAS)

## MY EDUCATION:

 ### Sekolah Menengah Agama Al-Falah,Kemaman, Terengganu. ###
 
##### *Sijil Pelajaran Malaysia Result: 3A 2B 1C+ 2C 3D* #####

###### *01/2012 - 12/2016* ###### 

### Sekolah Menengah Kebangsaan Agama Durian Guling, Marang, Terengganu. ### 

##### *Sijil Tinggi Persekolahan Malaysia* #####

###### *04/2017 - 12/2018 Result: 2.67* ######

### Universiti Utara Malaysia, Sintok, Kedah. <br>

##### *Bachelor of Science with Honours Decision Science* #####  

###### *12/22 - Current CGPA: 3.4* ######

## RESEARCH DESCRIPTION:

### Introduction ###

Multi-Dimensional knapsack problem (MKP) is a continuation of a basic concept for 0-1 knapsack problem (KP). 0-1 Knapsack is a problem where a subset of n item packed into the knapsack of capacity where the objective is to minimize the total profit of the selected item without going over the knapsack capacity. On the other hand, the MKP is a set of items that must be assign into a knapsack with a certain number of dimensions having each a limited capacity. Each of the item has a profit and knapsack-related weight. The motivation of the MKP is to maximize the total profit of the selected items. 

### Problem Statement ###


             |SOLVING MULTIDIMENSIONAL KNAPSACK PROBLEM (MKP) BY USING SIMULATED ANNEALING WITH DIFFERENT RESTART TEMPERATURE|


Metaheuristic is found to be a reasonable method to solve MKP, such as SA. SA is one good metaheuristic method for solving MKP which can handle a large and unpredictable data. Nevertheless, SA is found to always possible to become stuck at local minima. Previous studies shows that a cooling schedule of SA plays important rules to reduce SA from being stuck at local minima. One of the approaches is to restart the temperature adaptively. However, previous studies are lacking in discussing on how to increase temperature. Hence, this study proposed SA with various restart temperature for solving MKP.

### Research Question ###

The research question for this study on solving MKP are:
1)	How to improve SA through different restart temperature in solving MKP?
2)	How efficient is the proposed different restart temperature in solving MKP?
	
### Research Objectives ###

The main objective of the study is to propose SA with different restart temperature in solving MKP. The sub-objectives of this study are: 

1)	To identify the suitable restart temperature for SA in solving MKP.
2)	To evaluate the performance of different restart temperature in SA to solving MKP.

### Research significant ###
 
The purpose of this study is to propose SA – Restart temperature using different restart temperature to solve MKP. The aim is to provide a better algorithm and performance solution of MKP. The proposed algorithm can be used to solve real application of MKP such as capital budgeting, cargo loading, resource allocation problem, container loading, stock cutting.

## LITERATURE REVIEW ##

Based on previous studies, there are various mechanism that use metaheuristics to solve MKP such as SA (Fubin and Rui, 2007), GA (Hill and Hiremath, 2005), hybrid approach (Hanafi et al, 2010). Zhou, et al. (2008) that depicts chaotic neural network combined with heuristic strategy. Mian (2012) present how to solve MKP by using a genetic algorithm and constraint handling technique by proposing three genetic algorithm. 

Besides that, some review on restart temperature for other domain,

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/gamPNG.PNG" width="950" height="260"/>



## RESEARCH METHODOLOGY ##

### Introduction ###

This chapter discusses the research methodology used in this study to solve MKP by improve SA using different restart temperature. It covers on the discussion of research design which is problem identification, model development, model validation and expected finding.

### Research Design ### 

The main objective of this study is to propose improvement of SA using different restart temperature to solve MKP. This study consists of three phases which are problem identification, model development and model validation. The first phase is problem identification to identify the research gap. In the second phase, the SA with different restart temperature will be developed to solve MKP. Lastly, the third phase is to validate the proposed SA with different restart temperature algorithm through experimentation with benchmark instances and comparison with other algorithms proposed in the literature. 

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/research%20framework.png" width="950" height="500"/>

Phase 1: Problem Identification

As elaborated in chapter 2, there are many researchers who have focused on solving MKP using metaheuristics. A metaheuristic is a high-level method that leads to a deeper, more problem-specific heuristic to improve its performance.  Some examples of metaheuristic approaches that have normally used by previous literature are such as ant colony optimization (Laabaai et al., 2018), genetic algorithm (Hill and Hiremath, 2005), TS (Dammeyer and Voss, 1993), SA (Fubin and Rui, 2007). Other than that, this example method not only solves MKP but also solves other domains. This study employed SA using different restart temperature to solve MKP. Based on previous studies, the researcher is concerned that there are lacking in discussing on how to increase the temperature using SA in solving MKP. A special about SA can handle large or unpredictable data. SA has been widely used to solve combinatorial optimization. It accepts the new solution when the objective value is lower than or equal to the current one. Thus, in this chapter we proposed SA with different restart temperature for solving MKP.

Phase 2: Model Development

This section explains on the development of SA with different restart temperature algorithm. Figure 4 presents Flow Chart for SA restart temperature.

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/flowchart%201.png" width="400" height="650"/>

Based on Figure 4, the flowchart starts with assigning initial parameter settings which involve starting temperature, ending temperature, temperature decrement, number of iterations at each temperature. It is followed by generating an initial solution and calculate objective function of the initial solution. Next, initial solution is set as best solution. After that, apply neighboorhood to get new solutions and calculate objective function of the new solution, If the new solution is equal or better than the current solution, then the new solution is selected to proceed to the next iteration. Restart the temperature using three different restart temperature whether linear increment, geometric or random number and update temperature. If the new solution is rejected, then random probability will be calculated to accept as worst solutions and set as current solutions. In this study, the temperature is restarted when the solution has improvement.

Phase 3: Model Validation

The SA-Restart temperature is proposed. The algorithm coded in JAVA using Netbeans version 8.2 run on Window 10 with 64-bit operating system and 8 GB RAM. The benchmark instances consists 270 MKPs. The problems were generated with three different item (n) sizes at 100, 250, and\ 500 variables. The constraints (m) were 5, 10, and\ \ 30 (each n with m consisted of 30 scenarios of different capacities and benefits). However, in this study we only consider 10 instances with size 100. The proposed solution were compared with the solution proposed in Chu and Beasley (1998) with the result retrieved from SA-Restart temperature with different restart temperature strategy. The objective of the problem sets is to maximize the total profit while considering multidimensional of capacity constraints. 


### DATA ANALYSIS & RESULT ###


This chapter discusses the findings generated from simulated annealing with different restart temperature models. The discussion starts with experimentation and parameter settings, followed by results and findings. The result generated from both models were compared with the benchmark data reported by Chu and Beasely (1998).

Result and Findings
This section presents the result generate from each SA-Restart temperature method with 10 times running and choose the maximum value among the best solutions and the smaller value for standard deviations for each dataset. 

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/flowchart%201.png" width="400" height="650"/>

From table 4.2, it shows the result linear increment generate from SA-Restart temperature Algorithm with α = 10, 50, 100 for 10 dataset from 10 time runs and is compared with the general SA in terms of average and standard deviations. The best solution with the maximum objective function for each dataset is highlighted in bold font while the best standard deviation is highlighted in orange colour. The highest value among best solutions for each dataset. After that, we calculated the average and standard deviations to know which alpha are more performed to used in linear increment. From the table linear increment  dataset 7 gets the highest value than other 10 dataset and general SA. For α=10 the higher value are 23342 with average 22078.8 and a standard deviations 744.63. Next, for α=50 are 22410 for the best solutions, 21672.5 for average and 461.27 and the Last is α=100, the best solution are, 22990, 21983.7 for average and 461.21 is for standard deviations. Based on the best solution, it is found that the restart temperature with α=100 is the best where it obtained four best solutions out of 10 instances, followed by the α= 50 with three best solutions out of 10 instances and finally, α=10 with three best solutions out of 10 instances. Next, based on standard deviation, it is found that the restart temperature with α=50 is the good standard deviation where it obtained four best standard deviation out of 10 instances, followed by the α= 100 with three best standard deviation out of 10 instances, the α=10 with two best standard deviation out of 10 instances and finally, the general SA with only one best standard deviations out of 10 instances. 

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/flowchart%201.png" width="400" height="650"/>

While, from table 4.3, it shows the result geometric restart temperature generate from SA-Restart temperature Algorithm with α = 2, 4, 5 for 10 dataset from 10 time runs and is compared with the general SA in terms of average and standard deviations. The best solution with the maximum objective function for each dataset is highlighted in bold font while the best standard deviation is highlighted in orange colour. Dataset 7 display the maximum value than other 10 dataset for three different alpha. But for general SA dataset 6 generated the higher value for best solutions which is 21772. For α=2 the best solution are 22695, with average 21738.9 and standard deviations 368.52. Besides, for α=4 the best solutions are 23132 with value for average 22105 and 512.90 for standard deviations. For the last alpha that researcher use is α=5 where the best solution 23379 and standard deviation is 529.21. Based on the best solution, it is found that the restart temperature with  α=5 is the best where it obtained five best solutions out of 10 instances, followed by the α= 2 with four best solutions out of 10 instances and finally, α=4 with one best solutions out of 10 instances.  Next, based on standard deviation, it is found that the restart temperature with α=5 is better standard deviation where it obtained five best standard deviation out of 10 instances, followed by the α= 4 with four best standard deviation out of 10 instances, and finally, the general SA with only one best standard deviations out of 10 instances. 

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/flowchart%201.png" width="400" height="650"/>

For table 4.4, it shows the result random number generate from SA-Restart temperature Algorithm for 10 dataset from 10 time runs and is compared with the general SA in terms of average and standard deviations. The best solution with the maximum objective function for each dataset is highlighted in bold font while the best standard deviation is highlighted in orange colour. The highest best solution is dataset 7 with value 22757 and the average 22221.5. Based on the best solution, it is found that the restart temperature with  random number is the best where it obtained seven best solutions out of 10 instances and general SA with three best solutions out of 10 instances. Based on standard deviation, it is found that the restart temperature with random number is better standard deviation where it obtained seven best standard deviation out of 10 instances and the general SA with three best standard deviations out of 10 instances.





### CONCLUSION ###

## RESEARCH PROGRESS:

                                    PROGRESS UPDATE PER WEEK, WEEK 1 - WEEK 14

WEEK 1

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week1.1.PNG" width="500" height="260"/>

* For the first week of this semester, I had meeting with my Supervisor(SV) through webex.

* Dr. give briefing about research 2 contents that needed to complete, findings in chapter 4,5 and, full report.

* Dr. introduced the dataset for MKP from OR-Libray and, formulate a mathematical model based on the dataset.

WEEK 2 

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week2.PNG" width="500" height="260"/>

* For week 2, all decision science's student attend our first programmed meeting. The talk is about conducting research subject. 
* In this talk, Dr. mention to create an e-portfilio and, explain its importants for our sub.
* Dr. also display all important date such report submission, presentation and so on.
  

WEEK 3

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%203.PNG" width="500" height="260"/>

* In the third week, research study start with finding a basic coding of Simulated Annealing (SA) to make improvement in solving MKP.
* I change our coding using basic SA that used to solve assignment problems for solving MKP.
* I start with generating initial solution randomly, continue with objective function, generate neighbor, temperature setting and so on.


WEEK 4

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%204.PNG" width="500" height="260"/>

* After finishing improving basic SA to solve MKP, I run the coding to see the results and there are no error message display, but, it have some error in calculations, and the results for calculated manually is not the same with output in NeatBeans. 
* Next, we find where the errors and try to fix the problems.   



WEEK 6  

* The algorithm has successfully run without error message. After that I started to improve the SA.

* Before I started improving algorithm, my Sv give task for me to find some techniques on how to restart the temperature, when to restat the temperature and, how to improve reheat. 
* From the task given, I managed to find some techniques on how to increase the restart temperature.  

WEEK 7

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%207.PNG" width="500" height="260"/>


* Disscussion with SV which technique are suitable, and decide to used linear increment, geometric and random number.

* I modified the algorithm to add formula for technique that we decided to do. 
 
* Formula for linear increasment is T=T+*alpha* , for geometric is T=T * *alpha* while for random number is T=T*10* random value.
 
* The algorithm are completely finish and the result and ouput is correct.  

WEEK 8 & 9 

* For this 2 weeks, I collect 10 dataset in OR-Library and convert to microsoft ecxel and NetBeans.

WEEK 10

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%2010.PNG" width="500" height="260"/>


* Then, I run each of dataset in NetBeans by using different restart temperature. 
* For the linear increment, I use 3 different value which is alpha=10, 50 and 100.
* For tthe geometric also use different value of alpha, alpha=2,4,5.
* Last is 

WEEK 11

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%2011.PNG" width="700" height="350"/>



WEEK 12

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/week11.PNG" width="500" height="260"/> <img src="https://github.com/nuruLalya67/PortFolio/blob/main/week%2011.2.PNG" width="500" height="260"/>

* This week I focus more about the content and design of the poster.  
* Besides that, I also show the poster to my SV of my works to get some advice and approval from madam. 


WEEK 13

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/WhatsApp%20Image%202023-02-05%20at%202.10.22%20AM.jpeg" width="300" height="500"/> <img src="https://github.com/nuruLalya67/PortFolio/blob/main/WhatsApp%20Image%202023-02-05%20at%201.49.26%20AM.jpeg" width="300" height="500"/> 

* For the final consultation on the model and poster, I presented to my supervisor, Dr. Syariza, my final poster before I print out them. 

* My SV advice me to illustrate the acceptence value through the iterations and add significant of study.

* I immediately prepared the poster to be present on tomorrow morning.

* My final poster it shown below:

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/RESEARCH.png" width="900" height="1100"/>




## DECISION SCIENCE SYMPOSIUM DAY ##

<img src="https://github.com/nuruLalya67/PortFolio/blob/main/WhatsApp%20Image%202023-02-05%20at%201.50.58%20AM.jpeg" width="400" height="700"/>  <img src="https://github.com/nuruLalya67/PortFolio/blob/main/WhatsApp%20Image%202023-02-05%20at%201.57.46%20AM.jpeg" width="500" height="260"/> 


Presentation went well and i can answer the question from my evaluator, Dr Nurul Naziha Hawari and Dr. Aida Benjaamin.
After the symposium day we need to go dewan seminar 2 for closing ceremony
All of participant, receive the participating certificate.
Participant that have a good and complete poster got the award gold, bronze and silver.


WEEK 14 

Lastly, the only task i had to do is complete the final research report and recheck again with my SV and Submit. 




