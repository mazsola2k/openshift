# openshift automated installer

Automated Installer for Redhat Openshift cluster / SNO

pre-requisite: install a free developer access @ http://developer.redhat.com

sudo dnf install -y python3 python3-pip

pip install --upgrade pip

pip install ansible

git clone https://github.com/mazsola2k/openshift/

cd openshift

ansible-playbook openshift-sno-install.yaml

Bootup with the generated agent.x86_64.iso ISO to VM or Baremetal and let the installer to run (between 1 hours to 2-3 hours in case of vm)
