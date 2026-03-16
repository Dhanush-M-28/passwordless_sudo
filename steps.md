Steps to create passwordless sudo on remote machine:
1- Enter into your remote machine using SSH command (ssh username@ipaddress) and the password
2- Switch to root (sudo -i)
3- Open the sudoers file using (sudo visudo)
4- Enter the rule for passwordless sudo (username ALL=(ALL:ALL) NOPASSWD: ALL)
5  Check if the passwordless sudo is working using (sudo -l or sudo -n true)
-
