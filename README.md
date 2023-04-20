# Infrastructure-as-Code
Description for infrastructure as code \
https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac

https://github.com/arisyang1981/CloudFormation  

#On 4/20/203, compelted https://learn.acloud.guru/course/hashicorp-certified-terraform-associate-1/dashboard. First time.  
#4/20/2023, Terrsform associate certification.  
https://developer.hashicorp.com/terraform/tutorials/certification-003?ajs_aid=2c5829d6-f955-4dfe-898b-c70b1acab673&product_intent=terraform&utm_source=qualified  
#Study Guide  

#Learn about Infrastructure as Code (IaC)  
Tranditional Infra management vs IaC  
Trandition manage Infra via manual/GUI/customized scirpts: hard to track history, re-create, across-platform, inefficient elastic.  
https://www.hashicorp.com/resources/what-is-infrastructure-as-code  

#What is Terraform  
https://developer.hashicorp.com/terraform/intro  
Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.  
Question: How manage applications?  


Providers: public provider, and public registry  
Three stages of workflow: write, plan, apply
Configuration file  
state file  
backend file  
module: reusable Terraform configuration  
Terraform providers automatically calculate dependencies between resources to create or destroy them in the correct order.  

Scope - Identify the infrastructure for your project.  
Author - Write the configuration for your infrastructure.  
Initialize - Install the plugins Terraform needs to manage the infrastructure.  
Plan - Preview the changes Terraform will make to match your configuration.  
Apply - Make the planned changes.  
