# motd-setup-playbook-example
This is the motd playbook where the the motd-setup-ansible role came from.  

To develop an ansible role:  
Write the playbook with descreet tasks.  
Create files and templates needed for tasks.  
Test and make sure that the playbook works as expected.  
Create directory ./roles relative to your playbook(s)
Change directory to ./roles
Use ansible-galaxy command:  
ansible-galaxy init "rolename"  
In this case:  ansible-galaxy init motd-setup-ansible  
and edit appropriate files.  

The playbook tasks end up under motd-setup-ansible/tasks/main.yml  
The template motd.j2 end up under motd-setup-ansible/templates/motd.j2  
The default values are stored under motd-setup-ansible/defaults/main.yml  

Take a look at https://github.com/customizedcode/motd-setup-ansible  
and compare the files mentioned above.

-----
Roy Kim
customizedcode.us
https://github.com/customizedcode
