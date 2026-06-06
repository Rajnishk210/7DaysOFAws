# Days01 Practice Topic

## Compute
1. Amazon EC2
2. AWS Batch
3. AWS Elastic Beanstalk
4. AWS Lambda
5. AWS SAR
6. AWS Fargate
## Amazon EC2
### What is AWS EC2?
* EC2 stands for Elastic Compute Cloud.
* Amazon EC2 provide scalable could computing capacity in the AWS cloud.
* We can Use Amazon EC2 to lounch as many or as few virtual servers as we need, configure security group and neetworking and manage storage.
* In EC2 we can scale up and scale down the instaces.
* In EC2 having two storage option EBS and instance storage.
* A new AWS account usually gets a default EC2 On-Demand quota of 5 vCPUs per Region, so the number of instances depends on the instance type being lounched.
### Types of EC2 instances:

1. General purpose
2. Compute optimized
3. Memory Optimized
4. Storage optimized
5. Accelerated computing or GPU
 

1. General purpose: General pupose instances provide a balanced combination of compute, memory and networking resources and can be userd for vaiety of workloads.

Two types of genral purpose instances: T and M
* T- t2, t3, t4g
* M- M5, M6i,M7g

2. Compute optimized: Compute optimized instances design for that require high CPU performance.
* C5,C6i,C7g

3. Memory Optimized: Memory Optimized designed for workload that require large amounts of RAM to process data quickly.
* R5, R6i, R7g, X2idn

4. Storage Optimized: Storage Optimized instances are design for workload that require High speed access tolarge amount of data store localy in a disk.
* I3, I4i, D3, D3en

5. Accelrated Computing Instances: Accelerated Computing instances use specialized hardware accelerators such as GPUs, FPGAs, or AI chips to perform tasks much faster than a standard CPU.
* P- Series: P4d, P5
* G-Series: G4dn, G5
* FPGA(F-series) - F1
FPGA- field programmable gate array


## EC2 Instance Pricing Models


O-R-S-S-D-D

O → On-Demand
R → Reserved
S → Savings Plans
S → Spot
D → Dedicated Instances
D → Dedicated Hosts

1. On-Demand Pricing models:

* AWS EC2 offers six primary pricing models: On-Demand, Reserved Instances, Savings Plans, Spot Instances, Dedicated Instances, and Dedicated Hosts. On-Demand provides flexibility, Reserved Instances and Savings Plans offer discounted long-term pricing, Spot Instances use spare AWS capacity at very low cost, and Dedicated options provide hardware isolation for compliance and licensing requirements.


### Which EC2 pricing option is the cheapest?

Spot Instances are typically the cheapest, offering discounts of up to about 90% compared to On-Demand pricing, but they can be interrupted by AWS.

### Which pricing option is best for production workloads?

Reserved Instances or Savings Plans, because they provide significant cost savings for long-term, predictable usage.

### Which pricing option is best for Dev/Test?

On-Demand Instances, because they require no commitment and are easy to start and stop.
