## Exercise 9
# Ansible Web Server Automation

## Assignment Overview
This project uses **Ansible** to automate the setup of a basic web server environment.  
The playbook provisions a managed node with Apache, deploys a custom web page, sets timezone, manages services, and configures firewall rules.

## Tasks Performed
- Installs Apache web server  
- Deploys a custom `index.html` with the message:  
  *"Hi! My name is Latifah, Hello from Ansible"*  
- Sets server timezone to **Africa/Lagos**  
- Ensures Apache service is **started** and **enabled on boot**  
- Opens **port 80 (HTTP)** via UFW to serve web pages  

## Deliverables
- Ansible inventory file with one host  
- Playbook (`playbook.yaml`)  
- Screenshots of:
  - Playbook code  
  - Playbook execution  
  - Deployed webpage (`index.html`)  
