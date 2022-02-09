# Connect to VPN

* update Apt repository cache
```
sudo apt update
```

* using Apt install OpenVPN client using Debian 11 default repository
```
sudo apt install openvpn --no-install-recommends
```

* verify successful installation
```
sudo openvpn --version
```

* list available options if the client
```
sudo openvpn
```

* connect to VPN
```
sudo openvpn --config <*.ovpn>
```
