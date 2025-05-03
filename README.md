# Ansible Directory and File Creation Automation

## Introduction

This mini task showcases how to use **Ansible** to automate the creation of directories and files on multiple Linux systems. By utilizing Ansible playbooks, roles, and variable files, system administrators can ensure consistency and efficiency in infrastructure management.

This automation helps eliminate manual errors, speeds up deployments, and promotes Infrastructure as Code (IaC) practices.

---

## Objective

- Create specific files in `/opt/`
- Create specific directories in `/opt/` with full permissions
- Demonstrate Ansible role structure and reusability

---

## Tools Used

- **Ansible**
- **YAML** for configuration
- **Git** for version control
- **Linux** environment for deployment

---
<img width="757" alt="Screenshot 2025-05-03 at 00 05 56" src="https://github.com/user-attachments/assets/cae793ab-f498-4502-ae62-c1afaed5040a" />

---
## Conclusion

I successfully automated the creation of specific files and directories on remote nodes using Ansible. By leveraging a custom Ansible role (filemgt), I ensured consistent, repeatable provisioning of resources across multiple hosts. This approach reduces manual intervention, minimizes configuration errors, and simplifies infrastructure management.

This example showcases how powerful and efficient Ansible is for automating system-level tasks. It can be easily extended or modified to fit more complex automation scenarios in production environments.
