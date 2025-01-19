# Demo Project
  Automate Node js application Deployment

### Technologies used
  - Ansible
  - Nodejs
  - DigitalOcean
  - Linux

### Project Description
- Create server on DigitalOcean
- Write Ansible playbook that installs necessary technologies, creates linux user for an application and deploys a NodeJs application with that user
  
### 1. Create a DigitalOcean Droplet

1. Log in to your [DigitalOcean](https://www.digitalocean.com) account.
2. Create a new droplet (ubuntu) 
3. Ensure your droplet has an SSH key added for secure login.
4. Note the IP address of your droplet for later use.

### 2. Prepare Your Local Environment

Make sure your local machine is set up with:

- **Ansible**: To automate the server setup and deployment.
- **SSH Key**: Ensure the SSH key is configured for secure access to your droplet.

### 3. Create a hosts file in the root directory for Ansible to define your server.


Run the Ansible Playbook
ansible-playbook -i hosts playbook.yml
