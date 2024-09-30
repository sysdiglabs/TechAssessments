# Solutions Architect Technical Assessment (Cloud & Ecosystem) 2024

We recommend reviewing the [Sysdig Assessment Principles](https://github.com/sysdiglabs/TechAssessments) before starting.

## The Project

We’d like to understand your skills and how we can best support your success. 

**If you don’t have time to complete all the steps, it’s sufficient to describe how you would implement them and address the various challenges.**

**Note:** It is OK to Google or AI during the process, but keep in mind that many details may be overlooked if you don’t take some time to check the workflows manually.

### Prerequisites

* AWS Account (Please use free tiers or free credits options out there). If you can't use a real cloud account, you can skip the AWS part and work with a vanilla Kubernetes cluster locally.
* Sysdig Account (You should have received a trial account attached to this assessment). 

### Task Overview

1. **EKS Cluster Setup:** 
   - Create an EKS cluster using Terraform or CloudFormation.
   - Specs: 4 CPUs, 8GB RAM (enough to run a full set of Sysdig agents).
   - Please take care about billing alerts to avoid generating costs.
   - Turn off or scale down your cluster when you're not using it, but don't destroy it!

2. **Cloud Security:**
   - Secure the cluster with an agent-based method, and the cloud account using an agent-less method. To onboard Sysdig, you can use the *Getting Started* guide in the Sysdig UI and refer to Sysdig's official documentation.

3. **Deploy App(s):**
   - Deploy some test applications in the cluster. Some ideas are: [Voting App](https://github.com/dockersamples/example-voting-app) and/or [Juice Shop](https://github.com/juice-shop/juice-shop).  

4. **Explore Sysdig Features:**
   - Enable some runtime policies and generate any events (Example: "Terminal Shell in a container")
   - Review activity audit (Why is this important?).
   - Review posture management, what is failing and what is met.
   - Investigate runtime vulnerability management: Identify top vulnerabilities and explain why.
   - Can you provide a high level overview on how events are captured at different levels? (containers, and Cloudtrail).
   - What are captures? What is inside?

5. **Automations:**
   - Explain how to send runtime findings from the "Sysdig Runtime Threat Detection" policy to a third-party tool.
   - If you had to secure your GitHub Actions pipeline, describe how to automate the image scanning in your GitHub pipeline.
   - Outline an automation that pulls vulnerability data from an image every 24 hours.

6. **Cluster Review:**
   - Do not destroy your cluster. We will review it together.
   - Show off your namespaces and logs.

## Feedback
- How can we improve the process?
- How does Sysdig compare to other solutions you’ve used?
- What changes would you suggest for this assessment?
