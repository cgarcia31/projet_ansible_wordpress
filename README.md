# projet_ansible_wordpress

## Step 1 
**Configure your project**
Delete the file files/secrets/credentials to create your own.
Edit the ansible.cfg file to configure your password vault file
Look at the defaults files for each role to see the variables to modify if you wish
Adapt the prod.yml inventory file as well as the files in host_vars and group_vars

## Step 2
**Launch of the playbook**
Add your variables file if you have created one in the master.yml file

ansible-playbook master.yml

## Step 3
**Test your wordpress instance**
Open the browser and go to the page: http://YOURCLIENTIP/wordpress

## ToDo :
* https management with let's encrypt
* Configuration for different operating systems
* Modify apache so that the virtualhost is the default when accessing via ip
