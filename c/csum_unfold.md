# Function: <code>csum_unfold</code>

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
In net/core/utils.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/core/filter.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv4/inet_lro.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/mcast_snoop.c (0)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff8179a47b)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8179c884)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp.c (ffffffff817f392a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff817f870d)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81852aa6)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81855034)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856e2d)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8186040c)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81866d41)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff8186d867)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff81871837)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872bb3)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873909)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff817c821b)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff817cbb24)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp.c (ffffffff8182471a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff818295bc)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff818847a6)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81886da4)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888c2d)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189239c)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81899441)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff818a0667)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff818a5d97)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a71d3)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a7f89)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff817e6b7b)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff817eac04)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp.c (ffffffff81845431)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8184a5ca)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff818aaf77)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818ad29e)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff818af2bf)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b89fb)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff818bf763)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff818c6cab)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff818cc7f7)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdc49)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ce7e5)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff81861abb)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff81866e10)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp.c (ffffffff818c4ec1)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff818ca26f)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff8192daf4)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff8192feae)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81931fcf)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b8ad)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81942833)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff8194a16b)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff819515a7)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952a49)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953695)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff818ad6e6)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818b67b1)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp.c (ffffffff8191ab49)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8192059e)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81984e62)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8198858d)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198aa98)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994b36)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff8199b5fd)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/netfilter.c (ffffffff819a314a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_checksum.c (ffffffff819aab2f)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abff5)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad0a2)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff818d1946)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818db9c3)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff8190eab2)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81949309)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8194f3d7)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff819bb5eb)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bef0f)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c135a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb427)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d2015)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e161f)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2bd2)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3a4f)
Location: include/net/checksum.h:111
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
In net/core/utils.c (ffffffff8191ebd6)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff81928e55)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81970675)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff819ad95b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819b3c0d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81a2a1dd)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2de0b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a3012e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39e81)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a40df4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a503de)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5191e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a527bb)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff81950e4d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8195b535)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff819a7065)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff819e460b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819ea93d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81a60d2d)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a64976)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a66c7e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70a11)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a77a74)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a86ffe)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8851e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a8939b)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff81a21d6a)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a2f9c5)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81a903c5)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81ad30bb)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8557)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81b59c81)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81b5b9e3)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5f6ae)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a18f)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b71cea)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b822ae)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83abf)
Location: include/net/checksum.h:101
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8482b)
Location: include/net/checksum.h:101
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
In net/core/utils.c (ffffffff81a220ea)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a32295)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81a9a295)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81adf4fb)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ae454c)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81b682e1)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81b6a227)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b6de4e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78c70)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b80a1f)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b9199e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93177)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b9418b)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff81a0942a)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a193f5)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81a85588)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81aca40f)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81acf88f)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81b565ed)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81b58557)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81b5c1d1)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b677c2)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f63f)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81b80bf2)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82210)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8329b)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff81abb90a)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81aca1a5)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81b3fc78)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81b88cef)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e2af)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81c1cfbd)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81c1f8e7)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81c23938)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f3f2)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81c376fc)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81c4cc12)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e2c0)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f36b)
Location: include/net/checksum.h:109
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c778fe)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c80e6e)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c850c5)
Location: include/net/checksum.h:109
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/utils.c (ffffffff81c362db)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81c46d0c)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81ccc4a9)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81d1a053)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f4bf)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81db989a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81dbc511)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0860)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc844)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81dd52fe)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81ded068)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeb72)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defd7f)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1cb6e)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e2686a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e2b1d0)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/utils.c (ffffffff81de99ab)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81dfb24c)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81e8c3a9)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff81ee0cc3)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81ee667f)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81f8991a)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81f8d7e5)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81f90fe6)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d983)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a07)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81fc0e68)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2bc2)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3e8f)
Location: include/net/checksum.h:111
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff3ffe)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffdfa0)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82003380)
Location: include/net/checksum.h:111
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/utils.c (ffffffff81e5b1ba)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81e6cfdd)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81eea4ba)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39bcd)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff81f405f2)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff81f45ebf)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81fe89eb)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81fedd1e)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81ff18d6)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe403)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820071e0)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff82021df7)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023b51)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024eaf)
Location: include/net/checksum.h:113
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8207060e)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8207a184)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207f510)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/utils.c (ffffffff81f1a57a)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81f2c84d)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81fae26a)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffcbd)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp.c (ffffffff82006242)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8200bfff)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff820b754b)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff820bb92e)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff820bf4d5)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd2e5)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d6040)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff820f0f17)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2cb1)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f418f)
Location: include/net/checksum.h:113
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8214456e)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214f5e4)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82154a03)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/utils.c (ffff800010bf2a7c)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffff800010bfc524)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffff800010c56ae4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffff800010c9905c)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffff800010ca04fc)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffff800010d269b0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d2a7d0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffff800010d2cbcc)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38eec)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffff800010d410b0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffff800010d5375c)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d550c4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d561b8)
Location: include/net/checksum.h:107
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
In net/core/utils.c (c0d0b2b4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (c0d17320)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv4/udp.c (c0da7000)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c0dad750)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (c0e2e7c8)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/icmp.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/ip6_checksum.c (c0e54044)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/mcast_snoop.c (0)
Location: include/net/checksum.h:107
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
In net/core/utils.c (c000000000cd86b0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (c000000000ce4e00)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (c000000000d576f0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (c000000000daaa60)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (c000000000db2c80)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (c000000000e56718)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5b9cc)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c000000000e5e698)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c3c0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (c000000000e759a8)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (c000000000e8bf4c)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8ddf4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f314)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffe0007744b0)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffe000779238)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffe0007c0ada)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffe0007f8b00)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcbc8)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffe000867136)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086af36)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffe00086ce34)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008762c2)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffe00087c810)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffe00088b464)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c906)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088da5e)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff818f0e1d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818fb505)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81946ed5)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff8198447b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8198a7ad)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81a003bd)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a04006)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a0630e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a100a1)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a17104)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a2668e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27bae)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28a2b)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff818aac5d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff818b5335)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff819009c5)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff8193df3b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff8194426d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff819bd17d)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c0dc6)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff819c30ce)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cce61)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff819d3ec4)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff819e344e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e496e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5c1b)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff81941e4d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8194c535)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff81998065)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff819eec4b)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819f4f7d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81a6ae3d)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6ea86)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a70d8e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7ab21)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a81b84)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9223e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9375e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a945db)
Location: include/net/checksum.h:107
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
In net/core/utils.c (ffffffff8196374d)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (ffffffff8196def5)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/netfilter/utils.c (ffffffff819bad45)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/udp.c (ffffffff819f8dbb)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_csum
```
```
In net/ipv4/udp_offload.c (ffffffff819ff17e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv6/udp.c (ffffffff81a7744d)
Location: include/net/checksum.h:107
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7b0bb)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81a7d39e)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87361)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e484)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_checksum.c (ffffffff81a9e2ee)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f8ae)
Location: include/net/checksum.h:107
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa073b)
Location: include/net/checksum.h:107
Inline: True
```
</details>
</li>
</ul>

## Differences
