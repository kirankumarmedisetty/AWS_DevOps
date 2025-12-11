#Installing ansible on ubuntu machine (In some destroy's it default comes all the packages in single bundle as below)
apt install ansible

#How to run adhoc commands with example using ansible without playbooks.
#Create a file in remote machine for first time.
- Make sure you are able to authenticate to remote machine without password (ssh-keygen)
- Create a inventory file on host machine and mentione target ip
- Run the below command creates a file on single machine using inventory file.
  # ansible -i inventory 172.168.2.1 -m "shell" -a "touch testfile.txt"
- Run the below command to create a file on all the machines mentioned in inventory file.
  #  ansible -i inventory all -m "shell" -a "touch testfile.txt"
