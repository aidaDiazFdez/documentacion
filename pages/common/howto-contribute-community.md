---
title: "Contribute (Azure)"
sidebar: common
permalink: howto-contribute-community.html
---

## Purpose

The purpose of this document is to provide a guide to contribute to the development of EaC modules(Azure). If a module does not have any necessary features or updates here, you can find a way to contribute to it.

First of all, take a look to the HCF Frameworks (Security and Service Management)

[Security Controls for Public Cloud (formerly Security Control Framework)](https://confluence.alm.europe.cloudcenter.corp/display/ARCHSEC/Security+Controls+for+Public+Cloud)  

[Service Management Control Framework](https://santandernet.sharepoint.com/sites/PublicCloudPlatformAutomation/_layouts/15/Doc.aspx?OR=teams&action=edit&sourcedoc={34EFB2CF-8D4F-4D20-A533-9703001A656D})

Review and indentify the requirements indicated in both frameworks. Your changes must be according with these frameworks.

## Useful Links

### Modules source code location  
... 

### Modules Portfolio location  
[EaC - AZ Portfolio](eac-az-portfolio.html)  

## Create a New Module  
  
Steps Summary:  
1. Module Definition of Ready and module definition of done
2. Create the desired repository
3. Develop the code
4. Test the changes
5. Request the code upload  

### Definition of the Module  

Definition describes the Module and will be used to validate and Module certification.  
  
| Product Description | Template Parameters (including allowed ranges), Default parameter configuration values, target cloud model (Azure/AWS...) |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Acceptance Criteria | Acceptance criteria is a checklist that determine all the parameters of a module is completed and working, as 'done' all criteria must be fulfilled so that it is ensured that the module as planned and tested. |
| Target Security Control Framework|  Determine target Security Control Framework level that the control should target |
| Target Service Management Framework | Determine target Service Management Framework level that the control should target |
| Severity |  Severity of the request `Critical` or nothing if regular request |  

#### Product Description

The description of the product should include a high level overview about why the product is needed and how will the product be used. Include in
this description both Functional and Non-Functional Requirements (NFRs). Identify personas and describe the requirements using a use cases as
per the following samples.  

**Sample Personas**

| Persona | Description |
| --- | --- |
| Santander End User | End user of the service, has a corporate account and connects from the on-premises network or via vpn |
| Publi End User | End User of the service, might have a corporate account and connects from internet |
| Release Manager | Member of the development team with deployment permissions |
| Developer |  Member of the development team |  

**Sample Use Cases**

| Use Case | Description |
| --- | --- |
| UC-01 |  The Santander End User can connect to the web app via a public IP and can navigate resources stored in a backend on-prem database |
| UC-02 |  The Developer can connect to the Databricks Web UI to design and deploy spark routines |
| UC-03 | The Release Manager can remove a Windows App Service with WAF via Release Pipeline. All the Services provisioned during the deployment will be removed |  

#### Definition of Done (DoD)

| Product template & configuration scripts | The deployment template for the certified service and the following configuration scripts are created:<br>1. Provisioning script: Script that receives provisioning parameters and creates the service<br>2. Unprovisioning script: Script that completely removes the service from a subscription<br> |  
| Parameters file template |  The file with the template parameters for parametrizing the provisioning of the service |
| Product Documentation |  The following documentation must be created:<br>1. Readme.md with detailed information of the service<br>2. Architecture and Networking diagrams<br>3. Product catalog portfolio with the new product |<br>  

The Module must be compliant with the CCoE Standard Naming and Repo structure following the links below:<br>
must follow the best practice recomended in the section: [Modules - Blueprints](repo-modules_blueprints-naming-strategy.html)  

**Modules - Blueprints**  
* Terraform key Concepts
* Repo Modules/Blueprints Naming Strategy
* Before Create Your First Module/Blueprint
* Template Structure
* Unit & Integration Testing



### Sample diagrams

#### Architecture Diagram

{% include image.html file="AA6_DOR_DOD_Network_Diagram_1.png" %}


#### Network Diagram

{% include image.html file="AA6_DOR_DOD_Network_Diagram_2.png" %}


## Modify an Existing Module  
  
**Steps Summary**  
  
1. Create a Fork of the desired repository
2. Modify the code
3. Test the changes
4. Create a pull Request  

### How fork in GitHub UI  

Forking a repository is a simple two-step process.

* On GitHub, navigate to the repository.  
* In the top-right corner of the page, click Fork.  
  {% include image.html file="fork-button.png" %}
  
* select where the fork will be located  
  {% include image.html file="fork-located.png" %}  

* Now you have the repo forked in the selected destination  
  {% include image.html file="forked_repo.png" %}  
  
* Once you have the code available in your destination repo you can start to work as usual.  

  
### Modify the Module  
  
All the changes added must follow the best practice recomended in the section : [Modules - Blueprints](repo-modules_blueprints-naming-strategy.html)  
  
**Modules - Blueprints**  
* Terraform key Concepts
* Repo Modules/Blueprints Naming Strategy
* Before Create Your First Module/Blueprint
* Template Structure
* Unit & Integration Testing  
  
When the code was finished including the testing, your are in position to create a pull request, when we recieve the pull request we'll review the
code and if applied to the global requirements the code will be added to the module.  
  
### Merge Request from the Fork

* Navigate to the original repository you created your fork from.
  
* To the right of the Branch menu, click New pull request.  
  {% include image.html file="pull-request-start-review-button.png" %}  
  
* On the Compare page, click compare across forks.  
  {% include image.html file="compare-across-forks-link.png" %}  
  
* Confirm that the _base fork_ is the repository you'd like to merge changes into. Use the _base branch_ drop-down menu to select the branch of the upstream repository you'd like to merge changes into.  
  {% include image.html file="choose-base-fork-and-branch.png" %}  
  
* Use the _head fork_ drop-down menu to select your fork, then use the _compare branch_ drop-down menu to select the branch you made your changes in.  
  {% include image.html file="choose-head-fork-compare-branch.png" %}  
  
* Type a title and description for your pull request.  
  {% include image.html file="pullrequest-description.png" %}  
  
* If you do not want to allow anyone with push access to the upstream repository to make changes to your PR, unselect Allow edits from maintainers.  
  {% include image.html file="allow-maintainers-to-make-edits.png" %}  

* To create a pull request that is ready for review, click Create Pull Request. To create a draft pull request, use the drop-down and select Create Draft Pull Request, then click Draft Pull Request. For more information about draft pull requests, see ["About pull requests."](https://help.github.com/en/articles/about-pull-requests#draft-pull-requests)  
  {% include image.html file="pullrequest-send.png" %}   
  






