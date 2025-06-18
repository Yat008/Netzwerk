
# 1

A:

| Header Layer 2 |        |                | Header Layer 3 |              |                | Nutzdaten |
| -------------- | ------ | -------------- | -------------- | ------------ | -------------- | --------- |
| Destination    | Source | Weitere Felder | Destination    | Source       | Weitere Felder |           |
| FA A3          | AF 8C  |                | 172.16.1.10    | 172.16.1.254 |                |           |


B:

| Header Layer 2 |        |                | Header Layer 3 |            |                | Nutzdaten |
| -------------- | ------ | -------------- | -------------- | ---------- | -------------- | --------- |
| Destination    | Source | Weitere Felder | Destination    | Source     | Weitere Felder |           |
| 8B 34          | D6 83  |                | 172.24.1.10    | 172.24.1.1 |                |           |
# 2

TCP

Transmission Control Protocol

UDP

User Datagram Protocol

# 3

Layer 4 - Transportschicht

# 4

gottlose dalwasser kreuzaufgaben

# 5

TCP | 192.168.1.111:61603 | 52.113.195.132:443 | HERGESTELLT

Bedeutung:

192.168.1.111:61603 : IP Adresse vom Source PC, verwendet Port 61603 High Port

52.113.195.132:443 : IP Adresse der Website, verwendet Port 443 HTTPS

Wie? : Mein PC ist momentan mit dieser Website verbunden

# 6

1

| Network         | Mask          | Next Hop   |
| --------------- | ------------- | ---------- |
| 10.0.0.0/8      | 255.0.0.0     | 172.16.1.1 |
| 192.168.54.0/24 | 255.255.255.0 | 172.16.1.1 |
|                 |               |            |
2

| Network         | Mask          | Next Hop   |
| --------------- | ------------- | ---------- |
| 192.168.0.0/24  | 255.255.255.0 | 172.16.0.1 |
| 192.168.54.0/24 | 255.255.255.0 | 10.1.0.1   |
|                 |               |            |
3

| Network        | Mask          | Next Hop |
| -------------- | ------------- | -------- |
| 192.168.0.0/24 | 255.255.255.0 | 10.0.0.1 |
| 172.16.0.0/16  | 255.255.0.0   | 10.0.0.1 |
|                |               |          |

# 7

tracert 172.16.1.100

Bedeutung:

192.168.1.1 : Router vom dem Netzwerk

192.168.0.1 : Router vom dem Netzwerk

146.228.17.100 : Router mit IP vom Provider

Wieso ab 4 Zeitüberschreitung?

Die IP 172.16.1.100 ist eine Private IP die er nicht im Internet finden kann, da sie dort nicht existiert

# 8

route print


# 9

