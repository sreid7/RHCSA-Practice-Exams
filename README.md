# RHCSA-Practice-Exams
Pracice Exam 1
Question 1: How to create a local YUM repository using a RHEL 9 ISO image, assuming the image is mounted on either /mnt or /run in a Linux VM?

**1.** mount /dev/sr0 /mnt **2.** vi /etc/yum.repos.d/rhel9-local.repo
  
**3.** Inside Vi

[rhel9-local]

name=RHEL 9 Local Repository

baseurl=file:///mnt

enabled=1

gpgcheck=0 

Save and exit :wq **4.** dnf clean all && dnf repolist **5.** dnf install nano
