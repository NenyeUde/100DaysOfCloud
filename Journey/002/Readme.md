
EC2 --

## EC2 - ELASTIC CLOUD COMPUTE 

EC2 is a virtual machine that represents a physical server for you to deploy your applications on AWS. EC2 terminates your need to invest in hardware, Instead of purchasing your own hardware and connecting it to a network, Amazon gives you nearly unlimited virtual machines to run your applications while they take care of the hardware. Amazon EC2 can be used to launch as many or as few virtual servers as you need, manage storage, configure security and networking.

## WHAT EC2 OFFERS

EC2 has some of the following features:

- INSTANCES : A virtual server in Amazon EC2 for running applications on AWS

- INSTANCE TYPES : Amazon EC2 provides a wide selection of instance types optimized to fit different use cases. Instance types comprise varying combinations of CPU, memory, storage, and networking capacity and gives flexibility to choose the appropriate mix of resources for your applications. Instance types are grouped as:

    i.   General purpose - General purpose instances are optimized to have a high number of CPU cores, on-demand storage and memory. 
 
    ii.  Compute Optimized - The Big Data guys. Compute optimized instances are used to run big data applications that require large amounts of processing power and memory on the AWS cloud.
 
    iii. Memory Optimized - Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory. They use a high-speed, solid-state drive to provide ultra-fast access to data and deliver high performance. These instances are classic for applications that need more memory and less CPU power.  
 
     iv.   Storage Optimized - Storage optimized instances are made for workloads that require high, sequential access to very large data sets on local storage.

- INSTANCE STORE VOLUMES - An instance store provides temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances, such as a load-balanced pool of web servers. Also, stores temporary data that's deleted when you stop, hibernate, or terminate your instance.

- EBS VOLUMES - This functions just like your physical hard drive. Persistent storage volumes for your data. EBS volumes can serve as primary storage for data that requires frequent updates.


## Use Case

-   If a user wanted to host their web servers or do some software development and testing, general purpose instance would be ideal.
-   If you are running any CPU-bound scale-out applications, you should look at compute-optimized instances first. Examples of such applications include web servers, video encoding, and high performance science and engineering applications like genome analysis or high-energy physics.



## ☁️ Cloud Outcome

It is very important to choose the right instance type for your application. 

