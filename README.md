### Vagrant commands
`vagrant init` Init Vagrantfile \
`vagrant status` Check vm status. \
`vagrant up` Create and start. \
`vagrant suspend` VM Pause. \
`vagrant halt` VM shutdown. \
`vagrant destroy -f` Forse stop and delete VM.


`vagrant ssh-config` Check vm config (all what need for connect to vm) \

### Connect
`vagrant ssh` / `vagrant ssh <vm hostname>`  \
<b>OR</b> \
`ssh vagrant@127.0.0.1 -p 2222 -i full_path/.vagrant/machines/default/virtualbox/private_key`

### Box commands
`vagrant box help` Find out the list of commands \
`vagrant box <param> -h` Parameter list, where <param> can be: <span style="color: #10a006">add, list, outdated, prune, remove, repackage, update</span> \
`vagrant box add --provider virtualbox centos/7` Download centos / 7 for vm virtualbox \
`vagrant box list` List of downloaded os \
