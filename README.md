changes:
1. add mininum TTL config for cache dns . 
   add new config: min-ttl
   When there is many clients concurrent request to the DNS cache, the TTL of domain name may count down to 0, and this may cause the clients to send a dns query for each app request. set the mininum ttl may be helpful.
   ref:http://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2005q2/000251.html



