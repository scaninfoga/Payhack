# Payhack

Create metasploit payload easily using Payhack

![Screenshot](http://scaninfoga.in/wp-content/uploads/2022/04/Payhack.png)


# Installation

### For Linux users -
    sudo apt-get install python3 python3-pip net-tools
    
    git clone https://github.com/scaninfoga/Payhack.git
    
    cd Payhack
    
    sudo pip3 install -r requirements.txt
    
    python3 Payhack.py
    
### For Termux users -
    apt install python wget 
    
    git clone https://github.com/scaninfoga/Payhack.git
    
    cd Payhack
    
    pip install -r requirements.txt
    
    python payhack.py



# What's New in v5.1?

1) Bugs Fixed
2) If metasploit is not installed on your system, it will install automatically on your system (Only works on Debian-based distro and Termux)


# Usage

**1) Create a payload**
- Create a payload outside network by just giving LHOST and LPORT and send it to victim.

**2) Start Listner**
- After creating payload,send it to victim & execute it on victim machine.
- After execution,Select **'Start Listner'**,select LHOST from table and enter LPORT which used while creating payload.
- Now wait until a successfull connection.

**3) Launch Metasploit**
- Start Metasploit using **Launch Metasploit** option.

-----------------------------------------------------------------------------------------------------

### All payloads are stored in 'payload' folder.

-----------------------------------------------------------------------------------------------------

### Tested on - Ubuntu 20.04, Kali linux & Termux

-----------------------------------------------------------------------------------------------------

               www.scaninfoga.in
-----------------------------------------------------------------------------------------------------


# Donate


# upi id= technical777@ybl

