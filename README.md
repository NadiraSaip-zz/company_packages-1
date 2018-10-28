***** fail2ban service *****
fail2ban.yml
This playbook installs and configure fail2ban on amazon, linux and centOS7
The requirment to install fail2ban service is epel-relese repasetory
1. it installs epl-release on centOS7
2. It installs epel-release on amazon-linux
3. Installs fail2ban on amazon,linux and centOS7
4. enables fail2ban service 
5. create configuration file on centOS7
6. Configures fail2ban service on centOS7
7. Configures fail2ban service on amazon linux
8. Restarts fail2ban service on amazon linux
9. Restart fail2ban service on centOS7

**fail2ban configuration**
The configuration
1. Allows 3 tryes
2. Allows 2 minutes to login 
3. It failes to loginbans for 1 hour
4. Ignors company's CIDR block



Create file 5GB

This playbook create 5Glogfile in projects. You can pull it for some project and create your template and use it.

*atop_installation.yml

This playbook installs on Centos/RedHat. Atop is not available on Ubuntu. It is safe to run the playbook

*5Glogfile.yml I was able to create the playbook, and I created a project under my name "Roman's Project". Within this project you have atop-installation.yml file. Use it to install on Centos/Redhat Systems. Unfortunately atop is not available for Ubuntu. Please let me know if you have any questions. For more instructions please read README file.
