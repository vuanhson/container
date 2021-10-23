# What is container orchestration

Container orchestration simply refers to processes used to manage containers and to automate the management of containers

For example:
- I want to start up a set of five containers in production
  - I could spin up each container manually
  - Or, I could tell an orchestration tool like Kubernetes that I want five containers, and let the tool do it
- For the sake of redundancy, It's a good idea to spin up my five containers on five different hosts

The more complex my requirements for managing containers become the more useful my orchestration tools become

Zero downtime Deployment:
- In the old days, deployments went like this:
  - Take the server down for maintenance (it is unavailable to customers)
  - Perform the deployment
  - Bring the server backup
- A zero-downtime deployment (with containers) goes like this:
  - Spin up containers running the new code
  - When they are fully up, redirect user traffic to the new containers
  - Remove the old containers running the old code. No downtime for users!

How do you coordinate those steps quickly and efficiently? Orchestration tools can do it for you