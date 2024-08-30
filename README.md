GitHub Link->https://github.com/Siddhant22497/2022497-Assignment1

Name  : Siddhant Singh
RollNo: 2022497

Question-1
Code-> ifconfig

Question-2
Code-> Adding Custom IP Address
            sudo ip addr show
            sudo ip addr add 192.168.0.0/24 dev eth0
            sudo ip addr show
        Revert IP Address changes
            sudo ip addr del 192.168.0.0/24 dev eth0
            sudo ip addr show

Question-3
Code-> //At Server Side                                  //At Client Side
         netcat -l 1234                                    netcat 127.0.0.1 1234
                                                           netstat -an | grep 1234

Question-4
Code->   nslookup
         set type=ns
         www.google.in

Question-5
Code-> a) traceroute google.in
       b) ping -c 50 google.in
       f) ping -c 50 stanford.edu
       g) traceroute stanford.edu 
          traceroute google.in
       h) ping -c 50 google.in
          ping -c 50 stanford.edu

Question-6
Code->  sudo iptables -A INPUT -p icmp --icmp-type echo-request -j DROP
        ping 127.0.0.1
        sudo iptables -D INPUT -p icmp –icmp-type echo-request -j DROP

