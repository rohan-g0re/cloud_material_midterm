D.1 What is live VM migration? Describe the process through “iterative copy” with an 
illustration? Why shared storage between source and destination VM is required for live 
migration?  
D.2 What is the benefit of a private cloud? Provide three reasons why Enterprises are adopting 
this even though they need to invest in the infrastructure. How does Hybrid cloud help? 
D.3 What is the key difference between Full and Para virtualization?  
D.4 What is the benefit of serverless architecture? Why is it scalable?  
D5. What is the role of a message queue system like Kafka/Kinesis/SQS in the overall design of a 
system?


*******


 D.1 What is a hybrid cloud? Explain through examples/use cases when it is 
beneficial over a solely public cloud and/or a private cloud. In other words, 
when and why one would benefit from hybrid cloud. 
D.2 Explain the difference between full and para virtualization. What are the 
pros and cons in each of these Why are all modern hypervisors are para 
virtualization? 
D.3 What is the role of a message queue like SQS in a cloud based system? 
Give an example to show with and without SQS what would be the 
comparative benefit with SQS. 
D.4 We have discussed about Virtualization, Container and Serverless (Lambda in AWS) compute
 model. Illustrate through an example when you would use one over the other and their relative 
benefits and drawbacks. 
D.5 Why is iterative copy needed to facilitate Live migration with virtualization?



******


C.1 What is a hybrid cloud? Explain through examples/use cases when it is beneficial 
over a solely public cloud and/or a private cloud. In other words, when and why one 
would benefit from hybrid cloud.  
C.2 What is the role of a message queue like SQS in a cloud based system? Give an 
example to show with and without SQS what would be the comparative benefit with 
SQS.  
C.3 We have discussed about Virtualization, Container and Serverless (Lambda in AWS) 
compute model. Illustrate through an example when you would use one over the other and 
their relative benefits and drawbacks.  
C.4 Describe how you may implement an AWS Lambda like serverless capability using 
container.  
C.5 Construct a cloud devops pipeline leveraging appropriate AWS services. Your design should 
assume that your code repo is in GitHub and target environment is deployment of set of micro 
services using AWS container service. Illustrate through appropriate diagram and illustration. 



******

D.1 What is live VM migration? Describe the process through “iterative copy” with an 
illustration? Why shared storage between source and destination VM is required for live 
migration?  
D.2 What is the benefit of a private cloud? Provide three reasons why Enterprises are adopting 
this even though they need to invest in the infrastructure. How does Hybrid cloud help?  
D.3 What is the key difference between Full and Para virtualization? D.4 What is the benefit of 
serverless architecture? Why is it scalable?  
D5. What is the role of a message queue system like Kafka/Kinesis/SQS in the overall design of a 
system? 



*****


 1. Why is hybrid cloud beneficial for an enterprise compared to either public or private cloud?
 2. What is paravirtualization and why is paravirtualization more efficient than full virtualization?
 3. Explain how iterative memory copy is leveraged for live migration?
 4. What are the key differences between VM and containers?
 

******



 1. Howdoes the trade-off between memory space and false positives influence the design
 of Bloom filters in large databases, and how might this impact overall database
 performance?
 2. Explain the key difference between Full Virtualization, and Para Virtualization and state
 the pros-cons of each.
 3. Imagine you are developing a containerized application where user-uploaded files need
 to be persistently stored across container restarts. How would you use Docker volumes
 to achieve this, and provide a small Docker Compose template illustrating this.
 4. You built a docker image where the dockerfile looks like follows:
	Docker image 1 —----------------------------------
		 1) COPY./Assignment ./src
		 2) RUNcd./src
		 3) RUN“some build operation” —----> point 1
	Docker image 2 —----------------------------------
			 1) COPY./Assignment ./src
			 2) RUNcd./src
			 3) RUN“some build operation”
			4) RUN“rm-rf ./src”
			 5) RUN“ls” —---------> point 2
 What do you think about the image size of docker image 1 and docker image 2, which
 one will be greater ? Explain your answer
 

*******


 1. Explain Master-Slave Architecture as discussed in Lecture 1 and its issues concerning
 database replication
 2. Describe the live migration process and how it enables the seamless movement of
 virtual machines between physical hosts without service interruption and how it differs
 from traditional offline migration methods.
 3. Explain how Kubernetes achieves high availability and fault tolerance in a cluster. What
 components and mechanisms are used to ensure that applications running in
 Kubernetes remain available in the event of node failures?
 4. Howdoes hybrid cloud work and what are its challenges?
 5. Explain etcd, Persistent Volume, Persistent Volume Claim, and statefulsets in
 Kubernetes.
 
 

*******


1. Explain the differences between the three primary cloud service models—Infrastructure as a 
Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS) and provide 3 
points for each and two example products for each 
2. Your company is deciding between serverless (AWS Lambda) and containerized (ECS/EKS) 
architectures for a high-traffic web application.Explain: 
? The key differences in scalability, cold start latency between serverless functions and 
containers. 
? A scenario where serverless would be the better choice, and another where containers 
would be preferable. 
3. In a distributed system with unpredictable traffic, how does a message queue system like SQS 
improve resilience and scalability? 
Explain: 
? How message queues prevent system overload and failures. 
? How they enable scalability across microservices. 
? A real-world use case demonstrating these benefits. 
4. What is the use of Secondary Indexes in DynamoDB tables? List and explain the different types 
of secondary indexes available in AWS DynamoDB. 