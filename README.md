# iisdotnetcoreplaybook
Ansible Playbook to install IIS and dotnet core on the fresh new Windows Server 2008 R2

If you are not aware of [Ansible](https://www.ansible.com/quick-start-video), its a configuration mananagement tool similar to Chef, Puppet. It has instruction file know as Playbook. It YAML file with task as step

It will do the following
- Install Powershell 5
- Install unzip
- Enable IIS feature on Win 2008
- Install dotnet core server hosting
- Create AppPool, Website
- Copies the code to machine, and setup the ACL's for AppPool

## Instruction

### Step 1
Clone this repo to any disire directory

### Step 2
To run the playbook, install ansible on the machine

### Step 3
Modify the hosts file to enter machine or group of machine you are targeting

### Step 4
Run following command

> $ ansible-playbook playbook.yml 

You can find more information at 
[https://github.com/sbrakl/iisdotnetcoreplaybook/wiki](https://github.com/sbrakl/iisdotnetcoreplaybook/wiki)

If you have any question, you can post under GitHub Issue