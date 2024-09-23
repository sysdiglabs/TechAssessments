# Solutions Architect Technical Assessment (Cloud & Ecosystem) 2024

We strongly recommend reviewing the [Sysdig Assessment Principles](https://github.com/sysdiglabs/TechAssessments) before proceeding.

## The Project

We’d like to understand your skills and how we can best support your success. **Note:** It’s OK to use Google or AI tools during this assessment. Just be honest with yourself and communicate if you need more time.

### Task Overview

1. **EKS Cluster Setup:** (Please use free layers or free credit options out there).
   - Create an EKS cluster using Terraform or CloudFormation.
   - Specs: 4 CPUs, 8GB RAM (enough to run the Sysdig agent).
   - Please take care about billing alerts to avoid generating costs.
   - Turn off or scale down your cluster when you're not using it, but don't destroy it!

2. **Sysdig Platform Trial:**
   - Use the Sysdig account attached with this assessment

3. **Cluster Security:**
   - Secure the cluster and cloud account with both agent-based and agentless methods.
   - You can use the Sysdig’s *Getting Started* guide as well as Sysdig official documentation.

4. **Deploy Voting App:**
   - Use Helm to install the [voting app](https://github.com/dockersamples/example-voting-app) into your Kubernetes cluster.

5. **Explore Sysdig Features:**
   - Enable runtime policies and generate any secure events (Example: "Terminal Shell in a container")
   - Review activity audit (Why is this important?).
   - Review posture management, what is failing and what is met.
   - Investigate runtime vulnerability management: Identify top vulnerabilities and explain why.
   - Can you explain at high level how events are captured at different levels? (containers, and Cloudtrail).
   - What are captures? How they are taken? What is inside?

6. **Automations for DevSecOps:**
   - Explain how to send runtime findings from a policy to a third-party tool.
   - Describe how to automate image scanning in GitHub Actions.
   - Outline an automation that pulls vulnerability data from an image every 24 hours.

7. **Cluster Review:**
   - Do not destroy your cluster. We will review it together.
   - Show off your namespaces and logs.

## Feedback
- How can we improve the process?
- How does Sysdig compare to other solutions you’ve used?
- What changes would you suggest for this assessment?
