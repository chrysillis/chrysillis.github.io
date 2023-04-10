---
layout: post
author: chrysi
---
Speed up your infrastructure deployments using Terraform! I have put together some configs that will get you up and running in no time.


Using VM extensions, it's possible to run PowerShell commands or complete scripts after your VM is created in Azure. This allows for installing any server roles you may need or for installing software automatically such as your RMM agent for remote connectivity.

I have tested these configs to make sure they don't have any errors and can be deployed as-is. However, I recommend you edit the variables.tf file to suit your organization's needs.

GitHub Repository: [https://github.com/chrysillis/infra-code](https://github.com/chrysillis/infra-code)