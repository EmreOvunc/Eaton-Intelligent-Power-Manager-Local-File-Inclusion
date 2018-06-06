# Eaton-Intelligent-Power-Manager-Local-File-Inclusion
Local file inclusion in Eaton Intelligent Power Manager  v1.6 allows an attacker to include a file, it can lead to sensitive information disclosure, denial of service and code execution.

To exploit vulnerability, someone could use 'https://[HOST]/server/node_upgrade_srv.js?action=downloadFirmware&firmware=/../../../../../../../../../../' request to get some informations from the target.

![alt tag](https://www.emreovunc.com/blog/en/eaton-power-manager-lfi.jpg)
