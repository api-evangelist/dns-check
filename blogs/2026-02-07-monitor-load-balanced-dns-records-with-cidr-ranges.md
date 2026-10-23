---
title: "Monitor Load Balanced DNS Records with CIDR Ranges"
url: "https://www.dnscheck.co/blog/dns-monitoring/2026/02/07/cidr-load-balancer-monitoring.html"
date: "2026-02-07"
feed_url: "https://www.dnscheck.co/blog/feed.xml"
---
DNS Check's load balancer monitoring now supports CIDR notation, making it practical to monitor domains served by CDNs and cloud providers that use large IP pools. Instead of listing every possible IP address a provider might return, you can enter CIDR ranges like 104.16.0.0/13 and DNS Check will verify that responses fall within those ranges. How Load Balancer Monitoring Works Before diving into the CIDR improvements, here's a quick overview of how DNS Check monitors load-balanced records.
