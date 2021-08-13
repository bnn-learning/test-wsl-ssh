test-wsl-ssh
8/12/2021 - existing ssh key in WSL did not work with GitHub
- ~/.ssh/id_rsa.pub could not be added to ssh-add
- created new ssh key: id_ed25519.pub
- adding it to local ssh server
- ~ > ssh-add ~/.ssh/id_ed25519
Identity added: /home/brucen/.ssh/id_ed25519 (bnorikane@msn.com)- 
