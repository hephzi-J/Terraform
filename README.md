# Terraform

**Terraform 003**
Local-execute or remote-execute
null_resorces inplace of terraform_data
terraform taint > **-replace** flag on **terraform plan**
terraform refresh > **-refresh-only** with **terraform plan**
remote-block > cloud-block 
terraform.lock.hcl
mark data "sensitive"
TF cloud new UI


**prerequisite**
  on-prem or cloud


**objectives**

 **1. understanding IaC Concepts**
     1.1 explain what IaC
     1.2 describe the advantage of IaC
     
 **2. understand the pupose of TF**
     2.1 explain Multi-cloud and provider-agnostic benefits
     2.2 explain the benefits of state
     
**3. understand the basics of TF**
     3.1 Install and version Terraform providers
     3.2 Describe plugin-based architecture
     3.3 Write Terraform configuration using multiple providers
     3.4 Describe how Terraform finds and fetches providers
     
**4. Use Terraform outside the core workflow**
   4.1 Describe when to use **terraform import** to import existing infrastructure into your Terraform state
   4.2 Use terraform state to view Terraform state
   4.3 Describe when to enable verbose logging and what the outcome/value is
   
**5. Interact with Terraform modules**
   5.1 Contrast and use different module source options including the public Terraform Registry
   5.2 Interact with module inputs and outputs
   5.3 Describe variable scope within modules/child modules
   5.4 Set module version
   
**6. Use the core Terraform workflow**
   6.1 Describe Terraform workflow ( Write -> Plan -> Create )
   6.2 Initialize a Terraform working directory (**terraform init**)
   6.3 Validate a Terraform configuration (**terraform validate**)
   6.4 Generate and review an execution plan for Terraform (**terraform plan**)
   6.5 Execute changes to infrastructure with Terraform (**terraform apply**)
   6.6 Destroy Terraform managed infrastructure (**terraform destroy**)
   6.7 Apply formatting and style adjustments to a configuration **(terraform fmt)**
   
**7. Implement and maintain state**
   7.1 Describe default **local** backend
   7.2 Describe state locking
   7.3 Handle backend and cloud integration authentication methods
   7.4 Differentiate remote state back end options
   7.5 Manage resource drift and Terraform state
   7.6 Describe **backend** block and cloud integration in configuration
   7.7 Understand secret management in state files
   
**8. Read, generate, and modify configuration**
   8.1 Demonstrate use of variables and outputs
   8.2 Describe secure secret injection best practice
   8.3 Understand the use of collection and structural types
   8.4 Create and differentiate **resource** and **data** configuration
   8.5 Use resource addressing and resource parameters to connect resources together
   8.6 Use HCL and Terraform functions to write configuration
   8.7 Describe built-in dependency management (order of execution based)
   
**9. Understand HCP Terraform capabilities**
   9.1 Explain how HCP Terraform helps to manage infrastructure
   9.2 Describe how HCP Terraform enables collaboration and governance 
   
   
   
