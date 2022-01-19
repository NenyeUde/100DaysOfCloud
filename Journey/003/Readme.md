
# Elastic Block Store -- EBS

## Introduction - What is EBS?

Amazon Elastic Block Store is a block storage system that is best used for storing persistent data, that is data that is infrequently accessed and less likely to be modified.
EBS are block-level storage device that are attached to your instances, it enables you to keep data persistently on a file system, even after you shut down your EC2 instance.
Think of them like a hard drive but for the cloud.


## Creating an EBS volume

I'll give a brief walkthrough of how to create an EBS volume and attach it to an EC2 instance.

### Step 1 — Launch an EC2 instance (if you do not have one already), if you have one you can use it 

![Screen![2022-01-19 09_43_44-Greenshot](https://user-images.githubusercontent.com/88492373/150218949-0f39335e-6855-4ce9-aa15-57b946d5f1f5.png)



### Step 2 — Now we want to create an EBS volume in this EC2, select your preferred instance and navigate to storage

![!![2022-01-19 22_48_39-Greenshot](https://user-images.githubusercontent.com/88492373/150219692-8b442909-10b4-477b-b6a9-d765428c6aad.png)


### Step 3 — Go ahead and crteate the volume! 

![Sc![2022-01-19 09_44_16-Greenshot](https://user-images.githubusercontent.com/88492373/150220144-cc7d676d-5285-4c7e-b084-0a9656eca9e2.png)


### Step 4 — Remember, it is important to select an availiablity zone for your EBS volume to be the same one where the EC2 instance you plan to attch the volume to was set at, select the preferred size for your volume 

![Sc![2022-01-19 09_47_06-Greenshot](https://user-images.githubusercontent.com/88492373/150220679-0d141dfb-5fa0-4fde-a9a4-b0a64a7501f3.png)


### Step 5 — That would be all! easy right? Now go ahead and create volume! (of course there are other things you might want to add or remove when creating your volume, depends on what you want really)

![![2022-01-19 09_47_27-Greenshot](https://user-images.githubusercontent.com/88492373/150221290-e22ca336-e926-4d7b-b698-8cff911249cf.png)


### Step 6 — Now you want to attach that volume to an EC2 instance. after creating the volume, right click, there is an option to attach volume 

![S![2022-01-19 09_49_39-Greenshot](https://user-images.githubusercontent.com/88492373/150222330-e0a42c64-57e0-4f9e-8b32-4a6474ef8126.png)


### Step 7 — We have just successfully created and EBS volume and attached it to an EC2 instance!! 

![S![2022-01-![2022-01-19 09_50_20-Greenshot](https://user-images.githubusercontent.com/88492373/150222595-5d9bcdf6-d462-4c4f-b7c2-27890361d1d2.png)


## ☁️ Cloud Outcome

EBS volumes have to be attached to instances in the same availability zones (AZ) as same them, if you created your volume in us-east-1a you cannot attach that volume to an instance created in us-east-1b. It simply would not work (well that is where snapshots come in but that's talk for another day). So be sure of the AZ of the instance you plan to attach your volume to before creating it. 


