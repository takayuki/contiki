### Note on Packet Sniffer for Z1

This is a preliminary and tentative effort to maintain a packet sniffer for Z1 following the Contiki's up-to-date master branch. It's based on a previous implementation by Antonio Lignan and compatible with [sensniff](https://github.com/g-oikonomou/sensniff),

https://github.com/alignan/contiki/commits/z1_sniffer

For further discussion on a preferable, general sniffer framework which should be introduced in Contiki in future, see

Live Traffic Capture and Sniffer for cc2420
https://github.com/contiki-os/contiki/pull/1319

There is another implementation by Cedric Adjih available at Inria, which is based on Contiki 2.6, though it works for sure even with the latest revision of Z1. But it's not compatible with sensniff, and captures and forwards [ZigBee Encapsulation Protocol (ZEP)](https://www.wireshark.org/docs/dfref/z/zep.html) packets to loopback device for wireshark, instead.

http://contiki-hiper.gforge.inria.fr/README-sniffer.html

Takayuki Usui
