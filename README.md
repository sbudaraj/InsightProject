# InsightProject

Project Idea:

DOS: DevOps as Service - Continuous delivery & deployment for the gig economy


What is the problem:

Many of us have great ideas that do not translate to a product because we do not have time, skills or resources to build the solution. On the other hand there are many ambitious high school and college students with strong technical skills that are looking for real world experience applying their skills.  

Poposed Solution at high level:

My propoasl will have a  way to take project definition (business idea) and translate it into  feature list of chunk sized development tasks. These will then be picked by a small group of developers (vetted* HS/college students) that will work off of a predefined SW architecture on presetup docker container so they can be effective on day 1.  We will build a weekly deployment cadence based on SCM principles. GitHub feature code check ins will trigger Jenkins pipeline. Finalized main line will be deployed in a Canary or blue/green model using Kubernetes.

First project definition/use case will be using an existing codebase for a freecycle app built on Nginx/Flask/Python/Postgres stack.

Technologies that will be used:

Kubernetes, Docker, Jenkins and Terraform.


Link to updated project PPT:

https://docs.google.com/presentation/d/1ZgWNUfB3gbNdWpo3BbH02VOmguaHRF6ltfRn45Gk70c/edit#slide=id.g35f391192_00

Links to different source files for project:

Kubernetes Canary Deployment Setup: https://github.com/sbudaraj/k8canary

Auto build to EC2 using Jenkins GitHub Webhook: https://github.com/sbudaraj/jenkinstest

Initial Terraform files to get AWS Infra setup: https://github.com/sbudaraj/InsightProjectInfra
