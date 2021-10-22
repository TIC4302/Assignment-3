# Assignment-3
To bring up the assignment environment, use the command 
```
vagrant up
```

# 🏆 Challenge - 1 
## Objective
Analyse the given PCAP file, and retrieve the document sent to a target server. Wireshark is installed by default in Kali VM.
The PCAP file challenge-01.pcap in the Kali VM desktop.

Tip: LibreOffice can be installed in Kali VM to open and edit .doc files, to install libreoffice use the below command
```
sudo apt-get install -y libreoffice
```

### Useful Links 
Some useful links for solving the challenge
* [Hex Editor for converting and downloading files from raw hex values](https://hexed.it/)
* [Exporting objects from PCAP files](https://unit42.paloaltonetworks.com/using-wireshark-exporting-objects-from-a-pcap/)

  
# 🏆 Challenge - 2
## Objective
Escalate the privileges of user John in the ubuntu VM. 
Login with following credentials, 
```
username: john
password: pass1234
```
Hint: Use Docker privilege escalation technique discussed in class to escalte the privileges

### Screenshot requirements
Output of following commands after privilege escalation
```
hostname
whoami
id
sudo -i
```

### Useful Links
* A Dockerfile is placed in the home folder of user John, type command `ls` to view the dockerfile 
* [Build and run the dockerfile](https://www.freecodecamp.org/news/docker-easy-as-build-run-done-e174cc452599/)
