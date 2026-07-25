# Neptune's Privacy Utils v3.0.10 (stable) #

[!] Junk of Bash based scripts that can provide anonymity to anyone by applying many well known extreme linux privacy concepts as: Tor/i2p networks proxy, Anonymous DNS(via socks5, tor), nftables firewall rules, sysctl calls(like full no ipv6, no respond to pings) and MAC Address spoofing, all these include a boot automation.

### [WARNINGS] ###
- 1. Neptune is a personal project coded by gmasterone@duck.com, if you will use it you have to know that developer wont answer in case of any issue occurs in your machine(perhaps, issues are not common, in fact, they are very weird).

- 2. Fakeroot/containers: Have problems with firewall rules and causes DNS resolution imposible if is not via explicit socks5/tor only params !!.

- 3. Neptune wont run on Termux/ISH or something like this, at least not in the way you might think.

# [ Requeriments ] # 
- 3. Required PKGs: Bash, all other can be managed by any of the scripts.
- 4. Extra: Full root access(as i said before, to apply firewall with no issues and full sys DNS).

# [ Clone ] #
- As root: git clone https://github.com/sleuth3301/neptune && cd neptune && chmod +x * && ./make_it_work
