# UniFi-Linux-Install
This is UniFi Linux Install Script Backup

In case Community is no longer available. 

Original From:[Ui.com Community](
https://community.ui.com/questions/UniFi-Installation-Scripts-or-UniFi-Easy-Update-Script-or-UniFi-Lets-Encrypt-or-UniFi-Easy-Encrypt-/ccbc7530-dd61-40a7-82ec-22b17f027776)


## Install Step:

1) Copy the link location of the script.  

2) SSH into your Ubuntu/Debian machine, and login as root. ( Ubuntu | sudo -i | Debian | su )
  
2a) Make sure the ca-certificates package is installed.  
```
apt-get update; apt-get install ca-certificates wget -y
```
3) Download the script by executing the following command. ( change it to your wanted version )   
```
wget https://get.glennr.nl/unifi/install/unifi-6.5.55.sh
```

4) Now run the script with the command below.  
```
bash unifi-6.5.55.sh
```   

## Update Step:
1) Copy the link location of the script.  

2) SSH into your Ubuntu/Debian machine, and login as root. ( Ubuntu | sudo -i | Debian | su )  

2a) Users with a UDM/UDM-Pro running UniFi OS have to first enter the shell with unifi-os shell.  

3) Make sure the ca-certificates package is installed.
```
apt-get update; apt-get install ca-certificates wget -y
```  
4) Execute the following commands to download the script.
```
wget https://get.glennr.nl/unifi/update/unifi-update.sh
```
  
5) Now run the script with the command below.
```
bash unifi-update.sh
```
