# packet.filter.BSD
The native firewall of BSD-based system

# Contents
1) `general.rules` summarizes basic syntax for packet filter.

# Control syntax
1) `pfctl -F all -f /etc/pf.conf` command flushes all NAT, filter, state, and table rules and reload /etc/pf.conf.
2) `pfctl -e` command enables packet filter.
3) `pfctl -d` command disables packet filter.
4) `pfctl -s -i eth0` command list present fliter packet rules for interface eth0.
