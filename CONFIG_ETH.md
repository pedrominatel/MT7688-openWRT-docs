
# Using Ethernet interface with DHCP

*File: /etc/config/network

	config interface 'loopback'
		option ifname 'lo'
		option proto 'static'
		option ipaddr '127.0.0.1'
		option netmask '255.0.0.0'

	config interface 'lan'
		option ifname 'eth0'
		option proto 'dhcp'
		option gateway '0.0.0.0'
