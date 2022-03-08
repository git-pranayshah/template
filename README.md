# Topic of the Template

Topic Brief Description

# Topic Landing Zone

Description of the Landing zone


## Target audience

Example:
- Infrastructure Architect
- Application Developer
-       IT Professional
-       Cloud Solution Architect

# Product/LZ architecture

The [Template.json](https://github.com/git-pranayshah/template/blob/master/template.json) Azure Resource Manager template will help you automatically deploy the diagram below, which includes:

example!!!

- A Virutal Network Gateway and a Public IP address.
- A Network Security Group with the necessary outbound rules for Azure Virtual Desktop Hostpools to properly activate and work.

![alt image](https://github.com/git-pranayshah/template/blob/master/images/Landing_Zone_Template.png)

[Template.json](https://github.com/git-pranayshah/template/blob/master/template.json) can be modified to match your current infrastructure needs.

## One Click Deploying Teamplate
<!-- Powershell command for Translating Git URL for template.json
    $url = "https://raw.githubusercontent.com/git-pranayshah/template/master/template.json"
    [uri]::EscapeDataString($url)
    >> uri = https%3A%2F%2Fraw.githubusercontent.com%2Fgit-pranayshah%2Ftemplate%2Fmaster%2Ftemplate.json

Base URL: https://portal.azure.com/#create/Microsoft.Template/uri
Final URL: <Base URL>/<uri>
-->
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgit-pranayshah%2Ftemplate%2Fmaster%2Ftemplate.json)


## Deploying an ARM Template using the Azure portal

- Visit https://portal.azure.com

Using the search bar on top type Templates

![alt image](https://github.com/git-pranayshah/template/blob/master/images/Search.png)

- Create a new template

![alt image](https://github.com/git-pranayshah/template/blob/master/images/create.png)

- Give a name and a description to the template

![alt image](https://github.com/git-pranayshah/template/blob/master/images/Name%20and%20Description.png)

- Add for modified [Template.json](https://github.com/git-pranayshah/template/blob/master/template.json) and save it

![alt image](https://github.com/git-pranayshah/template/blob/master/images/add%20code.png)

- Select the newly added template and click deploy

![alt image](https://github.com/git-pranayshah/template/blob/master/images/Select%20and%20deploy%20template.png)

- Fill out the blanks with your details and click purchase

![alt image](https://github.com/git-pranayshah/template/blob/master/images/Fill%20out%20the%20details%20and%20purchase.png)

- Allow 30 minutes for the deployment to complete
- Peer your Hub and Spoke Virtual Networks as needed

## Azure services and related products

example!!
- Azure Networking
- Security

## Related references
example!!
- https://docs.microsoft.com/en-us/azure/virtual-desktop/overview
- https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/
- https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-connect-virtual-networks-portal#peer-virtual-networks
- https://docs.microsoft.com/en-us/azure/virtual-desktop/safe-url-list#virtual-machines



