# ansible-local
Setup for local pc
Adhoc adding to this repo which feeds on .dotfile module: https://github.com/viktorybloom/.dotfiles
So it may look incomplete, but got me to a running environment, but no doubt on a new install, I will be adding more. 

### Run instructions

Run `ansible-playbook --ask-become-pass local_playbook.yaml`

For vault protected auth passwords and tokens, use `ansible-vault encrypt/decrypt ...`
