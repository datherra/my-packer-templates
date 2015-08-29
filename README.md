[Packer](http://packer.io) templates for Linux boxes.
v0 of this templates are from https://bitbucket.org/ariya/packer-vagrant-linux

  - VirtualBox
    - CentOS 6.4 (Minimal) 64-bit
    - CentOS 6.5 (Minimal) 64-bit
    - Oracle Enterprise Linux 6.2 32-bit
    - Ubuntu 12.04.5 64-bit
  - AWS
    - non-packer
    -- CentOS 7 64-bit
    - penging
      retrive AMI ID and populate Vagrantfile
      create AMI from kickstart file
    - manual
      vagrant-aws plugin install
  - Digital Ocean
    - pending
      'vagrantify' (packer 0.7.5 and master are broken on this)
    - manual
      vagrant-digitalocean plugin install


Use the box (generated in `build` subdirectory) with
[Vagrant](http://vagrantup.com)

- TODO
  - double check kickstart file (packages are coming from Internet instead of ISO)