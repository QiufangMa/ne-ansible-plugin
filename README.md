# **ne-ansible-plugin**
ne-ansible-plugin is an ansible plugin for managing huawei net-engine series products, such as ATN,
NE,ME,CX routers.

## **Features**
- provide command line plugin for managing huawei net-engine series products
- provide netconf plugin for managing huawei net-engine series products
- provide a common command line module 
- provide a template command line module for delivering commands in batches
- provide a common netconf module, it will be referenced by ansible api generated by [ansible-gen](https://github.com/HuaweiDatacomm/ansible-gen)

[]()

## installation

### Prerequisites

- OS: Red Hat,Ubuntu,CentOS,OS X,BSD,Suse
- Python:  python2.6 or later (python 2.7 is preferred)/python3.x
- Ansible: 2.6 or later, lower than 2.10

### configure environment

`vi /etc/profile`

add ansible path and ncclient path

`export ncclient_path="/usr/lib/python2.7/site-packages/ncclient"`

`export ansible_path="/usr/lib/python2.7/site-packages/ansible-2.6.7.post0-py2.7.egg/ansible"`

or whatever version of python you installed

`source /etc/profile`

### obtain code

```
$git clone https://github.com/HuaweiDatacomm/ne-ansible-plugin.git
```

### execute install.sh

```
$cd ne-ansible-plugin
```

```
$chmod 777 install.sh
```

```
$sh install.sh
```
## Usage Examples
TBD
