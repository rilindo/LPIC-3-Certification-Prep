This is a list of resources needed to pass LPI3 117-300 - Mixed Environments

#Study Objectives

https://www.lpi.org/study-resources/lpic-3-300-exam-objectives/

http://www.ibm.com/developerworks/linux/library/l-lpic3-310-1/ - Note that it refers to LPIC-302, but the material in it is now in LPIC-300

## 390 – OpenLDAP Configuration

### 390.1 OpenLDAP Replication

* Replication concepts
* Configure OpenLDAP replication
* Analyze replication log files
* Understand replica hubs
* LDAP referrals
* LDAP sync replication

### 390.2 Securing the Directory

* Securing the directory with SSL and TLS
* Firewall considerations
* Unauthenticated access methods
* User / password authentication methods
* Maintanence of SASL user DB
* Client / server certificates

### 390.3 OpenLDAP Server Performance Tuning

* Measure OpenLDAP performance
* Tune software configuration to increase performance
* Understand indexes

## 391 – OpenLDAP as an Authentication Backend

### 391.1 LDAP Integration with PAM and NSS

* Configure PAM to use LDAP for authentication
* Configure NSS to retrieve information from LDAP
* Configure PAM modules in various Unix environments

### 391.2 Integrating LDAP with Active Directory and Kerberos

* Kerberos integration with LDAP
* Cross platform authentication
* Single sign-on concepts
* Integration and compatibility limitations between OpenLDAP and Active Directory

## 392 – Samba Basics

### 392.1 Samba Concepts and Architecture

* Understand the roles of the Samba daemons and components
* Understand key issues regarding heterogeneous network
* Identify key TCP/UDP ports used with SMB/CIFS
* Knowledge of Samba3 and Samba4 differences

### 392.2 Configure Samba
 
* Knowledge of Samba server configuration file structure
* Knowledge of Samba variables and configuration parameters
* Troubleshoot and debug configuration problems with Samba

### 392.3 Regular Samba Maintenance

* Monitor and interact with running Samba daemons
* Perform regular backups of Samba configuration and state data


### 392.4 Troubleshooting Samba


* Configure Samba logging
* Backup TDB files
* Restore TDB files
* Identify TDB file corruption
* Edit / list TDB file content


### 392.5 Internationalization

* Understand internationalization character codes and code pages
* Understand the difference in the name space between Windows and Linux/Unix with respect to share, file and directory names in a non-English environment
* Understand the difference in the name space between Windows and Linux/Unix with respect to user and group naming in a non-English environment
* Understand the difference in the name space between Windows and Linux/Unix with respect to computer naming in a non-English environment

## 393 – Samba Share Configuration

### 393.1 File Services

* Create and configure file sharing
* Plan file service migration
* Limit access to IPC$
* Create scripts for user and group handling of file shares
* Samba share access configuration parameters

### 393.2 Linux File System and Share/Service Permissions

* Knowledge of file / directory permission control
* Understand how Samba interacts with Linux file system permissions and ACLs
* Use Samba VFS to store Windows ACLs

### 393.3 Print Services

* Create and configure printer sharing
* Configure integration between Samba and CUPS
* Manage Windows print drivers and configure downloading of print drivers
* Configure [print$]
* Understand security concerns with printer sharing
* Uploading printer drivers for Point’n’Print driver installation using ‘Add Print Driver Wizard’ in Windows

## 394 – Samba User and Group Management

### 394.1 Managing User Accounts and Groups

* Manager user and group accounts
* Understand user and group mapping
* Knowledge of user account management tools
* Use of the smbpasswd program
* Force ownership of file and directory objects

### 394.2 Authentication, Authorization and Winbind

* Setup a local password database
* Perform password synchronization
* Knowledge of different passdb backends
* Convert between Samba passdb backends
* Integrate Samba with LDAP
* Configure Winbind service
* Configure PAM and NSS

## 395 – Samba Domain Integration

### 395.1 Samba as a PDC and BDC

* Understand and configure domain membership and trust relationships
* Create and maintain a primary domain controller with Samba3 and Samba4
* Create and maintain a backup domain controller with Samba3 and Samba4
* Add computers to an existing domain
* Configure logon scripts
* Configure roaming profiles
* Configure system policies

### 395.2 Samba4 as an AD compatible Domain Controller

* Configure and test Samba 4 as an AD DC
* Using smbclient to confirm AD operation
* Understand how Samba integrates with AD services: DNS, Kerberos, NTP, LDAP

### 395.3 Configure Samba as a Domain Member Server

* Joining Samba to an existing NT4 domain
* Joining Samba to an existing AD domain
* Ability to obtain a TGT from a KDC

## 396 – Samba Name Services

### 396.1 NetBIOS and WINS

* Understand WINS concepts
* Understand NetBIOS concepts
* Understand the role of a local master browser
* Understand the role of a domain master browser
* Understand the role of Samba as a WINS server
* Understand name resolution
* Configure Samba as a WINS server
* Configure WINS replication
* Understand NetBIOS browsing and browser elections
* Understand NETBIOS name types

### 396.2 Active Directory Name Resolution

* Understand and manage DNS for Samba4 as an AD Domain Controller - [Setup a Samba Active Directory Domain Controller](https://wiki.samba.org/index.php/Setup_a_Samba_Active_Directory_Domain_Controller)
* DNS forwarding with the internal DNS server of Samba4 - [Samba Internal DNS](https://wiki.samba.org/index.php/Samba_Internal_DNS)

## 397 – Working with Linux and Windows Clients

### 397.1 CIFS Integration

* Understand SMB/CIFS concepts - [Getting Familiar with a SMB/CIFS Network](http://www.oreilly.com/openbook/samba/book/ch01_03.html)
* Access and mount remote CIFS shares from a Linux client -  [Linux mount CIFS Windows Share](http://www.cyberciti.biz/faq/linux-mount-cifs-windows-share/
* Securely storing CIFS credentials - [Proper way to mount samba share](http://unix.stackexchange.com/questions/82194/proper-way-to-mount-samba-share)
* Understand features and benefits of CIFS - [Learn Linux, 302 (Mixed environments): CIFS integration](http://www.ibm.com/developerworks/library/l-lpic3-314-1/)
* Understand permissions and file ownership of remote CIFS shares - [File, Directory, and Share Access Controls](https://www.samba.org/samba/docs/man/Samba-HOWTO-Collection/AccessControls.html)

### 397.2 Working with Windows Clients

* Knowledge of Windows clients - [Configuring Windows Clients](https://www.samba.org/samba/docs/using_samba/ch03.html)
* Explore browse lists and SMB clients from Windows - [Accessing an SMB Share With Linux Machines](http://www.tldp.org/HOWTO/SMB-HOWTO-8.html)
* Share file / print resources from Windows - [Using Samba to share files between Linux and Windows](https://www.linux.com/news/using-samba-share-files-between-linux-and-windows)
* Use of the smbclient program - [Samba Client Guide](https://help.ubuntu.com/community/Samba/SambaClientGuide)
* Use of the Windows net utility - [Linux for Windows Admins: Doing the Samba Shuffle](http://www.admin-magazine.com/Articles/Linux-for-Windows-Admins-Samba-Shuffle)