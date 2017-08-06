# asg-scale-up-down-stack-02
Stack Name: "asg-scale-up-down-stack-02"
Create an AutoScale Group (name: "quad-test-asg-02") in the Default VPC of us-east-1 region
The ASG should span across two availability zones
Minimum Size: 1, Maximum Size: 5, Desired Size: 3
This ASG should scale up by one instance if the Average CPU Utilization goes beyond 80% for at least 2 minutes
This ASG should scale down by one instance if the Average CPU Utilization goes below 40% for at least 5 minutes
