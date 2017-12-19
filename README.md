
# 	Ceph Cookbook – Second Edition
This is the support file repository for [Ceph Cookbook - Second Edition](https://www.packtpub.com/virtualization-and-cloud/ceph-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_content=9781788391061), published by [Packt](https://www.packtpub.com). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Ceph is a unified distributed storage system designed for reliability and scalability. This technology has been transforming the software-defined storage industry and is evolving rapidly as a leader with its wide range of support for popular cloud platforms such as OpenStack, and CloudStack, and also for virtualized platforms. Ceph is backed by Red Hat and has been developed by community of developers which has gained immense traction in recent years.

This book will guide you right from the basics of Ceph , such as creating blocks, object storage, and filesystem access, to advanced concepts such as cloud integration solutions. The book will also cover practical and easy to implement recipes on CephFS, RGW, and RBD with respect to the major stable release of Ceph Jewel. Towards the end of the book, recipes based on troubleshooting and best practices will help you get to grips with managing Ceph storage in a production environment.

By the end of this book, you will have practical, hands - on experience of using Ceph efficiently for your storage requirements.

## Instructions and Navigations
Some of the important commands are as follows:
```
$ git clone https://github.com/PacktPublishing/Ceph-Cookbook-Second-Edition
```
```
# vagrant up ceph-node1 ceph-node2 ceph-node3
```
```
# yum install ntp ntpdate -y
# ntpdate pool.ntp.org
# systemctl restart ntpdate.service
# systemctl restart ntpd.service
# systemctl enable ntpd.service
# systemctl enable ntpdate.service
```
```
# ceph -s
```


## Software and Hardware Requirements

The various software components required to follow the instructions in the chapters are as
follows:

* VirtualBox 4.0 or higher (https://www.virtualbox.org/wiki/Downloads)
* GIT (http://www.git-scm.com/downloads)
* Vagrant 1.5.0 or higher (https://www.vagrantup.com/downloads.html)
* CentOS operating system 7.0 or higher (http://wiki.centos.org/Download)
* Ceph software Jewel packages Version 10.2.0 or higher (http://ceph.com/resources/downloads/ )
* S3 Client, typically S3cmd (http://s3tools.org/download)
* Python-swift client
* NFS Ganesha
* Ceph Fuse
* CephMetrics (https://github.com/ceph/cephmetrics)


## Related Products
* [Learning Ceph - Second Edition](https://www.packtpub.com/virtualization-and-cloud/learning-ceph-second-edition?utm_source=github&utm_medium=repository&utm_content=9781787127913)

* [Mastering Proxmox - Third Edition](https://www.packtpub.com/big-data-and-business-intelligence/mastering-proxmox-third-edition?utm_source=github&utm_medium=repository&utm_content=9781788397605)

* [Building Data Streaming Applications with Apache Kafka](https://www.packtpub.com/big-data-and-business-intelligence/building-data-streaming-applications-apache-kafka?utm_source=github&utm_medium=repository&utm_content=9781787283985)

