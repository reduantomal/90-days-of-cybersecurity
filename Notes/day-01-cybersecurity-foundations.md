# Day 01 - Cybersecurity Foundations

## What is Cybersecurity?
Cybersecurity protects systems, networks, applications and data
from unauthorized access, damage and disruption.

## CIA Triad

### Confidentiality
Only authorized users can access information.

### Integrity
Information remains accurate and is not modified without authorization.

### Availability
Systems and information remain accessible when needed.

## Important Terminology
Asset: The server and its customer database.
Vulnerability: The software contains a known security weakness.
Threat: An attacker may try to exploit it.
Exploit: The attacker uses a technique to take advantage of the weakness.
Risk: Customer data could be stolen or modified.
Control: Patch the software, restrict network access and monitor logs.


## My Kali Linux Environment
- Distribution: Kali GNU/Linux
- Kernel: Linux
- Architecture:  x86_64
- CPU:13th Gen Intel(R) Core(TM) i7-13620H 
- RAM: 15 Gi
- Available Storage:189 G
- Network Interfaces: Wlan0

## Running Services and Listening Ports
Netid  State   Recv-Q  Send-Q        Local Address:Port      Peer Address:Port  
udp    UNCONN  0       0                   0.0.0.0:40978          0.0.0.0:*     
udp    UNCONN  0       0               224.0.0.251:5353           0.0.0.0:*     
udp    UNCONN  0       0               224.0.0.251:5353           0.0.0.0:*     
udp    UNCONN  0       0               224.0.0.251:5353           0.0.0.0:*     
udp    UNCONN  0       0                   0.0.0.0:5353           0.0.0.0:*     
udp    UNCONN  0       0                         *:47523                *:*     
udp    UNCONN  0       960                       *:41544                *:*     
udp    UNCONN  0       0                         *:42445                *:*     
udp    UNCONN  0       0                         *:1716                 *:*     
udp    UNCONN  0       0                         *:60294                *:*     
udp    UNCONN  0       0                         *:52204                *:*     
udp    UNCONN  0       0                         *:5353                 *:*     
tcp    LISTEN  0       4096              127.0.0.1:20241          0.0.0.0:*     
tcp    LISTEN  0       511                 0.0.0.0:443            0.0.0.0:*     
tcp    LISTEN  0       128                 0.0.0.0:1514           0.0.0.0:*     
tcp    LISTEN  0       128                 0.0.0.0:1515           0.0.0.0:*     
tcp    LISTEN  0       4096              127.0.0.1:9050           0.0.0.0:*     
tcp    LISTEN  0       2048                0.0.0.0:55000          0.0.0.0:*     
tcp    LISTEN  0       4096     [::ffff:127.0.0.1]:9300                 *:*     
tcp    LISTEN  0       50       [::ffff:127.0.0.1]:9614                 *:*     
tcp    LISTEN  0       50                        *:1716                 *:*     
tcp    LISTEN  0       4096     [::ffff:127.0.0.1]:9200                 *:*     
tcp    LISTEN  0       2048                   [::]:55000             [::]:*     
                               


