# Samba Server

### Windows client

[client modify](https://www.cnblogs.com/Dy1an/p/11325272.html)

[client modify](https://www.zhihu.com/question/59814912)


### Linux client

```bash
sudo mount -t cifs -o rw,dir_mode=0644,file_mode=0644,username=user,password=password,port=445 //ip_address/share_name /mnt/point
```

```bash
smbclient -p 445 //ip_address/share_name -U user%password
```
