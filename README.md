# Fundamentals of DevOps and Software Delivery — Code Examples

Personal code examples and hands-on exercises from *Fundamentals of DevOps and Software Delivery: A Hands-On Guide to Deploying and Managing Software in Production* by Yevgeniy (Jim) Brikman, published by O'Reilly Media.

---

## About This Repository

This repo serves as my personal reference and learning log as I work through Brikman's comprehensive guide to modern DevOps and software delivery. Rather than just reading, I worked through the examples so every meaningful configuration, and deployment script I encounter gets documented here.

---

## About the Book

*Fundamentals of DevOps and Software Delivery* is a hands-on guide to everything required to take application code and run it in production. It starts with a single server deployment and works all the way up to microservices running in a Kubernetes cluster with a full CI/CD pipeline, service mesh, and end-to-end encryption.

**Author:** Yevgeniy (Jim) Brikman, co-founder of Gruntwork and author of *Terraform: Up & Running*

---

## Skills Covered

Working through this book provides hands-on experience with the following:

**Cloud & Deployment**
- Deploying applications via PaaS (Render) and IaaS (AWS EC2)
- Running containerized workloads with Docker and Kubernetes
- Serverless deployments with AWS Lambda
- On-prem vs. cloud trade-off analysis

**Infrastructure as Code**
- Managing infrastructure with OpenTofu (open-source Terraform fork)
- Image building with Packer
- Configuration management with Ansible

**CI/CD Pipelines**
- Automating builds, tests, and deployments with GitHub Actions
- Structuring software delivery lifecycle automation
- Splitting codebases into environments, libraries, and microservices

**Networking**
- VPC design and configuration
- VPN setup
- DNS management and TLS certificate provisioning
- CDNs and service meshes

**Data & Observability**
- Setting up and managing data stores
- Backup strategies
- Hooking up monitoring and alerting for production systems

**Security**
- Network hardening fundamentals
- End-to-end encryption in microservice environments
- Security considerations across the delivery lifecycle

---

> **Note:** Chapter folders are added as I progress through the book. Not all chapters may be present yet.

---

## Why I'm Reading This

My career focus is on DevSecOps and cloud engineering — specifically targeting roles in defense contracting and fintech post-graduation. While my AWS and Terraform certs give me a strong theoretical foundation, this book fills in the practical gaps: how do real production systems actually get built, deployed, secured, and maintained.

This repo is part of how I build and demonstrate that practical knowledge.

---

## Tools & Technologies Featured

`AWS` `Docker` `Kubernetes` `OpenTofu` `Terraform` `Packer` `Ansible` `GitHub Actions` `Render` `Lambda` `VPC` `DNS` `TLS` `Bash` `Linux`

---

## Resources

- [Book on O'Reilly](https://www.oreilly.com/library/view/fundamentals-of-devops/9781098174583/)
- [Book on Amazon](https://www.amazon.com/dp/1098174593)
- [Gruntwork Blog Series (Free)](https://www.gruntwork.io/books/fundamentals-of-devops/fundamentals-of-devops)
- [Author's Website](https://www.ybrikman.com)

---

## Notes

All code in this repo is adapted from the book's examples for personal learning purposes. Credit for original examples goes to Yevgeniy Brikman and O'Reilly Media.