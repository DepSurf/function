# Function: <code>ipv6_addr_is_multicast</code>

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
In net/ipv6/anycast.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817dec7a)
Location: include/net/ipv6.h:612
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/udp.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/raw.c (ffffffff817e5090)
Location: include/net/ipv6.h:612
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/ping.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/ipv6.h:612
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/ipv6.h:612
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
In net/ipv6/anycast.c (ffffffff81830ef9)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81831d53)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8183595b)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8183cc51)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81845fa0)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff8184e493)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818508bb)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81854392)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81856901)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185a1b0)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff8186152b)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81862617)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818636b8)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8186a457)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81862969)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81863cd3)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8186748b)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8186e711)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81877d00)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff818803e3)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff8188270a)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818860b4)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81888703)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188c100)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81893478)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818946a8)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81895cd2)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8189d2a7)
Location: include/net/ipv6.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff818870fb)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81889295)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8188bbe8)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff818934cd)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81898ce6)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff818a6483)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818a8fe4)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818ac43d)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff818aee05)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b27b2)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff818b98f4)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818baa89)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff818bc261)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff818c37c2)
Location: include/net/ipv6.h:645
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff8190832b)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819096e0)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff8190ced3)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff819147b3)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81919fe6)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81928eb3)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff8192bdf8)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff8192ee04)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81931b08)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81935512)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff8193c874)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8193da99)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff8193f33a)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81946a64)
Location: include/net/ipv6.h:686
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff8195f51a)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819609f6)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819642be)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8196bb8b)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff819720c8)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81981227)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819842ba)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81987aa9)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff8198a5c2)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198e68d)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff819958e6)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819969b1)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81998114)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8199efdc)
Location: include/net/ipv6.h:674
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff8199416a)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81996cf6)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81999b8c)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819a160b)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff819a7820)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff819b78e4)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819ba7f0)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff819be3e9)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c0e5c)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4f3d)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff819cc1c8)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819cd2ab)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819ceaa4)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff819d5afc)
Location: include/net/ipv6.h:666
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff819ffc6a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a00af6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05ac8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a0d802)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81a13e77)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81a26332)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a298c7)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a2d6cc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a2f9d7)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a33dbd)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81a3aca8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c373)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a3d75b)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a44bb6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81a3684a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a376c6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c63c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a444e2)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81a4aa67)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81a5cdb2)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a60423)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a6423f)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a66527)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6a90d)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81a71928)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a72ff3)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a743c4)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b7a6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81b2b9ca)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d201)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b31cdc)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b3ad04)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81b44fc5)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81b54983)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b58f72)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5ccb5)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5ef26)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b6384b)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81b6b21b)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d47a)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6df0b)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
```
```
In net/ipv6/ip6mr.c (ffffffff81b7667f)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81b3a3ea)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc11)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b408dc)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b49a04)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81b53945)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81b61a55)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b675af)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b6b4f5)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b6d6b6)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b71ffb)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81b79c9b)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bf2a)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b7c98b)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_flow_key_init
```
```
In net/ipv6/ip6mr.c (ffffffff81b85444)
Location: include/net/ipv6.h:729
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81b280ca)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2956b)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e174)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b37608)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81b40f07)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81b4fcb5)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b55789)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81b5983a)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5ba51)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b60d3a)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81b687c8)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6aa0e)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81b6bc5f)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81b73fb4)
Location: include/net/ipv6.h:730
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81bee024)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81beefaa)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4461)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81bfdde8)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81c08bd7)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81c17015)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81c1e262)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81c20e63)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81c23156)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c2870a)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81c30492)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81c3286e)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81c33ad2)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e863)
Location: include/net/ipv6.h:733
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81d86582)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81d87677)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d181)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81d977a4)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81da3892)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81db2da5)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81dba8f5)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81dbdc26)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81dc0058)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc5ab9)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81dcdee0)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0063)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81dd135a)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd012)
Location: include/net/ipv6.h:787
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81f540e2)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81f553f7)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b278)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81f663f4)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81f72cd2)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81f825d5)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81f8a9f8)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81f8e138)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81f907c8)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f9668f)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81f9ef73)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81fa13f3)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff81fa2955)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81fae49c)
Location: include/net/ipv6.h:820
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81fb3ace)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4e7d)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb014)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81fc6504)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81fd2dc8)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81fe28e5)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81fea307)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81fee916)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81ff1029)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff7060)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81fffab7)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff82001c93)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff820031f8)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8200f91c)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff8208137e)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff82082515)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff82088424)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff82093af4)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff820a06d8)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff820b0805)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_is_multicast
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff820b80c3)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff820bc4ea)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff820bec09)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c4ca0)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff820ce8ad)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff820d0a93)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ip6_tlvopt_unknown
```
```
In net/ipv6/datagram.c (ffffffff820d1fc6)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff820de8ac)
Location: include/net/ipv6.h:817
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffff800010cf7484)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffff800010cfa2c4)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffff800010cfd96c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffff800010d068bc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffff800010d0db38)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffff800010d22060)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffff800010d2589c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffff800010d2a164)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffff800010d2c48c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d31ec8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffff800010d3a378)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3bac0)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffff800010d3ce48)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffff800010d45328)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (c0dfdb0c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c0dff3d8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e05130)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c0e0d458)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (c0e143dc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (c0e27d0c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (c0e2910c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c0e2e118)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c0e3030c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e34d8c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (c0e3c8ac)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3e560)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c0e3ffd4)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (c0e47ee0)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (c000000000e1dd60)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c000000000e1f288)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c000000000e25a20)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c000000000e30aec)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (c000000000e39954)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (c000000000e519bc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (c000000000e55304)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c000000000e5b1f0)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c000000000e5dd9c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e6416c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (c000000000e6d5b8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c000000000e6f3c0)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (c000000000e70e80)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (c000000000e7ae3c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffe000842874)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffe000843c9e)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffe000847e24)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffe00084ea4a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffe0008557cc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffe000863d12)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000866302)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffe00086a99e)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffe00086c712)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe000870770)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffe00087701c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe00087855e)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffe0008796b8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffe000880632)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff819d5eda)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819d6d56)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff819dbccc)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819e3b72)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff819ea0f7)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff819fc442)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819ffab3)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a038cf)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a05bb7)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a09f9d)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81a10fb8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a12683)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a13a54)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a1ae36)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In drivers/net/vxlan.c (ffffffff8176ba2f)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_open
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/ipv6/anycast.c (ffffffff81992c9a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81993b16)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81998a8c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff819a0932)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff819a6eb7)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff819b9202)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819bc873)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff819c068f)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c2977)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c6d5d)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff819cdd78)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819cf443)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff819d0814)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff819d7bf6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81a4095a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a417d6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a4674c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a4e5f2)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81a54b77)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81a66ec2)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a6a533)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a6e34f)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a70637)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a74a1d)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81a7ba38)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d103)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a7e4d4)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a858b6)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv6/anycast.c (ffffffff81a4c55a)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d436)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (ffffffff81a5247c)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffff81a5a592)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_del
```
```
In net/ipv6/route.c (ffffffff81a60b67)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_confirm_neigh
```
```
In net/ipv6/ndisc.c (ffffffff81a734a2)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a76b50)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff81a7a8e8)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a7cc57)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a810df)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/ping.c (ffffffff81a88288)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a89953)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/datagram.c (ffffffff81a8ad75)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a92323)
Location: include/net/ipv6.h:724
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
</details>
</li>
</ul>

## Differences
