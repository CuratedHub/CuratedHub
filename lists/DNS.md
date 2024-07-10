# DNS  
The following will provide practical solutions to infringement of privacy based on your DNS queries, such as [DefecTor attacks](https://nymity.ch/tor-dns/tor-dns.pdf), which can be used by enterprise agents such as Google or governments to figure out who you are, even over Tor. This is why for your daily driver devices, we recommend the simple solution of using Unbound + DNSCrypt anonymized relays. This will provide high performance, security, and privacy. 

Anonymizing your DNS does not hide your traffic from your ISP. But it works in conjunction with your proxy/VPN/Tor to make those services more secure. 
You should note, however, that by using a DNSCrypt proxy, you are placing trust there rather than you ISP. You could get a VPS and set up your own 
anonymizing relay, but that is too much work for most people. Instead, we recommend using many different relays, chosen with a random weight. 

## Unbound  
[Unbound](https://nlnetlabs.nl/projects/unbound/about/) is a A validating, recursive, and caching DNS resolver. A DNS resolver is a specific type of DNS server responsible for translating domain names into internet protocol (IP) addresses. It receives a hostname, such as www.example.com, and is responsible for tracking down the IP address for that hostname.  
- A **validating** DNS resolver checks the authenticity of DNS records using DNSSEC (Domain Name System Security Extensions).  
- A **recursive** DNS resolver is responsible for resolving DNS queries by recursively following the chain of DNS records until it finds the requested IP address for a given domain name.  
- A **caching** DNS resolver stores DNS records in a cache to reduce the need for repeated queries to upstream DNS servers. This can significantly improve DNS query performance, as the resolver can quickly return cached DNS data for frequently queried domains.

Unbound is a DNS resolver that provides a secure and efficient way to resolve domain names. It reduces reliance of some trust that can't be checked with third-party services such as Cloudflare (1.1.1.1). It can be installed on a server or client easily (service directly on Windows, docker, WSL, virtualization, linux, raspberry pi, etc). 

Unbound has the added benefit of being able to circumvent some network policies, such as VPN blocks set up by your work network admin. 



### Instructions to install Unbound on Windows 10/11 as a service  
1. Download the latest [.zip binaries](https://www.nlnetlabs.nl/projects/unbound/download/). The .exe is currently not working on 1.20, but binaries work as a portable app on Windows.  
2. Unzip and copy contents into C:\Program Files\Unbound  
3. Create a file called unbound.conf and place in \Unbound  
4. Open unbound.conf with text editor and copy this [configuration](https://github.com/CuratedHub/CuratedHub/blob/main/lists/docs/unbound.conf), and change to your liking.  
5. Search for change adapter options (Control Panel\Network and Internet\Network Connections)  
     Right click the adapter you want to use (like wi-fi), and click properties  
     Go to Internet Protocol Version 4 (TCP/IPV4) and click properties  
     Change preferred DNS Server to 127.0.0.1  
6. Go back to programfiles/unbound and open the .exe to start server and program.

The unbound.conf has information on how to check if it is currently running at the top.   
If you use a port other than 53, you may need to unblock it in your firewall.  





## Anonyzmized DNS - DNSCrypt2   
A DNS proxy is a type of DNS resolver that acts as an intermediary between the client application and the upstream DNS servers. DNS proxies can provide additional security, privacy, and performance benefits, as they can cache DNS records, validate DNS data, and filter out potentially malicious DNS queries.  

The [DNSCrypt 2 Protocol](https://github.com/DNSCrypt/dnscrypt-proxy/wiki/Anonymized-DNS) can make it so the DNS resolver "receives a connection from the relay, not from the actual client. So the only IP address it knows about is the IP of the relay, making it impossible to map queries to clients." This is an alternative to using [DNS over Tor](https://developers.cloudflare.com/1.1.1.1/other-ways-to-use-1.1.1.1/dns-over-tor/) that provides much faster performance times.  
[dnscrypt-proxy-2](https://github.com/DNSCrypt/dnscrypt-proxy)  
[SimpleDnsCrypt](https://github.com/instantsc/SimpleDnsCrypt)  
[SecureDNS](https://github.com/Texnomic/SecureDNS)  
[Encrypted DNS Server](https://github.com/DNSCrypt/encrypted-dns-server)  
[YogaDNS](https://yogadns.com/) (not open-source)  

### ECH with DNSCrypt
Hopefully in the future, [ECH](https://support.mozilla.org/en-US/kb/faq-encrypted-client-hello) will be widespread. [Implement it through DNSCrypt](https://github.com/DNSCrypt/dnscrypt-proxy/wiki/Local-DoH). 


## Android
[ReThink DNS](https://github.com/celzero/rethink-app) (provides DNS-over-Tor and WireGuard)   


List of anonymized relays: https://dnscrypt.info/public-servers/ 
