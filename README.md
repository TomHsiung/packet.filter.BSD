# packet.filter.BSD
The native firewall of BSD-based system

# Contents
1) `general.rules` summarizes basic syntax for packet filter.

# Control syntax
1) `pfctl -F all -f /etc/pf.conf` command flushes all NAT, filter, state, and table rules and reload /etc/pf.conf.
2) `pfctl -e` command enables packet filter.
3) `pfctl -d` command disables packet filter.
4) `pfctl -sr` command list present fliter packet rules for interface eth0.
5) `pfctl -si` command shows traffic statistics.

# Miscs
1) Usually the configuration file of packet filter locates at `/etc/pf.conf`.
