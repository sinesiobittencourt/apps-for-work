# Apps For Working

## How to start your Workstation

Step 1 -  Install Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
Step 2 - Clone this repository
```bash
git clone https://github.com/sinesiobittencourt/apps-for-work.git
```
Step 3 - Enter the folder
```bash
cd apps-for-work
```
Step 4 - Apply the configuration
```bash
ansible-playbook ubuntu.yml --ask-become-pass
```
