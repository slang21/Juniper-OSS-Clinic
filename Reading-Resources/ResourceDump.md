## Innovations to support:
### [O&M: Extended ICMP for Interface Identification](https://tools.ietf.org/html/rfc5837)
### [O&M: PROBE: A utility for probing interfaces](https://tools.ietf.org/html/rfc8335)
### [Security: The TCP Authentication Option](https://tools.ietf.org/html/rfc5925)
### [IPv6: The IPv6 Compact Routing Header](https://tools.ietf.org/html/draft-bonica-6man-comp-rtg-hdr-22)
### [IPv6: The IPv6 Tunnel Payload Forwarding (TPF) Option](https://tools.ietf.org/html/draft-bonica-6man-vpn-dest-opt-12)

## Tools in which to support them:
### Wireshark
#### - [Documentation](https://www.wireshark.org/docs/wsdg_html_chunked/)
#### - [Gitlab](https://gitlab.com/wireshark/wireshark)
### TCPDUMP & LIBPCAP
### Linux
#### Alternatively, FreeBSD or OpenBSD

## Glossary:
#### [Transmission Control Protocol (TCP)](https://tools.ietf.org/html/rfc793#page-15)
#### [IPv6](https://tools.ietf.org/html/rfc8200)
#### [BGP](https://www.cloudflare.com/learning/security/glossary/what-is-bgp/)

Submitting Linux Patches
https://kernelnewbies.org/FirstKernelPatch
Tutorial that starts from basics on installing Linux kernel, updating, testing, committing, and submitting changes
Would be good to at least have one of us do this tutorial, if not all
https://opensource.com/article/18/8/first-linux-kernel-patch
Less detailed overview of process
https://www.kernel.org/doc/html/v4.10/process/submitting-patches.html
Official documentation for submitting patches, less of a tutorial
General process for submitting a patch
Describe problem
Style-check changes (https://www.kernel.org/doc/html/v4.10/process/coding-style.html#codingstyle)
Find email of maintainer of a section of code (get_maintainer.pl perl script might help)
Send the formatted patch (plain text) either through mutt or git
Wait for response
Fix recommendations
Go to 4
