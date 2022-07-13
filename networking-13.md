# Validate network config
- display interface name associated with Ethernet address .....
  ip link
- display current IP address and netmask for all interfaces
  ip -br addr 
- display statistics for interface X
  ip -s link show enX
- display route info
  ip route
- verify router is accessible
  ping -c3 x.x.x.x
- show all hops between local system and classroom.example.com
  tracepath classroom.example.com
- display listening sockets
  ss -lt

CIDR address 192.168.122.225/24 means the first 24 bits are the network address and the last 8 bits are the hostname i.e. 192.168.122.0 is the network and the host address is 225

# Configure networking from command line
# Configure networking via config files
# Configure hostnames and name resolution

