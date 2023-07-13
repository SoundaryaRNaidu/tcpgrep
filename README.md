# tcpgrep
we developed a command line tool called "tcpgrep" that can be used to filter the TCP traffic.This command line tool helps the user to get the required information on the TCP packets by using the following options. The command is : tcpgrep and the options are :
tcpgrep
-t Display total number of TCP sessions.
-i Display total number of incomplete TCP sessions.
-in Display total number of incomplete TCP sessions with packet numbers.
-r Display total number of RST packets.
-rn Display total number of RST packets with packet numbers.
-a Display total number of duplicate TCP ack packets.
-an Display total number of duplicate TCP ack packets with packet numbers.
-p - Dump specific range of TCP packets. Dump one by one if no range is specified from first.
-p IP:port Start dumping packets with specified IP port.
-p Start dumping packets with specified TCP Flag. (U: Urgent,A: Acknowledgement,P: Push,R: Reset,S: Sync,F: Fin)
