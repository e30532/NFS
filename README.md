# NFS storage on OCP

This yml script creates a NFS storage class on a OCP cluster. 
```
git clone https://github.com/e30532/NFS.git
ssh-copy-id root@api.***.ibm.com
nohup ansible-playbook ./NFS/install.yml -i api.***.ibm.com, -u root > /tmp/nfs.out.log 2>&1 &
```

