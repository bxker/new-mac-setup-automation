# Mac Setup

## Pre-reqs:
1. Install Homebrew
    1. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

1. Install Ansible
    1. `sudo easy_install pip && sudo pip install ansible`


## Run installation
`ansible-playbook -i inventory site.yml -c local`