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

Step 3 - Apply the configuration
```bash
ansible-playbook tools/ubuntu.yml --ask-become-pass
```
