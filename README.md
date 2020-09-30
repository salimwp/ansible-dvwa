This repo houses a simple Ansible playbook used to configure a VM to run
[Damn Vulnerable Web Application (DVMA)](http://www.dvwa.co.uk/). A great application to 
learn the ins and outs of security testing of web applications.

To use this repo, simply clone it and run 

```
git clone https://github.com/salimwp/ansible-dvwa.git
cd ansible-dvwa
vagrant up
```

The URL is http://10.0.0.80/dvwa

To change the IP address, edit the IP in the Vagrant file.

This application is full of security holes and should not be accessible to the public.