# TCP

![State Trasition Diagram](http://www.ssfnet.org/Exchange/tcp/Graphics/tcpStateDiagram1.gif "")

### TCP Header

![TCP Header](http://www.ssfnet.org/Exchange/tcp/Graphics/tcpHeader1.gif "")

##### TCP three-way handshake

![](https://www.cisco.com/c/dam/en_us/about/ac123/ac147/images/ipj/ipj_9-4/94_syn_fig1_lg.jpg)
![](https://sites.google.com/a/javainterview.net/question/_/rsrc/1425457816649/misc/tcp-ip/3-way-handshake-Intro-to-transport-layer-The-internetworking-Part2.gif)
- Both hosts' sequence number is increased by one although no payload was sent or received during the establishment of all TCP sessions.
- 在TCP 链接建立的过程中， 两方主机的序列数字都增加1， 尽管没有发送或者接收真实的数据。
- sequence number will be increased by the length of payload being sent, the acknowledgement number indicates the sequence number of the packet excepted to receive.
- 以后每次数据被发送的时候， 序列号相应增加被发送的字节数， 

##### PUSH and URG flags
- The sending application informs TCP that data should be sent immediately.
- The PSH flag in the TCP header informs the receiving host that the data should be pushed up to the receiving application immediately.
