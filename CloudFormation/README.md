# Task-1 

The [Task-1](https://github.com/PrajwalP7295/AWS/tree/main/CloudFormation/Task-1) dir contains the cloudformation yaml file to provision the following resources : 
- 1 VPC (Virtual Private Cloud) 
- 1 IGW (Internet Gateway) 
- 2 Subnets : 1 Public Subnet and 1 Private Subnet 
- Route Tables 
- Route Table Associations

# Task-2 

The [Task-2](https://github.com/PrajwalP7295/AWS/tree/main/CloudFormation/Task-2) dir contains the cloudformation yaml file to provision the following resources : 
- 1 EC2 instance 
- 1 RDS instance 

These resources use the previously created network infrastructure resources in Task-1.

# Task-3 

The [Task-3](https://github.com/PrajwalP7295/AWS/tree/main/CloudFormation/Task-3) dir contains the cloudformation yaml file to provision the following resources :
- 1 TG (Target Group)
- 1 ALB (Application Load Balancer)

These resources use the previously created resources' attributes in Task-1 and Task-2.

# Task-4

The [Task-4](https://github.com/PrajwalP7295/AWS/tree/main/CloudFormation/Task-4) dir contains the cloudformation yaml file to provision the following resources :
- 1 LT (Launch Template)
- 1 ASG (Auto-Scaling Group) : 
    - Min. capacity = Max. capacity = 1
    - Trigger based on "CPU Utilization" 
    
These resources use the previously created resources' attributes in Task-1, Task-2 and Task-3.