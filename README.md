# linux-router
Linux BGP Router

This is a repository for a scalable linux router. The point of this router is to do fast bgp routing, use standards, forward packets as fast as possible, be very scalable, and to do it with as little complexity as possible. These routers use bgp4/4+ standards and a pure ipv6 backbone for both IPv4 and IPv6 routing and forwarding. 

The router uses frr for bgp, sriov for 100g network, and currently is built on ubuntu 24.04. The configuration could easily run on other disturbutions. I have run it on various suse verions, several ubuntu versions, and some redhat varieties.
