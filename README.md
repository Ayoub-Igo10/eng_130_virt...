-   GNU nano 6.4                                                                               README.md
### Vagrant
- check internet connectivity `sudo apt-get update`
- Run upgrade `sudo apt-get upgrade-y`
- Where am i `pwd` give you your current location
- Whoami `uname` or `uname -a`
- How to create a file in linux `touch filename` & `nano filename`v
- How to check file/folder available in current location
`ls` or to check all files hidden files as well `ls -a`
- How to create a folder
- How to navigate between OS & VM `exit` Enter
- for admin access `sudo` switch to admin user `sudo su`
- change permission `chmod intruction file-name` i.e
        `chmod 700 test.text`
- Currently running process `top` & `ps aux`
- To remove any process `kill PID` - `kill 7`
- how to delete folder/hidden folder `ls -a`

- print last 3 lines from the test.txt
- print first 3 lines from the test.txt
- print last 10 lines from the test.txt
- print last lines from the text.txt
- Research how to use ` pipe` & `grep` & `sort`
- `ps aux` short list by name
- How to create/run a process in the background & foreground, create/run a process in both areas
- kill the process that you create- `sudo apt-get install nginx -y`
- How to check a tool/software status in linux `usdo systemctl status nginx`
- How to restart a process in Linux
- testestst


 ` pipe` & `grep` & `sort`

- Sort command helps in sorting out the contents of a file alphabetically.

  The syntax for this command is: `sort Filename`

- Grep command. It will scan the document for the desired information and present the result in a format you want.

  The Syntax for this command is: `grep search_string`

- Pipes help you mash-up two or more commands at the same time and run them consecutively

  The syntax for this command is: `cat filename | less`

# How to force kill process in Linus:

- Use the pidof command to find the process ID of a running program or app
  `pidoff appname`

- To kill process in Linux with PID:
  `kill -9 pid`

- Want to kill process in Linux with application name? Try:
  `killall -9 appname`

### Task

- What is virtualisation & benefits of it?
  
  Virtualization relies on software to simulate hardware functionality and create a virtual computer system. This enables IT organizations to run more than one virtual system – and multiple operating systems and applications – on a single server. The resulting benefits include economies of scale and greater efficiency.

- what is dev env?
  
 A development environment in software and web development is a workspace for developers to make changes without breaking anything in a live environment.

- What is vagrant?

Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time

- What is a virtual box?

VirtualBox is open-source software for virtualizing the x86 computing architecture. It acts as a hypervisor, creating a VM (virtual machine) where the user can run another OS (operating system).

