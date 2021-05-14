# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

For the CMS app, the App Service solution is cheaper than the VM. The F1 option in pricing tiers is free. 
The scalability and availability offer by App Service is enough for CMS app. Multiple VMs can be grouped to provide high availability, scalability, and redundancy, but impact on price of the solution. 
For developer, it is easier and faster to setup a App Service than a VM. 

For the CMS app, I choose App Service solution, because the App Service´s hard limitation is enough for this application,
the application language (Python) is supported by App Service, it is a cheaper solution and easier for developer than the VM.

### Assess app changes that would change your decision.

If there is a need for dedicated server for security reasons, Virtual Machine will be a better alternative.
If the hardware limitations become a problem, Virtual Machine can become the best option. 
If the requirements for scalability, availability and redundancy increased, Virtual Machine can become a better solution. 

