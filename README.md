# openvpn_as
làm việc trên OpenVPN Access Server 2.11.3 của digitalocean

Tải file pyovpn-2.0-py3.10.egg thay thế file trong đường dẫn /usr/local/openvpn_as/lib/python/pyovpn-2.0-py3.10.egg

```bash
mv /usr/local/openvpn_as/lib/python/pyovpn-2.0-py3.10.egg /usr/local/openvpn_as/lib/python/pyovpn-2.0-py3.10.egg_bak
wget -O /usr/local/openvpn_as/lib/python/pyovpn-2.0-py3.10.egg https://github.com/Leak-VN/openvpn_as/raw/refs/heads/main/pyovpn-2.0-py3.10.egg
cd /usr/local/openvpn_as/bin
./ovpn-init
```