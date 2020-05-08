## environment：
  Ubuntu 18.04.4 LTS
  libpcap

## functions：
1. use libpcap to capture the packets in the local area network
2. support ip, udp, tcp, icmp protocol parsing
3. print the protocol type, address and destination

## how t use：
1. g++ sniffer.cpp -o sniffer -lpcap
2. sudo ./sniffer

