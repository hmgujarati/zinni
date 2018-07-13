### Qos ###

This is a Linux bash script that will set up tc to limit the outgoing bandwidth for connections to the Bitcoin network. It limits outbound TCP traffic with a source or destination port of 15877, but not if the destination IP is within a LAN (defined as 192.168.x.x).

This means one can have an always-on zinnid instance running, and another local zinnid/zinni-qt instance which connects to this node and receives blocks from it.
