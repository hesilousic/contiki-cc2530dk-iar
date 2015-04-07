#Contiki 2.7 port for CC2530DK IAR

This is a proof of concept to build Contiki 2.7 with IAR EW8051 9.1. The main reason to use IAR is debug ability.

This port contains the original Contiki 2.7 source + cpu/cc253x_iar + platform/cc2530dk_iar 
examples\cc2530dk\udp-ipv6\server.c: SERVER_RPL_ROOT = 1
examples\cc2530dk\udp-ipv6\client.c: destination ips are modified to let client and server able to talk to each other on my boards.

The IAR project can build 3 working examples: blink-hello, udp client, udp server. Others would work too but not included.

This port was based on https://github.com/brycel/ContikiCC2530Port
