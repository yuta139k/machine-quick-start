# my-quick-start

This is my development quick setup and quick start!!

# Usage

First, install git and clone this repository.


```
$ git clone git@github.com:kseta/my-quick-start.git
```

Intall Homebrew.

```
# see https://brew.sh/
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Intall Ansible.

```
$ brew install ansible
```

Provisioning, my Mack Book Pro.

```console
$ ansible-playbook -i hosts macos.yml
```

This is all!!
