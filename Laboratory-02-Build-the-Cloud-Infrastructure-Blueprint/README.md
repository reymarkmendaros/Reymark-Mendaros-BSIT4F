
# Laboratory 02 – Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focused on investigating a Linux-based cloud environment and understanding the basic components of cloud infrastructure. Using KillerCoda, the Linux environment was examined to identify its operating system, kernel, CPU, RAM, storage, mounted file systems, hostname, and IP addresses. The findings were then documented and related to cloud computing concepts.

## Objectives

- Investigate a Linux-based cloud environment using terminal commands.
- Identify compute, storage, networking, and operating system resources.
- Document the technical specifications of the Linux environment.
- Compare equivalent infrastructure services from AWS, Microsoft Azure, and Google Cloud Platform.
- Design a simple cloud infrastructure architecture.
- Practice technical documentation using Markdown and GitHub.
- Improve cloud computing and Linux administration skills.

## Cloud Infrastructure Components

### Compute Resources

The KillerCoda environment provides an Intel Xeon E312xx processor with 1 CPU core. The CPU provides the processing power required to execute commands and run applications.

### Storage Resources

The main storage resource is `/dev/vda1`, which has a total capacity of 19G. Other mounted file systems include `/boot` and `/boot/efi`.

### Networking Resources

The Linux environment has two identified IP addresses: `172.30.1.2` and `172.17.0.1`. These addresses allow the virtual environment to communicate with other network resources.

### Operating System

The environment uses Ubuntu 24.04.4 LTS (Noble Numbat) with Linux kernel version `6.8.0-136-generic`.

## Tools Used

- GitHub – Repository and project documentation
- KillerCoda – Cloud/Linux practice environment
- Linux Terminal – System investigation
- Figma – Cloud infrastructure diagram
- Markdown – Technical documentation

## Linux Commands Executed

The following Linux commands were used during the investigation:

```bash
cat /etc/os-release
uname -r
lscpu
nproc
free -h
df -h
hostname
hostname -I
