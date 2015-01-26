PacketFu Examples
=================

Set of examples to use the packetfu rubygem.

Description
===========

* arp-poisoning: PoC to implement a DNS poisoning
* stats-per-host: Analize pcap files and print reports per destination
  host

arp-poisoining usage
====================

$ sudo arp-poisoning eth0 yourip

stats-per-host usage
====================

$ stats-per-host pcap-examples/hbot.pcap

$ stats-per-host pcap-examples/slammer.pcap
