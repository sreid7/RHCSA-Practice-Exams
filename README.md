# RHCSA-Practice-Exams
**Practice Exam 1**

**Question 1**: How to create a local YUM repository using a RHEL 9 ISO image, assuming the image is mounted on either /mnt or /run in a Linux VM?

**1.** mount /dev/sr0 /mnt **2.** vi /etc/yum.repos.d/rhel9-local.repo
  
**3.** Inside Vi

[rhel9-local]

name=RHEL 9 Local Repository

baseurl=file:///mnt

enabled=1

gpgcheck=0 

Save and exit :wq **4.** dnf clean all && dnf repolist **5.** (test) dnf install nano

**Question 2**: How to configure a network interface in Red Hat Enterprise Linux 9 to use a static IP address setup with these parameters: IPv4 address 192.168.1.211 with a 24-bit subnet mask, a gateway of 192.168.1.1, and a DNS server address of 8.8.8.8?

**1.** 
