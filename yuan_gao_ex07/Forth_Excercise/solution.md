##solution 

#a) Find out in what kind of applications MPI and OpenMP are used. Write a couple of lines
about your findings.

Answer:

My interest is on robot(affective and intellectual) learning algorithms and robot dynamic systems. As a consequence, I collected several OpenMP applications on related fields.

##1) Mobile robot parallel PF-SLAM based on OpenMP

The OpenMP library is used heavily for the high performance computing. The particle filter is an algorithm which simulates the sequancial monte carlo process. The computational tasks could be very complicated considering the number of particles in certian environment. The OpenMP library could speed up this process by calculating the partical probabilities parallelly.

##2) Hybrid MPI/OpenMP Parallel Linear Support Vector Machine Training

In the field of machine learning, there are numerous large-scale algorithms. The support vector machine is one of them. The OpenMP and MPI library can help this high-dimensional statistical model to get a flexible training time.

##3) Hybrid Parallelization of Maximum Likelihood Fitting with MPI and OpenMP

In a technique report of CERN, it was siad that the OpenMP was used for Maximum Likelihood Fitting problem. It is an other area of data analysis.


#b) Find out what are the largest (number of cores) supercomputers currently in the world.

Answer:

##1) Tianhe-2 
Tianhe has-2  in total 3,120,000 cores and it is largest and fastest computer in the world. However, the utilization of the processors is much lower than other super computers. 

##2) Titan 
Titan has 299,008 cores. It is now the second fastest coputer in the world.

##3) IBM Sequoia 
IBM Sequoia is the third fastest computer in the world. It has 705,024 cores. It has more cores than Titan, but it run a little bit slower due to other floating point computing devices.





