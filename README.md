# Vagrant environment for Python development

````
git clone https://github.com/thielsen/vagrant-python-dev-environment.git
vagrant up
````

Files stored in /home/vagrant will be accesible in the vagrant-python-dev-environment directory allowing use of your favourite editor on the host.

To reprovision after any change to the ansible yml file run

````
vagrant up --provision
````
