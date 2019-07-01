# Build VPN with AWS on OSX
https://www.freecodecamp.org/news/how-you-can-use-openvpn-to-safely-access-private-aws-resources-f904cd24f890/

###openvpn:

* ssh -i pem openvpnas@ip
* visit ip/admin to get configure file
* download tunnelblick to coonect
* fail due to firewall

###shadowsocks:
*https://blog.csdn.net/Da___Vinci/article/details/86629960
* config ss.json file should be pure to avoid decode problem (no '\'', no '//' and so on)
