# IS117 | Homework 3/11/19
## How to access NJIT's AFS Directory from WebStorm
**If you are NOT on the NJIT network. You must follow these steps or this process will not work.**
- [x] Check your local internet settings to make sure you are NOT on NJITSecure.
- [x] Visit https://ist.njit.edu/vpn/ and download Cisco AnyConnect VPN for your particular OS.
- [x] Once the program has been installed, use vpn.njit.edu address to connect to the network.
- [x] Enter in your NJIT login credentials and you will be able to access the NJIT network 

## Once you've connected to the NJIT network

1 ) In WebStorm go to the Tools section on the top left.

![](images/tools.PNG)

2 ) From the tools menu, go to **"Start SSH Session"**.

![](images/tools1.png)

# Linux Commands

- ls: directory listing
- ls -a: formatted listing with all file and folder extensions 
- cd: change current working directory
- pwd: show current directory
- mkdir: create a directory 
- rm: delete/remove command 
- rm -r dir: delete directory dir
- rm -f file: force remove file
- rm -rf dir: force remove directory dir
- cp file1 file2: copy file1 to file2
- cp -r dir1 dir2: copy dir1 to dir2
- mv file1 file2: rename or move file1 to file2
- touch file: create or update file
- man: shows the manual for a particular command
- chmod: changes the file permissions
- chown: changes the ownership 
- vi: initialize linux embedded text editor
- exit: closes out of current session

# How the Internet Works

In order to access a web page, your modem/ router will send a request to a DNS server provided by your internet service provider.
 From there the DNS server will direct you to an online directory of places as to where the current IP address you are looking for. After the DNS server has reached the appropriate place, it will contact the web server of where you are looking towards, and redirect your traffic.
 The web server will then send you a return packet of data, of which will is coming directly from a database, thus allowing you to see a displayed web page.
