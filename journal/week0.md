# Week 0 — Billing and Architecture


This is my cloudwatch billing alert
![Screenshot 2023-02-18 at 15 16 45](https://user-images.githubusercontent.com/106006096/219873617-94c767d4-b2ba-40d7-8a6b-5ae719d4a9d9.png)


This is my Billing Budget 
![Screenshot 2023-02-18 at 15 16 00](https://user-images.githubusercontent.com/106006096/219874076-fe6f240c-bfde-47aa-a2e8-0849a2bc51b9.png)

This is my conceptual diagram 
![Screenshot 2023-02-18 at 15 28 27](https://user-images.githubusercontent.com/106006096/219874203-e892add5-6c7d-4e40-93c2-fa5d6283ee8a.png)

Logical diagram showing a pipeline where developers create a docker file and push it into the repocodebuild will access the newly commited dockerfile and use the build spec file to produce a docker image.Codeploy will use the built docker image to deploy the application on an ec2 which will be managed by ECS. Users will be able to access the application where traffuc will be routed to the application load balancer and on the instances

![Screenshot 2023-02-18 at 16 01 29](https://user-images.githubusercontent.com/106006096/219875829-8685f922-f23d-4cc7-8605-bf88b47a94a6.png)





