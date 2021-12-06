# Useful Ansible Playbooks

A collection of minimalist Ansible playbooks for automating server setups.

## Getting Started

To set up your Ansible environment, please follow my article on Medium: [Ansible: do zero ao Zabbix](https://amauryborgesouza.medium.com/ansible-dozeroaozabbix-a52a5c98175c)

## Run your first network Ansible command

The first thing to do is check the connectivity on the remote server:

#### Usage

```yml
$ ansible [pattern] -m [module] -a "[module options]"
```

Now you can check the ping module command on the servers:

```bash
mkdir girus
```

```yml
# ansible aws -m ping -i inventory.yml 
elliot01 | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3"
    },
    "changed": false,
    "ping": "pong"
}
```

## Run Your First Command and Playbook

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
