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

# OpenBSD syntax
6) `pfctl -f  /etc/pf.conf`	Load the pf.conf file
7) `pfctl -nf /etc/pf.conf`	Parse the file, but don't load it
8) `pfctl -sr`		Show the current ruleset
9) `pfctl -ss`		Show the current state table
10) `pfctl -si`		Show filter stats and counters
11) `pfctl -sa`		# Show everything it can show

# Miscs
1) Usually the configuration file of packet filter locates at `/etc/pf.conf`.
