
# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.


### App Services
- Costs- cost is flexible , you can set amount of hardware allocated to host your application, and the cost varies based on the plan you choose.There are three different tiers - Dev/Test, Production, and Isolated. It is important to note that you’re always paying for the service plan, even if your services or application isn’t running.
- Scalability- with App Service there is auto scaling,which makes it friendly for scalability,there is both vertical and horizontal scaling.However, there are hardware limitations, such as a maximum of 14GB of memory and 4 vCPU cores per instance
- Availability- Azure App Service have a high availability,  although they support multiple languages(.NET, .NET Core, Java, Ruby, Node.js, PHP, or Python) they are limited to just using those languages.
- Workflow- Continuous deployment model using GitHub, Azure DevOps, or any Git repo.

### Virtual Machines
- Costs- Lower  up-front cost compared to purchasing and maintaining hardware.It is relatively more expensive when compared to Azure App Service
- Scalability- VMs have a high Scalibilty
- Availability- VMs also have a high availability,there is support for both Linux and Windows.
- Workflow- unlike Azure App Service, VMs are Labour intensive and can be more time consuming.
## Choose the appropriate solution (VM or App Service) for deploying the app
 #### Azure App Service

## Justify your choice 
  Some reasons that justified using Azure App Service are:
  1. Easy deployment from Github.
  2. It is a lightweight application and lightweight applications are better suited to App Services than VMs
  3. Since the ability to scale is not really a concern in this case, Azure App Service seemed perfect
  4. And lastly, Azure App Service cost less than Vms do.



## Assess app changes that would change your decision.

- If there is potential that the app will grow in resource needs and many more features are added or demand changes in a way that requires scaling then VMs wil be better suited to handle such scenerio.

- The level of control needed is also another factor to be considered as VMs allow you full access and control.

- A change in security requirement may also necessitate a chnage in decision as VMs  will be needed for dedicated servers for security reasons.


URL:https://udacity-egregius.azurewebsites.net/