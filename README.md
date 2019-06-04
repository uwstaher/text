unicast is a method of connection between client and server which is one to one and it actually uses IP for sessions 
for delivery and tcp and udp. there is more overhead added to server per client and it takes more bandwidth for more clients.
while multicast is a method of sending data from one server or client to a group of clients. it is similar to broadcast. 
it relies of multicast enabled routers. there is a fix bandwidth needed for different number of clients that a server sends 
packet to them. more client does not add overhead to the server.







b node is a type of mDNS nodes that can not resolve name outside multicast zone. also it can do multicast queries. 
it listen to linklocal and local. 
p node is done via multicast only, it should not send multicast query. it is defult method of DHCP name resolution but
not receiving mdns.
m node uses multicast before unicast. and it can listen to linklocal and local scope. 
h node uses unicast before multicast and listen to linklocal and local scope. 
