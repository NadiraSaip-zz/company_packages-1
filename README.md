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



****install atop on
