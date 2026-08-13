# Cloud Infrastructure Components

## 1. Compute Resources

### Example in the Linux Environment

The KillerCoda environment provides an Intel Xeon E312xx processor with 1 CPU core.

### Purpose

Compute resources provide the processing power needed to run applications, execute commands, and perform calculations. The CPU processes instructions and allows the Linux operating system and applications to function.

### Importance in Cloud Computing

Compute resources are essential in cloud computing because applications require processing power to operate. Cloud providers allow organizations to provision and scale virtual CPUs based on their workload requirements.

### Relation to KillerCoda

The KillerCoda environment provides 1 CPU core from an Intel Xeon processor. The `lscpu` command was used to identify the processor information, while `nproc` was used to determine the number of available CPU processing units. The environment also uses KVM virtualization, showing how computing resources can be provided through virtualization.

---

## 2. Storage Resources

### Example in the Linux Environment

The main storage resource identified in the KillerCoda environment is the `/dev/vda1` filesystem with a total capacity of 19G. Additional mounted filesystems include `/boot` and `/boot/efi`.

### Purpose

Storage resources are used to store operating system files, applications, configurations, and user data. They allow information to be retained and accessed when needed.

### Importance in Cloud Computing

Storage is important in cloud computing because applications and services need reliable space for data. Cloud providers offer different storage services that can be scaled according to the amount and type of data being stored.

### Relation to KillerCoda

The `df -h` command was used to investigate the available storage. The main filesystem `/dev/vda1` has a capacity of 19G, with approximately 5.4G used and 13G available. The environment also contains mounted filesystems such as `/boot` and `/boot/efi`.

---

## 3. Networking Resources

### Example in the Linux Environment

The KillerCoda environment has two identified IP addresses:

- 172.30.1.2
- 172.17.0.1

### Purpose

Networking resources allow computers, servers, applications, and other devices to communicate with each other. IP addresses identify systems within a network and allow network communication to take place.

### Importance in Cloud Computing

Networking is essential in cloud computing because cloud resources need to communicate with users, applications, databases, and other services. Proper network configuration also helps provide connectivity, security, and controlled access to cloud resources.

### Relation to KillerCoda

The `hostname -I` command was used to identify the IP addresses assigned to the Linux environment. The two IP addresses observed were 172.30.1.2 and 172.17.0.1. These addresses demonstrate that the virtual Linux environment has network connectivity.

---

## 4. Operating System

### Example in the Linux Environment

The operating system identified in the KillerCoda environment is Ubuntu 24.04.4 LTS (Noble Numbat), running kernel version 6.8.0-136-generic.

### Purpose

The operating system manages hardware and software resources and provides an environment where applications and commands can run. It also manages resources such as the CPU, memory, storage, and networking.

### Importance in Cloud Computing

Operating systems provide the foundation for cloud servers and virtual machines. Linux is widely used in cloud environments because it is flexible, reliable, secure, and provides powerful command-line tools for system administration.

### Relation to KillerCoda

The KillerCoda environment uses Ubuntu 24.04.4 LTS. The `cat /etc/os-release` command was used to identify the operating system, while `uname -r` was used to identify the Linux kernel version. The Linux terminal allowed the investigation and management of the virtual environment.
