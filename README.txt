## .Trojan App Critical Vulnerability Fix - V-ESM-2019-0001

This security patch will address a critical vulnerability within the .Trojan app.


Steps to patch.
Do the following command

1) mv ~/.trojan/trojan_env/Trojan_App/Trojan/AWS_Utilities/src/server_util.py /tmp/backup_server_util.py
2) cp patch_server_util.py ~/.trojan/trojan_env/Trojan_App/Trojan/AWS_Utilities/src/server_util.py

