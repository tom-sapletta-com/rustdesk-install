# rustdesk-install
rustdesk-install


## On ubuntu 22


Make sure you have got access via ssh or otherwise setup prior setting up the firewall. The example commands for UFW (Debian based) are:
```
YOURIP=$(hostname -I | awk '{print $1}')
echo $YOURIP
sudo ufw allow proto tcp from $YOURIP to any port 22
```


```
sudo ufw allow 21115:21119/tcp
sudo ufw allow 8000/tcp
sudo ufw allow 21116/udp
sudo sudo ufw enable
```


CLIENT
```

```



SERVER
```

```



---
+ [edit](https://github.com/tom-sapletta-com/rustdesk-install/edit/main/README.md)
