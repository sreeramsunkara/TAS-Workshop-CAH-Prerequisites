![](./images/vmware-logo.png)

# VMware Tanzu Application Service Workshop 
### (9:00AM to 12:00PM on 01-28-2021)

- We need you to carry out a few prerequisite steps in preparation for the July 22nd Tanzu Application Service Workshop

#
### 1. Sign-up using the Progress Worksheet

- You should be able to access this [Workshop Google Sheet](https://docs.google.com/spreadsheets/d/1IRY5QVNfI5fkrqmpbwCagM5kffEysAnsXoYI68mdlKo/edit?usp=sharing) 
    
  **Action Item**:
  - Please add your name to the Google Sheet to claim your UserID.
  - Workshop sizing is a function of the # of attendees.

#
### 2a. If using a Windows PC
- You will need to use [PuTTY](https://github.com/sreeramsunkara/TAS-Workshop-Prerequisites/blob/master/PuTTY_and_SSH.md) to access a Ubuntu VM (public IP address) using a `.ppk` private-key file.
- To download [`cah.ppk`](https://github.com/sreeramsunkara/TAS-Workshop-Prerequisites/blob/master/cah.ppk) you can install and use [wget](http://downloads.sourceforge.net/gnuwin32/wget-1.11.4-1-setup.exe) in a PowerShell window.
```
help wget
cd ~\Downloads
wget https://raw.githubusercontent.com/sreeramsunkara/TAS-Workshop-Prerequisites/master/cah.ppk -Outfile cah.ppk
```
- If you rather not install [wget](http://gnuwin32.sourceforge.net/packages/wget.htm), you can simply click on [`cah.ppk`](https://raw.githubusercontent.com/sreeramsunkara/TAS-Workshop-Prerequisites/master/cah.ppk) then cut-&-paste its contents to a local file in your Windows machine. The file must be named `cah.ppk` and set to read-only mode.
- If you need help installing or using PuTTY with [cah.ppk](https://raw.githubusercontent.com/sreeramsunkara/TAS-Workshop-Prerequisites/master/cah.ppk) check these [detailed instructions](https://github.com/sreeramsunkara/TAS-Workshop-Prerequisites/blob/master/PuTTY_and_SSH.md).
- If you successfully tested the access to the `ubuntu@user1.pks4u.com` VM, you are ready for the workshop.

#
### 2b. If using a  Mac 
- You will need to SSH into a Ubuntu VM (public IP address) using a private-key `.pem` file
- Using a Terminal Window, execute the following commands to download `cah.pem` and set the downloaded file to read-only mode:
```
cd ~/Downloads
wget https://raw.githubusercontent.com/sreeramsunkara/TAS-Workshop-Prerequisites/master/cah.pem
chmod 400 ~/Downloads/cah.pem
```
- You can now test whether SSH is working with the `cah.pem` private key using the following command:
```
ssh -i ~/Downloads/cah.pem ubuntu@user1.pks4u.com
```
- Please `exit` from the Ubuntu VM if your test was successful. You are ready for the workshop.

#
### 3. If using Google Chrome or Firefox as your Browser

- Throughout this workshop you will be frequently asked to cut & paste commands from this github page to your terminal window.
- Consequently, the [CodeCopy](https://github.com/zenorocha/codecopy#install) browser extension for Firefox & Google Chrome can be a valuable add-on to have. 
- If installing add-ons does not infringing on corporate security policies, please go ahead and install CodeCopy.


#

## [Link to Workshop](https://github.com/sreeramsunkara/TAS-Workshop#vmware-tanzu-application-service-workshop)


