UniMaster
===========================
UniMaster is an IT Infrastructure Security and Manage Platform

## Essential required packages
* Python2.7
* python-devel
* pip
* lshw
* mysql-devel
* openssl
* gcc

## Essential required python modules
* rsa
* psutil
* futures
* python-magic
* nginxparser
* beautifulsoup4
* requests
* paramiko
* redis
* pymongo
* MySQL-python

## Support OS
| Distribution  | Release | Basic Info| Monitor | Vulscan | Hardening
|:----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|
| Ubuntu  | 11, 12, 14, 15, 16| YES | YES | YES | YES |
| Debian  | 7, 8, 9 | YES | YES | YES | YES |
| Red Hat | 5, 6, 7 | YES | YES | YES | YES |
| Fedora  | 22, 23, 24, 25, 26 | YES | YES | YES | YES |
| MacOS X | xx | YES | YES | YES | YES |


## Tutorial:
This tutorial will let you know how to launch UniMaster client daemon and how to associate your devices with cloud account 
This can be done in the following steps.

1. Install required packages
2. Install required python modules
3. Register a cloud account
4. Launch ./install.sh script
5. Associate your cloud account with your device
6. Enjoy

### Step1. Install required packages

* Ubuntu/Debian/Mint Linux
```Bash
sudo apt-get update
sudo apt-get install python python-dev lshw libmysqlclient-dev openssl gcc

```

* Oracle/RHEL (Red Hat)/CentOS Linux
```Bash
sudo yum update
sudo yum install python python-devel lshw mysql-devel openssl gcc
```

* Fedora Linux
```Bash
sudo dnf update
sudo dnf install python python-devel lshw mysql-devel openssl gcc
```

* Arch Linux
```Bash
sudo pacman -S python2
```

* Suse/OpenSUSE Linux
```Bash
sudo zypper install python
```

* FreeBSD Unix
```Bash
pkg install python2
```

* OpenBSD Unix
```Bash
pkg_add python
```

* MacOS X
```Bash
brew install python
```

### Step2. Install required python modules
We recommend you to install the latest version of following modules

```Bash
pip install psutil futures python-magic nginxparser beautifulsoup4 requests paramiko redis pymongo MySQL-python
```
or
```Bash
python -m pip install psutil futures python-magic nginxparser beautifulsoup4 requests paramiko redis pymongo MySQL-python
```

### Step3. Register a cloud account
Visit https://unimaster.turingsec.com to register a cloud account.  
Cloud account used to manage your multiple devices via web panel.

### Step4. Launch ./install.sh script
This script help you to install Unimaster client daemon on your device.  
We recommend you to launch script with root privilege to have a better experience.  
This script also help you to install required packages and python modules which you haven't installed in Step1 and Step2

```Bash
chmod +x install.sh
./install.sh
```

### Step5. Associate your cloud account with your device
Enter your cloud account registed on Step3


### Step6. Enjoy
Once you see 

