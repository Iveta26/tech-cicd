# Intro to Terraform

Terraform is an open-source infrastructure-as-code software tool created by HashiCorp. Users define and provide data center infrastructure using a declarative configuration language known as HashiCorp Configuration Language, or optionally JSON.

---

### Why Terraform?

**Improved collaboration:**
   
It allows teams to define and manage infrastructure using version control, which makes it easier for multiple people to collaborate and work on the same codebase. This can help improve collaboration and reduce the risk of errors.

**Version history:**
   
It automatically maintains a version history of your infrastructure, which makes it easy to roll back to previous versions if necessary. This can help protect against mistakes and ensure that you can recover from failures quickly.

**Consistency:**
   
It allows you to define your infrastructure using a high-level configuration language, which means that you can specify the desired state of your infrastructure in a consistent and predictable way.

**Reusability:**
   
It allows you to define infrastructure as modular components, which can be easily reused across multiple deployments. This can help reduce duplication and make it easier to manage your infrastructure at scale.

**Portable across cloud providers:**
   
It is portable across different cloud providers, which means that you can use the same tools and processes to manage your infrastructure regardless of where it is deployed.

---

### Who uses Terraform?

Around the world in 2023, over 27781 have started using Terraform as Configuration Management tool.

Some customers of Terraform include:
- Mercedes - Benz AG
- Samsung Electronics Co
- Booking.com
- Adobe, Inc.
---

### Installation on Windows

1. Install a package provided on Terraform website ([here](https://developer.hashicorp.com/terraform/downloads))
2. Create Path environmental variable on your machine. Add the path to your installed package. 
    ```Control Panel``` -> ```System``` -> ```System settings``` -> ```Environment Variables```

![Alt text](cicdImg/envVarWind.jpg)

3. Run ```terraform --version``` on your machine to test the installation

![Alt text](cicdImg/terraformVersion.jpg)
