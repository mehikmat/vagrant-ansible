vagrant-ansible
===============
Repository for testing vagrant and ansible functioning

How to use
=============== 

$ git clone https://github.com/mehikmat/vagrant-ansible.git

$ cd vagrant-ansible

Replace box url with yours 
eg. config.vm.box_url = "file:///home/hikmat/contributions/vagrant-ubuntu/boxes/ubuntu1304-x86_64-20140301.box"

To get ubuntu box, follow below steps

$ git clone https://github.com/mehikmat/developer-setup.git

$ cd developer-setup

$ ./setup.sh

$ git clone https://github.com/mehikmat/vagrant-ubuntu.git

$ cd vagrant-ubuntu

$ ./setup

==============OR===============
You can download ubuntu box from web

After replacing box url in Vagrantfile

$ vagrant up


