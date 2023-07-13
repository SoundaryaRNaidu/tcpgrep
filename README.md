# tcpgrep
we developed a command line tool called "tcpgrep" that can be used to filter the TCP traffic.It can be used to filter traffic based on a variety of criteria, including source and destination IP addresses, ports, and protocols.This command line tool helps the user to get the required information on the TCP packets by using the following options. The command is : tcpgrep and the options are :
tcpgrep
1.-t Display total number of TCP sessions.
2.-i Display total number of incomplete TCP sessions.
3.-in Display total number of incomplete TCP sessions with packet numbers.
4.-r Display total number of RST packets.
5.-rn Display total number of RST packets with packet numbers.
6.-a Display total number of duplicate TCP ack packets.
7.-an Display total number of duplicate TCP ack packets with packet numbers.
8.-p - Dump specific range of TCP packets. Dump one by one if no range is specified from first.
9.-p IP:port Start dumping packets with specified IP port.
10.-p Start dumping packets with specified TCP Flag. (U: Urgent,A: Acknowledgement,P: Push,R: Reset,S: Sync,F: Fin)
