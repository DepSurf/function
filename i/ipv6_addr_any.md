# Function: <code>ipv6_addr_any</code>

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
In security/lsm_audit.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv4/ping.c (ffffffff817a23ed)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b6494)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d4922)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817e0130)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
```
In net/ipv6/udp.c (ffffffff817e34c6)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_portaddr_hash
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff817e50c2)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff817f4339)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6mr.c (ffffffff817f7e46)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6_mr_forward
```
```
In net/ipv6/xfrm6_state.c (0)
Location: include/net/ipv6.h:539
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802023)
Location: include/net/ipv6.h:539
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (0)
Location: include/net/ipv6.h:539
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
In security/lsm_audit.c (ffffffff8139c5b0)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
```
In net/ipv4/ping.c (ffffffff81811690)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81823493)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/net/ipv6.h:571
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff8182fb48)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff818315a2)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81838eed)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81844c5e)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8184e7d3)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff8185080f)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/raw.c (ffffffff81854311)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff8185b539)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185ecbf)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8186394e)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81869aac)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
```
```
In net/ipv6/xfrm6_state.c (0)
Location: include/net/ipv6.h:571
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818733fc)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873bbc)
Location: include/net/ipv6.h:571
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
In security/lsm_audit.c (ffffffff813b3160)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
```
In net/ipv4/ping.c (ffffffff81842ba0)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854de3)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/net/ipv6.h:571
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff818615c8)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81863012)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8186a90d)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff818769dd)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81880726)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81882308)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/raw.c (ffffffff81886033)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff8188d439)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890d7f)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895fa9)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8189c8fc)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
```
```
In net/ipv6/xfrm6_state.c (0)
Location: include/net/ipv6.h:571
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4284)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7a3f)
Location: include/net/ipv6.h:571
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a823c)
Location: include/net/ipv6.h:571
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
In security/lsm_audit.c (ffffffff813c9fd6)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
```
In net/ipv4/ping.c (ffffffff81864131)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878951)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81885d0c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81887824)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8188ee51)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8189c14f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a67ee)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff818a8da3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/raw.c (ffffffff818ac3de)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff818b3b27)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7378)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc530)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff818c2ccc)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
```
```
In net/ipv6/xfrm6_state.c (0)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca8cb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce2ba)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff818ceae6)
Location: include/net/ipv6.h:572
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
In security/lsm_audit.c (ffffffff813f0470)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:common_lsm_audit
```
```
In net/ipv4/ping.c (ffffffff818e4277)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f92a3)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/net/ipv6.h:613
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff81906ebc)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81908ad4)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819104a1)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff8191ee17)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8192923e)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff8192b97f)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp6_portaddr_hash
```
```
In net/ipv6/raw.c (ffffffff8192edaa)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff819368a7)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a1b8)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f63c)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff819450ec)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any_parent
```
```
In net/ipv6/xfrm6_state.c (0)
Location: include/net/ipv6.h:613
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194dfe3)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8194fa83)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8195311a)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81953996)
Location: include/net/ipv6.h:613
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
In security/lsm_audit.c (ffffffff81420fd2)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1e8d)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/ping.c (ffffffff8193ab3b)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fd7f)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81953233)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff8195de90)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff8195fc75)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819678d6)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81972702)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81981566)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81983cf5)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81987a4e)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff8198f638)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993015)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81998454)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8199e408)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/xfrm6_state.c (ffffffff819a1938)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_init_temprop
  - net/ipv6/xfrm6_state.c:xfrm6_init_temprop
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a754f)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a92f5)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac822)
Location: include/net/ipv6.h:585
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad345)
Location: include/net/ipv6.h:585
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
In security/lsm_audit.c (ffffffff8143d6f0)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fb8d)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8192354a)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff8196a82b)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983402)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81987539)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff819929d4)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81994a15)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199cfb2)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff819a826c)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b7c13)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff819ba224)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff819be38a)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff819c5ef8)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c939c)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819cee1d)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff819d4f41)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/xfrm6_state.c (ffffffff819d8568)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/xfrm6_state.c:xfrm6_init_temprop
  - net/ipv6/xfrm6_state.c:xfrm6_init_temprop
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de0a6)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819dfbcf)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3366)
Location: include/net/ipv6.h:577
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3ce0)
Location: include/net/ipv6.h:577
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
In security/lsm_audit.c (ffffffff8146b2b1)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff8198249c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985efa)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff819d14ce)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819d35be)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ed23a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff819f130f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff819fe2f0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81a005c5)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a09194)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81a15476)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a26683)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81a293a2)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a2d674)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a34d46)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37eea)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a3db0a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a43d9d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cc19)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e7b3)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a520b1)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52b97)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff81485091)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8d0f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc70a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81a0802e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a0a12e)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2424a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a281df)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff81a34ee0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81a37195)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a3fe44)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81a4c046)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a5d103)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81a5ff00)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a641e7)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a6b896)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6ea2a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7477a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a98d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a837e9)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a85443)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88cb4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a89777)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff814db22a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3816)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa718a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81af7e0b)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81afac18)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f412)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1aa8c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81b29d70)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c6c5)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b3e712)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81b45b96)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b54ce3)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81b58a09)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81b5cc5f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5ec56)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b647cf)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67644)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6e93a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81b7623d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e5de)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fe07)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83d00)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84a89)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
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
In security/lsm_audit.c (ffffffff814f86be)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aade56)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab181a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81b04d2c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81b09324)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d702)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2923c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81b386b0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b0d5)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b4d2a2)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81b54536)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b63303)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81b6703e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff81b6b498)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b6d3c8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b72f5f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75e44)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b7d3e6)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81b84fcd)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d604)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f087)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93560)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b943e9)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
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
In security/lsm_audit.c (ffffffff814ff42c)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98e1b)
Location: include/net/ipv6.h:636
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ca8a)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81af058c)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81af4734)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b042)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16e7c)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81b26397)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81b28ef5)
Location: include/net/ipv6.h:636
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b31fcd)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81b41c96)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b5162a)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81b55214)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81b597dd)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5b72f)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b61c20)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64878)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81b6bfca)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81b73c7d)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c4b4)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e867)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82680)
Location: include/net/ipv6.h:636
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b834b4)
Location: include/net/ipv6.h:636
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In security/lsm_audit.c (ffffffff8155a489)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b542e0)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b587ba)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81bb11e9)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81bb4f34)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcded3)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb22c)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81becf50)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0035)
Location: include/net/ipv6.h:639
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf809d)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81c099c6)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81c18a8a)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81c1dced)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81c20e06)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81c22e3a)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c296d0)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ca78)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81c33e63)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e2a4)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c473b4)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a1c7)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e750)
Location: include/net/ipv6.h:639
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f584)
Location: include/net/ipv6.h:639
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In security/lsm_audit.c (ffffffff815f51d7)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2455)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce6990)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81d4479e)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81d489ec)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d63fbd)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81d71fa1)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81d85635)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81d886c5)
Location: include/net/ipv6.h:693
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d9144d)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81da4b97)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81db4c3d)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_ns_create
```
```
In net/ipv6/udp.c (ffffffff81db9f45)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81dbdbcf)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81dbfbe0)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc6b4f)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9e1c)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81dd1706)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc934)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de672b)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de9c22)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def050)
Location: include/net/ipv6.h:693
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81deffb7)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/mptcp/sockopt.c (ffffffff81e33b05)
Location: include/net/ipv6.h:693
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
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
In security/lsm_audit.c (ffffffff816a5ca7)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3390)
Location: include/net/ipv6.h:726
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d4f)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa300)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81f0d83e)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81f11fac)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2ed2d)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3dba1)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81f530e5)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81f564a5)
Location: include/net/ipv6.h:726
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5fbad)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81f74047)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81f8482d)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_ns_create
```
```
In net/ipv6/udp.c (ffffffff81f89ff5)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81f8e0de)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81f9032f)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f977af)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ae17)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81fa2d26)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81fad9ee)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb871e)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd372)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc30f0)
Location: include/net/ipv6.h:726
Inline: True
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc40d7)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/mptcp/sockopt.c (ffffffff8200bc25)
Location: include/net/ipv6.h:726
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
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
In security/lsm_audit.c (ffffffff816de68d)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/ethernet/microchip/vcap/vcap_tc.c (ffffffff81c5efd4)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
```
```
In net/ethtool/ioctl.c (ffffffff81ed4dbb)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02ae7)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_match_addr_any
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_match_addr_any
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f044c0)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08b21)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81f6d4db)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff81f71c9c)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f637)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d35d)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2ab4)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5e85)
Location: include/net/ipv6.h:727
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbf8dd)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff81fd4127)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81fe4b79)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_ns_create
```
```
In net/ipv6/udp.c (ffffffff81fe9949)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81fee8b9)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81ff0c68)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff816d)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc217)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820035d7)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8200e19e)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82018e8e)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_local.c (ffffffff8201e692)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820249d0)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff820250f7)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/mptcp/sockopt.c (ffffffff82087e4c)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
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
In security/lsm_audit.c (ffffffff8171b251)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/ethernet/microchip/vcap/vcap_tc.c (ffffffff81d15965)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
```
```
In net/ethtool/ioctl.c (ffffffff81f98878)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5c90)
Location: include/net/ipv6.h:727
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc87e6)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccec8)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff82033c2b)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/nexthop.c (ffffffff820383ac)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:fib6_check_nh_list
  - net/ipv4/nexthop.c:fib6_check_nexthop
```
```
In net/ipv4/tcp_ao.c (ffffffff82055657)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d397)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff8206a6bd)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffff8208026e)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff82083555)
Location: include/net/ipv6.h:727
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208cd7d)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/route.c (ffffffff820a1a39)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff820b2a89)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_ns_create
```
```
In net/ipv6/udp.c (ffffffff820b7ace)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff820bc48d)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff820be855)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c5dbd)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c952c)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff820d23ae)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff820dcd2e)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e7e5e)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_local.c (ffffffff820ed7c2)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3cc1)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f43d7)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
```
In net/mptcp/sockopt.c (ffffffff8215d89c)
Location: include/net/ipv6.h:727
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_get_sub_addrs
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
In security/lsm_audit.c (ffff800010577648)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a288)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6e824)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffff800010cc1268)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffff800010cc3590)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce1290)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5a38)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffff800010cf599c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffff800010cf9d2c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffff800010d010d4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffff800010d11550)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d22368)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffff800010d25668)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffff800010d2a118)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffff800010d33134)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37370)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffff800010d3d144)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffff800010d44458)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f584)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d514b0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d559d8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffff800010d5655c)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (c072a374)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (c0d796ac)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (c0d7d3bc)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (c0dccfcc)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (c0dcf520)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
```
```
In net/xfrm/xfrm_policy.c (c0dea5a8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (c0deeb54)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (c0dfc3d8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (c0dfe628)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c0e08bf4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (c0e1596c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c0e27bb8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (c0e28ab8)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (c0e2e080)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (c0e35eb0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (c0e3960c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c0e403dc)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (c0e46b9c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (c0e502d4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e5206c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (c0e55fa0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (c0e56b50)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (c0000000006e0ae0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f6a0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (c000000000d74940)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (c000000000ddc514)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (c000000000ddf198)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000e03ae4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_pol_inexact_addr_use_any_list
```
```
In net/xfrm/xfrm_state.c (c000000000e09338)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (c000000000e1bbd0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (c000000000e1eb5c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c000000000e2af6c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (c000000000e3a9ec)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c000000000e51e00)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (c000000000e54fe4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (c000000000e5b18c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (c000000000e65770)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69ae0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (c000000000e71320)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (c000000000e7a9ec)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86774)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e895d0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e984)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f7b0)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffe0003c9b82)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d002e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d3734)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffe000816250)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffe0008188a6)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fdc2)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_pol_inexact_addr_use_any_list
```
```
In net/xfrm/xfrm_state.c (ffffffe00083450e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
  - net/xfrm/xfrm_state.c:xfrm_init_tempstate
```
```
In net/ipv6/af_inet6.c (ffffffe00084132c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffe00084323a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffe00084b03e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffe0008561fa)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_nh_lookup_table
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000863f58)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffe00086607c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffe00086a92a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffe00087155a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000874718)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffe00087997c)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffe000880316)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887b0a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe0008896d2)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d166)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088ddce)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff8147d671)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958b7f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c57a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff819a7dce)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff819a9ece)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c38da)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff819c786f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff819d4570)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff819d6825)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819df4d4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff819eb6d6)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819fc793)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff819ff590)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a03877)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a0af26)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e0ba)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a13e0a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a01d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22e79)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a24ad3)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28344)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28e07)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff8146e091)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/vxlan.c (ffffffff8176dd1d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:__vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191266f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8191606a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff8196188e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff8196398e)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819806ca)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff8198465f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff81991330)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff819935e5)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199c294)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff819a8496)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b9553)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff819bc350)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff819c0637)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff819c7ce6)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cae7a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff819d0bca)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff819d6ddd)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfc39)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e1893)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5104)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5ff7)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff81479711)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c334f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6d4a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81a1266e)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a1476e)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2e35a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a322ef)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff81a3eff0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81a412a5)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a49f54)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81a56156)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a67213)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81a6a010)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a6e2f7)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a759a6)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78b3a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a7e88a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a84a9d)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d8f9)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f553)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93ef4)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a949b7)
Location: include/net/ipv6.h:635
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
In security/lsm_audit.c (ffffffff814911c1)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd01f)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d089a)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_rcv_saddr_any
```
```
In net/ipv4/ping.c (ffffffff81a1d076)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_lookup
```
```
In net/ipv4/nexthop.c (ffffffff81a1f17e)
Location: include/net/ipv6.h:635
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39b51)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3dbef)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/af_inet6.c (ffffffff81a4aab0)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_getname
```
```
In net/ipv6/ip6_output.c (ffffffff81a4ce95)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a55e94)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/route.c (ffffffff81a6218b)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a737f3)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_ns
```
```
In net/ipv6/udp.c (ffffffff81a76620)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp_v6_rehash
  - net/ipv6/udp.c:udp_v6_get_port
  - net/ipv6/udp.c:udp_v6_get_port
```
```
In net/ipv6/raw.c (ffffffff81a7a890)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a820d2)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a852ca)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81a8b13b)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81a913ed)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a603)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c2d3)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0044)
Location: include/net/ipv6.h:635
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0b17)
Location: include/net/ipv6.h:635
Inline: True
```
</details>
</li>
</ul>

## Differences
