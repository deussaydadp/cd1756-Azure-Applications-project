# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
VMs can be more expensive than App Services since there's additional management suchs as VM,monitoring,etc while App Services are structured in terms of tier-based pricing of resources.
Scalability
VMs are manually configured for scaling but offers flexibility while in App Services there is a built in scaling based on CPU usage, etc. Much easier to manage in terms of scaling operations.
Availability
VMs requires setting up the backup and recovery solutions while in App Services there's a built in back up and load balancer. I find App Services easy to manage in terms of Disaster recovery than VM.
Workflow
VMS is more complex in deployment process and customization while in App Services is a simpler to deploy but limited to customization.

I chose the App Services to use in this project due to straightforward manner of configuration of the Web App. In terms of this project deliverable App Service is suitable due to simplicity of the requirement.

### Assess app changes that would change your decision.

Switching between the two may depend on the complexity of the need of the business. I find App Services easier to manage and less resources are needed.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
