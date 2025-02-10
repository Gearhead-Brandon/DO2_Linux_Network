# Network Configuration and Testing Report

## Chapter III

This report includes the results of network-related tasks performed on virtual machines using Ubuntu 20.04 Server LTS.

## Part 1: IP Calculation (`ipcalc` tool)
- Determine network address and mask conversions.
- Identify minimum and maximum hosts for different masks.
- Check localhost accessibility with different IPs.
- Classify given IPs as public or private.
- Identify possible gateway addresses.

## Part 2: Static Routing Between Two Machines
- Configure internal network interfaces on `ws1` and `ws2`.
- Set up static routes manually and persistently.
- Verify connectivity using `ping`.

## Part 3: Network Speed Test (`iperf3` tool)
- Convert bandwidth measurements.
- Measure connection speed between `ws1` and `ws2`.

## Part 4: Network Firewall (`iptables`)
- Configure firewall rules on `ws1` and `ws2` using different strategies.
- Test network accessibility with `ping` and `nmap`.

## Part 5: Static Network Routing
- Set up a network with five virtual machines (3 workstations, 2 routers).
- Enable IP forwarding.
- Configure default and static routes.
- Use `traceroute` and `tcpdump` to analyze network paths.
- Examine ICMP protocol behavior in routing.

## Part 6: Dynamic IP Configuration (`DHCP`)
- Configure DHCP service on `r2`.
- Assign IP addresses dynamically and based on MAC addresses.
- Request IP updates and analyze DHCP options.

## Part 7: Network Address Translation (NAT)
- Set up Apache servers on `ws22` and `r1`.
- Configure firewall rules to manage traffic.
- Enable SNAT and DNAT for internal and external connectivity.
- Verify TCP connections using `telnet`.

## Part 8: SSH Tunnels
- Configure a firewall on `r2`.
- Set up local and remote SSH tunneling.
- Validate access to a web server using `telnet`.