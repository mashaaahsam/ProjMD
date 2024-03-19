
```shell
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Run this command to crate a ssh key located in /$HOME/.ssh


---
Note:
1. Some old systems may not support ed25519 algorithm so some old algorithm may be used like rsa.
```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
