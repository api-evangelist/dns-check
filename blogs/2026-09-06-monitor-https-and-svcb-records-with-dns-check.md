---
title: "Monitor HTTPS and SVCB Records with DNS Check"
url: "https://www.dnscheck.co/blog/dns-monitoring/2026/09/06/https-and-svcb-record-monitoring.html"
date: "2026-09-06"
feed_url: "https://www.dnscheck.co/blog/feed.xml"
---
DNS Check now supports monitoring HTTPS records and SVCB records , DNS record types 65 and 64, both standardized in RFC 9460 . They tell a client how to connect to a service rather than only where it is: which HTTP versions the endpoint speaks, which port it listens on, which addresses it can start connecting to, and which keys it needs for Encrypted ClientHello, all before it opens a connection. SRV records have carried a target and a port since 2000, but they say nothing about the transport, and browsers never adopted them for HTTP.
