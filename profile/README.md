What is digger
==========

Digger is an open source Terraform Cloud alternative. We allow you to manage your terraform runs directly in your CI/CD provider without compromising on security, scalability or usability of your runs. Everything runs within your CI provider and on your infrastructure so you don't need to trust your sensitive terraform state file with an external vendor.


![](https://raw.githubusercontent.com/diggerhq/.github/main/profile/0001banner.png)


The key features of digger are:

- **Managed state** Dedicated remote backend and lock table for every Terraform state file
- **Apply job queues** A Separate queue of terraform apply jobs for each .tfstate to avoid conflicts
- **Environments** Independent configurations for dev / staging / prod / you name it
- **Works with your CI** Secrets and cloud access never shared with any third party
- **Plan preview** See Terraform Plan right in your Github
