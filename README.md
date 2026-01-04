# linux-router
Linux BGP Router

This is a repository for a scalable linux router. The point of this router is to do fast bgp routing, use standards, forward packets as fast as possible, be very scalable, and to do it with as little complexity as possible.

- Virtual Machine - Recommended 8cpu / 16gb ram / 40gb hdd
- Ubuntu 24.04.3 - https://cloud-images.ubuntu.com/noble/current/noble-server-cloudimg-amd64.img
- Mellanox Connectx4/5/6/7 setup on host with sriov
- Virtual Platform of you liking - Ours is built in Harvester and Rancher.

https://harvesterhci.io/

Over the last 2 years, we have transitioned our networks AS40805 and AS33000 to a fully resilient open source routing platform runing 100% virtually and supporting multi-100g throughput. The platform described here is built 100% on standards with fully open packages that are supported long term. These routers use BGP4+ standards, and use IPv6 for the backbone and all peering.

They scale efficiently and effectively by adding more nodes to each cluster or zone. Each node adds exponentially greater resilience and throughput utilizing multipath and ecmp for fast routing and forwarding. We use BFD for fast failures, and utilize FRR for BGP and route management.

 These routers use bgp4/4+ standards and a pure ipv6 backbone for both IPv4 and IPv6 routing and forwarding. 

The router uses frr for bgp, sriov for 100g network, and currently is built on ubuntu 24.04. The configuration could easily run on other disturbutions. I have run it on various suse verions, several ubuntu versions, and some redhat varieties.
