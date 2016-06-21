Packer configuration for creating Ubuntu 12.04 Virtualbox virtual machines
================
A [packer](http://www.packer.io/) template (`ubuntu_64.json`) with a debconf preconfiguration file to automate the Ubuntu installer (`preseed.cfg`). Outputs a Virtualbox VM image in `output-virtualbox-iso` with a fully configured Ubuntu 12.04 LTS, ready for you to SSH into and further customize. You can read the blog post that goes with the code here: [Creating An Ubuntu VM With Packer](http://kappataumu.com/articles/creating-an-Ubuntu-VM-with-packer.html)
