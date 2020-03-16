# HarmonyValidatorAlerts

Steps to run harmony node with systemd:

1. create a service file: sudo nano /etc/systemd/system/harmony.service;
2. copy the code above into the service file created and adapt it; It is important to define correctly the working directory and from where the node should be executed. This is basically quite simple as it represents the user and folder where node.sh is placed.
3. Ctrl+X to save the service file;
4. You might have to create the hmn directory under /var/log/ so that the hmn.log or how you want to call it can be written into;
5. sudo systemctl enable harmony.service;
6. sudo systemctl start harmony.service;
7. sudo systemctl status harmony.service;
8. Check the logs;
