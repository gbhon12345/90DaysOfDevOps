## Systemd:-

Systemd is a system and service manager for linux operating system.
It is designed to provides number of features such as parallel startup of system serices
at boot time
On demand activation of daemons or dependency based service control logic.

File locations:
/usr/lib/systemd/system/ 
/etc/systemd/system/  --Systemd unit files created by systemctl enable as well as unit files added for extending a service. This directory takes precedence over the directory with runtime unit files.

## Systemd Command:

` systemctl enable httpd.service ` -Enabling the service
` systemctl list-units --type service --all ` --listing service
` systemctl status name.service ` service status
` systemctl is-active name.service ` check if the service is active
` systemctl is-enabled name.service ` -Check service enabled or not
