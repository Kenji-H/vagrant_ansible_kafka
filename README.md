## Usage
### Run Virtual Machines

```
$ cd vagrant
$ vagrant box add ubuntu15.04 https://github.com/kraksoft/vagrant-box-ubuntu/releases/download/15.04/ubuntu-15.04-amd64.box
$ vagrant up
```

### Run Virtual Machines

```
$ cd ansible
$ vi ansible.cfg  # update private_key_file value
$ ansible all -m ping
192.168.33.11 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
```
