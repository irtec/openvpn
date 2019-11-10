Ubuntu Install
<pre>wget https://raw.githubusercontent.com/irtec/openvpn/master/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh</pre>

Centos 7 Install
wget https://raw.githubusercontent.com/irtec/openvpn/master/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh</pre>
<pre>sudo systemctl stop openvpn@server # <--- stop server
sudo systemctl start openvpn@server # <--- start server
sudo systemctl restart openvpn@server # <--- restart server
sudo systemctl status openvpn@server # <--- get server status
