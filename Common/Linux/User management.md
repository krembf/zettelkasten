#### check user expiration
```sh
chage --list <username>
```
![[Pasted image 20221212014529.png]]

#### expire user password
```sh
chage -d 0 <username>
```

#### add new user
```sh
sudo adduser newuser
```

#### grant new user sudo privileges
```sh
usermod -aG sudo newuser
```

#### see what groups your new user is
```sh
groups newuser
```