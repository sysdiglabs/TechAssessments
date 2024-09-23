# Strategic Partners Solutions Architect TechAssessment (AWS) 2022

We Strongly recommend reading and understand the [Sysdig assessments general principles](https://github.com/sysdiglabs/TechAssessments) before continuing.

# The Project

To get a handle on who you are, what your drive is, and how we can best support your success we have a few asks.  **Disclaimer**, we live in the age of Google, and that's OK! It's totally fine to look things up as you go. Get as far as you can, and be honest with yourself about your time. We're happy to give you more if you need it, just communicate with us when you're ready!  

At a high level, we'd like you to attempt the following

1. Create an EKS cluster and secure it with Sysdig usint a GitOps approach with Terraform or CloudFormation. Lots of free 'credit' options out there.
    - (Note: A node with 4cpu and 8 gigs of ram should be fine to run the Sysdig agent on)
    - If you're building in the cloud, and you're new to the cloud, learn about security and billing alerts!
    - Turn off or scale down your cluster when you're not using it, but don't destroy it!
2. Signup for a Sysdig Platform Trial (https://sysdig.com/company/free-trial-platform/).
3. Install the Sysdig Agent(s) and Sysdig Cloud using the *Getting Started* interface. 
4. Install the classic *voting app* into your K8s cluster (https://github.com/dockersamples/example-voting-app)
5. Get Creative and build some stuff in Sysdig. 
    - Enable Runtime Policies, generate some noise (how might you do that?)
    - Activity audit! Why's that valuable?
    - Posture? What's up with those?
    - Vulnerability Management, secure images before they are deployed.
6. Design and describe how to resolve the following use-cases prioritizing the usage of AWS services.
    - We want to retain events up to 6 months, how could we accomplish that?
    - Our DevSecOps team wants to receive critical events in a 3rd party tool which exposes a REST API.
7. Don't destroy your cluster! We'd like to look at it with you.
    - Hit some buttons and nav around things
    - Show off your namespaces
    - Pull some logs

# Feedback?  
- How can we get better?  
- How did you experience with Sysdig differ from your experience of any other similar solutions?  
- What suggestions do you have on this process?  
- What tasks could be different or better?  
