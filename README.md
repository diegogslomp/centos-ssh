# centos-ssh

Centos docker image with ssh service:

```
docker pull diegogslomp/centos-ssh:8
docker run -d -p 2222:22 diegogslomp/centos-ssh:8
ssh -p 2222 root@localhost
# pass: newpass
```
