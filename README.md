# Paas_shellinabox
Following steps are required -
Providing Platform-as-a-service (PAAS) through shellinabox
1) Configure your hosts file to the remote host where you will run this playbook or to your localhost.
2) Python (platform) will be accessed through your web browser, so allow port forwarding to your docker container by writing the free port available in your localhost or the machine you are using to confugre for paas in var.yml file.
3) Also mention the current location of your Dockerfile which is the current folder. By default, it is left blank.
4) Run the main.yml playbook.
5) After successful completion of your playbook go to your web browser and write http://IP:free_port
6) You will get a python shell.
