What is an instance

a vertual server for running applications on amazon's ec2. it can also be understood like a tiny part of a large computer, a tiny part which ash its own hard drive, network connection, OS, etc. But it is actually all virtual

in a system you can run different applications. Or many different applications. If they are all running individually without really having them involve each other. The instance is the virtual means of making that effect. 

Virtualization is the process of doing things in instances


EC2
Elastic Compute Cloud
elastic: resizeable and reuseable
Compute: carries out computation practice


cost effective, scalable, flexible


types of instances: 

general purpose instance: for apps that require balance of performance and cost. Need prompt response, cost effective, less processing
ex. email response system

compute instance: for apps that require a lot of processing from the CPU
ex. analysing streaming data. => data that continuously flows in and out

memory instances: for apps that require more memory/RAM. good computation power, but RAM resides in local system. So good memory capacity
ex. applciations that need multi tasking. Dashboard

storage instances: apps that require storing huge amounts of data. 

GPU instances: for apps that require heavy graphics rendering
ex. 3d modeling



Instance pricing models: 
on-demand: demand and get it. usually limited time frame
dedicated: privatized, secure, above and beyond. not shared w/ anyone
on spot: bidding
reserved: renting on lease for a longer period. ex. reserves for a year


Classifications of Instances

Burstable: category of gender purpose, starts w/ base power. 
EBS optimized: highest speed
Cluster Network:
Dedicated: 



use case
Edureka: let's assume using AWS and EC2
analysis of customer's data

auto response email system: would be served better by burstable performance

search engine and browsing: clustered network

confidential data processing: dedicated

