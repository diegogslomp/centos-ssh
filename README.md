# centos-ssh

Centos8 docker image with ssh service:

```
docker build -t centos-ssh .
docker run -d -p 2222:22 centos-ssh
ssh -p 2222 root@localhost
# pass: newpass
```
