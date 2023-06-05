# rustdesk-install
rustdesk-install

+ [rustdesk/rustdesk-server: RustDesk Server Program](https://github.com/rustdesk/rustdesk-server)
+ [Installation :: Documentation for RustDesk](https://rustdesk.com/docs/en/self-host/install/)


## DOCKER

+ [rustdesk-server/docker-compose.yml at master · rustdesk/rustdesk-server · GitHub](https://github.com/rustdesk/rustdesk-server/blob/master/docker-compose.yml)


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
