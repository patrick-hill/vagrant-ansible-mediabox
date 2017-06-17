# Vagrant-Ansible: MediaBox
Vagrant project to test my [ansible-playbook-mediabox](https://github.com/patrick-hill/ansible-playbook-mediabox) playbook

# Requirements
Vagrant 1.7.4+ [https://www.vagrantup.com/]   
Ansible 2.0.1+ [https://www.ansible.com/]   
Virtualbox 4+ [https://www.virtualbox.org/wiki/Downloads]   
CentOS 7.1 Vagrant Boxes (Possibly 6.7)   
* Repo: Make your own like me: [https://github.com/boxcutter/centos]   
* Use prebuilt boxes: [https://atlas.hashicorp.com/boxcutter/boxes/centos71]    


# Using this Repo
1. Clone the repo
2. Make any needed changes to run.properties
3. Run `./run.sh`
4. Use the following URLS's to test services:
    - Sabnzbd: `localhost:8080`
    - Sickrage: `localhost:8081`
    - CouchPotato: `localhost:5050`
    - Plex: `localhost:32400`
    - Headphones: `localhost:8181`
    - Sonarr: `localhost:8989`
