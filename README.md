# Cloud Adoption Framework in a day

## Lab Context 
Tailwind Traders is planning to migrate initial set of workloads from on-premises to cloud. They need a reference architecture to deploy and enforce resources, policies, and templates that will allow them to confidently get started with Azure. 

## Pre-requisites: 
Empty Azure Subscriptions with root level owner access  
 
## Exercise 1: Start Small and Expand Migrate Landing Zone 
  
In this exercise, you will create a blueprint definition based on CAF Migration Landing Zone, explore the capabilities it provides and assign it at the subscription level to get start started with Azure. Also, you will update the blueprint to match DMS Network architecture of Tailwind Traders. 
 

## Exercise 2: Governance  

Migrations have gone well. However, there are no strict governance established across the organization.  

Tailwind Traders need to establish recommended best practices for governance and a way to audit that no deployments have been made that bypass those rules. This audit needs to scale across the entire organization. 

Enable Resource Consistency 

Enable Security Baseline 

Enable Cost Management 
 
## Exercise 3: Enterprise Scale 

 The Enterprise-Scale architecture is modular by design and allow organizations to start with foundational landing zones that support their application portfolios, regardless of whether the applications are being migrated or are newly developed and deployed to Azure. The architecture enables organizations to start as small as needed and scale alongside their business requirements regardless of scale point. 
 
The Wing Tip company want to start with Landing Zones for their workload in Azure, where hybrid connectivity to their on-premise datacenter is not required from the start.  
 
In this exercise you will deploy the Management Group structure using ARM template and Policy Set definitions and also deploy the resources in the Enterprise scale landing zone

## Exercise 4: Azure Server Management Services 

In this exercise you will enable server management services like Onboard Update Management, Change Tracking, and Inventory solutions to Azure virtual machine 

- Create and update schedules 

- Use the Azure Policy Guest Configuration extension to audit the configuration settings in a virtual machine to verify that password security settings in Windows and Linux computers are set correctly 

- Enable Tracking and Alerting for Critical Changes 

- Set Alerts on file or registry changes in the VM 
