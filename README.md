# NetPractice
NetPractice is a general practical exercise to let you discover networking. 

[useful](https://github.com/lpaube/NetPractice)
[subnet mask cheat sheet](https://dnsmadeeasy.com/support/subnet)
- https://docs.netgate.com/pfsense/en/latest/network/cidr.html

- when something is being sent to a router that has to sent smoethig to a different router you can on the left give it the ips without the last number and just type 0 and then shalsh with the mask of that network and on the right the ip of the router
- when i have ips from 0 - 128 with /26 and ip from 129 - 192 with /30 i just have to go from 194 because 193 it network addr

What is IPv4?
> a 32 bit address (like house numbers for devices). It supports about 4.3billion ips. Can be form 0-255.

What is IPv6
> like ipv4 but with more available ips (~340 undectillion ips)

Difference between v6 and v4
> v6 can hold way more ips and its mre optimized and instead of 4 bytes with 42bit like v4, v6 has 128bit with 16 bytes. v4 ahs broadcasting and v6 doesnt

What is a (sub-)netmask
> lets you divide a network into host porpotions. Can be written in ip addr form like 255.255.255.0 or just /30 or something
