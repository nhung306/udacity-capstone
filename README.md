## Capstone
# Udacity Cloud DevOps Engineer: Project 05 - Capstone
This is final project of Udacity Cloud DevOps Engineer Nanodegree Program. 
In this project we'll apply the skills and knowledge that I've learn from the nanodegree, including:

- Working with AWS
- Using CircleCI to implement CI/CD
- Building pipelines
- Building Kubernetes clusters
- Building Docker containers in pipelines

# Application
This is a simple "Hello, World!" site deploy and hosted with Nodejs

# Deployment strategy
- I applied 'Rolling' deployment to this project
- Integrate Slack to send notification describe the result of the jobs
- Check to see whether the app is successfully running and rolled out
- Map custom domain to LoadBalancer DNS Name

# Steps
- Deploy app
- Setup the EKS cluster
- Linting the Dockerfile
- Build and push the image to dockerhub
- Deploy to Kubernete cluster
- Send notity to slack
- After deploy, using Curl to check if the app is up and running at port 80
- Finally, I check if the app successfully rolled out or not
