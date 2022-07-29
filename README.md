This is my July 23 Homework

It's a simple terraform script to create a simple EC2 instance generated with Ansible, which will install nginx on that EC2 and run a simple html file


To RUN these script u have to:

Sign in AWS

then

$ aws configure
AWS Access Key ID [****************D55M]: **************************************
AWS Secret Access Key [****************A+Mg]: **********************************
Default region name [us-east-1]: ***********
Default output format [json]: **************

install Ansible:

$ sudo apt update
$ sudo apt install ansible



install Terraform:

$ wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg
$ echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
$ sudo apt update && sudo apt install terraform



