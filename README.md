# AWS-EC2-Instance-for-R-Studio
Lets understand how to create and launch a EC2 Instance for R-Studio on AWS.
--

## Step 1:
Create a account on AWS with your credit card. 


## Step 2:
Once your account is created, login to the amazon platform and go to the services tab. 
Here, you can select the VPC service to create your own VPC which is the first step towards initialising your EC2 instance on AWS.


## Step 3:

### VPC Creation
* Click on 'Your VPCs'
* Select *Create VPC*
* You will see the below window after clicking the *Create VPC* tab

![VPC_creation](https://user-images.githubusercontent.com/39962972/70740041-8a018f00-1d18-11ea-87a6-511b1a8c1f8a.png)

Follow the instructions onscreen and set CIDR block to 10.0.0.0/16

* Click on *Create*


## Step 4:

### Subnet Creation
* Click on *Subnets* tab present on the pane in the left handside
* You will see the below window

![subnet1](https://user-images.githubusercontent.com/39962972/70742002-e6ff4400-1d1c-11ea-98a0-7ee876bc8c47.png)

* Click on *Create Subnet*, you will see the window below

![subnet2](https://user-images.githubusercontent.com/39962972/70742884-dc45ae80-1d1e-11ea-8ae8-30a028197315.png)

* Create a subnet. Attach it to the VPC you just created, and set the CIDR block to 10.0.0.0/20


## Step 4:



