This is my personal workstation (Desktop/Laptop) configuration management project using [ansible] (http://www.ansibleworks.com/why-ansible/)

# Ansible installation

You can follow ansible [official installation instructions] (http://www.ansibleworks.com/docs/intro_installation.html).

These are the steps I follow to install ansible on my ubuntu workstation:

(for ubuntu)

1. I want to install ansible with python pip and keep it in it's own virtualenv. So install virtualenv if you don't have it.
	sudo easy_install pip

2. Create virtualenv.
	cd ~/python-env && virtualenv my-workstation-config

3. Activate project's virtualenv and install packages from requirements.txt
	source ~/python-env/my-workstation-config/bin/activate && pip install -r requirements.txt

