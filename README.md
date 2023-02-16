# ansible-pull-authorize-korbad-ssh
Adds Korbad's public keys (from github) to current local user's authorized keys:

```ansible-pull -U git@github.com:Korbad/ansible-pull-authorize-korbad-ssh.git -i localhost, --accept-host-key --clean --purge```


Adds the 'korbad' user and adds the authorized keys to that user:
```ansible-pull -U git@github.com:Korbad/ansible-pull-authorize-korbad-ssh.git -i localhost, --accept-host-key --clean --purge -K board_korbad_user.yml```