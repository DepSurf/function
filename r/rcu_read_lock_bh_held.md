# Function: <code>rcu_read_lock_bh_held</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:521
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:530
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:271
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:269
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:285
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:291
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:293
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:351
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:327
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:328
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/vxlan.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_tunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_udp_tunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:236
Inline: True
```
</details>
</li>
</ul>

## Differences
