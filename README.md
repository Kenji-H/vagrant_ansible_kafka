## Usage
### Run Virtual Machines

```
$ cd vagrant
$ vagrant box add ubuntu15.04 https://github.com/kraksoft/vagrant-box-ubuntu/releases/download/15.04/ubuntu-15.04-amd64.box
$ vagrant plugin install vagrant-hosts
$ vagrant up
```

### Run Ansible Playbook

```
$ cd ansible
$ ansible all -m ping
192.168.33.12 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
192.168.33.11 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
$ ansible-playbook site.yml
```
