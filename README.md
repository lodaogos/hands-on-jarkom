# hands-on-jarkom

Nama : Charles

NRP : 5025211082

## TCP Hands On
### No 1

![no1](src/TCP-Hands-On/no1.jpg)
![no1_2](/src/TCP-Hands-On/no1_2.jpg)

Jawab :

IP : 192.168.86.68
Port : 55639

### No 2

Jawab :

128.119.245.12
Port : 80

### No 3 

![no3](/src/TCP-Hands-On/no3.jpg)

Jawab :

Seq = 4236649187

### No 4

![no4](/src/TCP-Hands-On/no4.jpg)

Jawab :

Seq = 1068969752
The ack has a value
Ack = 4236649188

### No 5

![no5](/src/TCP-Hands-On/no5.jpg)
![no5_2](/src/TCP-Hands-On/no5_2.jpg)

Jawab :

Seq = 4236649188
TCP Payload bytes : 1448
No

### No 6 

-

### No 7

Jawab :

Length : 1514

###No 8 

-

###No 9

![no9](/src/TCP-Hands-On/no9.jpg)

Jawab :

yes there is, we can check from wireshark in the right
side which packet has tcp segment

### No 10

![no10](/src/TCP-Hands-On/no10.jpg)

Jawab :

The length for each data received is 1448 bytes

### No 11

![no11](/src/TCP-Hands-On/no11.jpg)
![no11_2](/src/TCP-Hands-On/no11_2.jpg)
![no11_3](/src/TCP-Hands-On/no11_3.jpg)

Jawab :

First we find the total packet bytes which is 154kb
And then we find the start and end time for the segment which is:
Start : 09:43:26.716922000
End : 09:43:26:840555000
Then we subtract it, we get : 0.123,633,000 second

### 12 

-

### 13 

-

### 14 

-


## UDP Hands On

### No 1

![no1](/src/UDP-Hands-On/no1.jpg)
![no1_2](/src/UDP-Hands-On/no1_2.jpg)

Jawab :

Packet number : 4
Port : 443 (HTTPS)
There is 4 fields : Source Port, Destination Port, Length, Checksum

### No 2

![no2](/src/UDP-Hands-On/no2.jpg)
![no2_1](/src/UDP-Hands-On/no2_1.jpg)
![no2_2](/src/UDP-Hands-On/no2_2.jpg)
![no2_3](/src/UDP-Hands-On/no2_3.jpg)

Jawab :

2 bytes each

### No 3

![no3](/src/UDP-Hands-On/no3.jpg)

Jawab :

The length is length of header + payload which is 8 + 888 = 896

### No 4 

Jawab :

Because the length is represented with 2 bytes or 16 bit that means 
about 0 to 65,535 (2^16 - 1) can be represented as the length. As for the
UDP payload, that means 65535 - 8 = 65,527 bytes

### No 5 

Jawab :

The largest source port available is 65535 because it uses 2 bytes to represent it

### No 6 

![no6](/src/UDP-Hands-On/no6.jpg)

Jawab :

The protocol number is 17 for UDP

### No 7

![no7](/src/UDP-Hands-On/no7.jpg)
![no7_1](/src/UDP-Hands-On/no7_1.jpg)
![no7_2](/src/UDP-Hands-On/no7_2.jpg)

Jawab :

The first segment packet is number 4, the second one is 5.
The src port number for the first packet became the dst port for the second packet
and the dst port number for the first packet became the src port number for the 
second packet


