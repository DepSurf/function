# Function: <code>__in6_dev_get</code>

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
In net/core/neighbour.c (ffffffff817243e2)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8173869c)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff817c38f3)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_close
```
```
In net/ipv6/ip6_output.c (ffffffff817c6b03)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c8a95)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff817c9285)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff817d3196)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff817de29a)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e3f34)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff817e7c7d)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817e8fbe)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffff817ee973)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f12a0)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff817f2e7e)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff817f8050)
Location: include/net/addrconf.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/output_core.c (ffffffff818005bc)
Location: include/net/addrconf.h:262
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
In net/core/neighbour.c (ffffffff8178e2d3)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff817a498c)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff81830bfd)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81833bd2)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81835d05)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8183fdef)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff818428d3)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu
```
```
In net/ipv6/ndisc.c (ffffffff8184fa99)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818522e3)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81856d75)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81857c9c)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff8185d1b1)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860fe8)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81861cac)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8186a1b4)
Location: include/net/addrconf.h:275
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/output_core.c (ffffffff81871ccc)
Location: include/net/addrconf.h:275
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
In net/core/neighbour.c (ffffffff817bb76c)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff817d33fc)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff8186266a)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8186564c)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81867825)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81871a6f)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81874643)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu
```
```
In net/ipv6/ndisc.c (ffffffff818819b9)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818840a3)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81888b75)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81889a86)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff8188f11a)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892f18)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81893c1c)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189d004)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4e53)
Location: include/net/addrconf.h:277
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff818a622c)
Location: include/net/addrconf.h:277
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
In net/core/neighbour.c (ffffffff817d9eb2)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff817f2739)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff81886e3a)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81889e5e)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188bfb5)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff818967fb)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff818989e3)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu
```
```
In net/ipv6/ndisc.c (ffffffff818a7ad9)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff818aa85a)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff818af205)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b02b4)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff818b5626)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b9453)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff818ba0cf)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c34fc)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb893)
Location: include/net/addrconf.h:299
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff818ccc7b)
Location: include/net/addrconf.h:299
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
In net/core/neighbour.c (ffffffff81854652)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8186dcf9)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff8190805a)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8190b04f)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190d2a5)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff81917bcb)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff8191a469)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu
```
```
In net/ipv6/ndisc.c (ffffffff8192a589)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff8192d373)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81931f15)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819330c4)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff8193839c)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c3c7)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff8193d0af)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81946792)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950633)
Location: include/net/addrconf.h:298
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81951a5b)
Location: include/net/addrconf.h:298
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
In net/core/neighbour.c (ffffffff8189fca1)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff818bee47)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff8195f1d7)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8196250e)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819646af)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/addrconf.c (ffffffff8196f2eb)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81970d7f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff819827e9)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81985e2f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff8198a9dd)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198d034)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81990d1b)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994837)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff8199692d)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199fc14)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9b2c)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819aafeb)
Location: include/net/addrconf.h:334
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
In net/core/neighbour.c (ffffffff818c2671)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff818e7c40)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv6/anycast.c (ffffffff81993d67)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff8199751d)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999061)
Location: include/net/addrconf.h:342
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a4e9b)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff819a69af)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff819b8e89)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819bc420)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c12a5)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2204)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff819c7454)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb2c7)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff819cd22d)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d6899)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e064c)
Location: include/net/addrconf.h:342
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819e1b0b)
Location: include/net/addrconf.h:342
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
In net/core/neighbour.c (ffffffff819107ce)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff819375c7)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff819c73df)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff819ff816)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a03506)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a04f61)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a111ab)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81a1487b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff81a278f9)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a2af4c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a3006e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31007)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a35d8a)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39d01)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c2ed)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a45973)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f2ad)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a508cb)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffff81942e3e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8196a487)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff819fdf8f)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81a363f6)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a0d6)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bb31)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a47f0b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81a4b46b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff81a5e359)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a61aac)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66bbe)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a67b57)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a6c8aa)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70891)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a72f6d)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c563)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85f3d)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a874eb)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffff81a133be)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff81a3e347)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeca9f)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81b2b4ba)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_get_idx
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f825)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b30fb1)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b3e9eb)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81b415a0)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81b57149)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b5a968)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5f5ee)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b61cd7)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_idx
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b65aaa)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b694b5)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d3fd)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b73d36)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80f5d)
Location: include/net/addrconf.h:309
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b82afb)
Location: include/net/addrconf.h:309
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
In net/core/neighbour.c (ffffffff81a1379e)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff81a41153)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81af9e54)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81b39eda)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_get_idx
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e279)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fbe1)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b4d57b)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81b50060)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81b657b9)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b690fd)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b6dd8e)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b70477)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_idx
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b7420a)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77ee1)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bead)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b82aa6)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b9077d)
Location: include/net/addrconf.h:312
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b9216f)
Location: include/net/addrconf.h:312
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
In net/core/neighbour.c (ffffffff819f98a1)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff81a25db7)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae5594)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81b27bea)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81b2caab)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2da11)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81b3b42b)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81b3df60)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81b53a69)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81b5726d)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c125)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5d687)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b633cf)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b669ec)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a991)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b71710)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f9c6)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81b8143f)
Location: include/net/addrconf.h:311
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
In net/core/neighbour.c (ffffffff81aab2cb)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff81adab23)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba4994)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81bedb2a)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2bfe)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3c65)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81c01c2d)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81c04630)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81c1afa9)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81c1e847)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c2387b)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c24934)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81c2ae8e)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e599)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81c327f1)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81c38f93)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bb86)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b266)
Location: include/net/addrconf.h:311
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81c4d45f)
Location: include/net/addrconf.h:311
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
In net/core/neighbour.c (ffffffff81c22a3b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff81c5c227)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3741a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81d86032)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b74e)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8c98a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81d9b97b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81d9ee0a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81db75c9)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81dbb097)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc07aa)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc1ba3)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81dc8727)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbe37)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfff1)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81dd6f07)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ef4)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deabb6)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81ded9cf)
Location: include/net/addrconf.h:313
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
In net/core/neighbour.c (ffffffff81dd5c1b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e1287e)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81effc3a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81f53b52)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81f5977a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5ab9a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81f6a5db)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81f6ddea)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81f872b9)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81f8b16c)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f90f47)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f924e3)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81f994cf)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9cf48)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1381)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff81fa88c7)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb9b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe776)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81fc179f)
Location: include/net/addrconf.h:313
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
In net/core/neighbour.c (ffffffff81e46a86)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81e86092)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5f6ba)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81fb3542)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81fb942b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fba94a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff81fca61b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81fcde9a)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff81fe75f9)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81feb833)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff1837)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff2e53)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81ff9e9f)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd9d9)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff82001c21)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff82009257)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff8200c33b)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f616)
Location: include/net/addrconf.h:313
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff8202271f)
Location: include/net/addrconf.h:313
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
In net/core/neighbour.c (ffffffff81f0572f)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff81f4809b)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff82025c8a)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff82080da5)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff820869cf)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82087d7a)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffff82097dbe)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff8209b6ea)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_nh_find_match
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ndisc.c (ffffffff820b5459)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff820b94fe)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf436)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c0af6)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff820c7b0f)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc858)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff820d0a21)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ioam6.c (ffffffff820d81f7)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/ipv6/ip6mr.c (ffffffff820db30b)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee746)
Location: include/net/addrconf.h:321
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff820f183f)
Location: include/net/addrconf.h:321
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
In net/core/neighbour.c (ffff800010be3870)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffff800010c11890)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6114)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffff800010cf6ee8)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffff800010cfb098)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfd0c0)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d0aae8)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffff800010d119ac)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffff800010d233ac)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffff800010d26b40)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cb1c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d3086c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffff800010d352a0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39d7c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffff800010d3ba64)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d46678)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d52818)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffff800010d53dd4)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (c0cfbff8)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (c0d285c0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (c0dc1bec)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (c0dfd66c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ac6_get_next
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c0e01b00)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e041f4)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c0e111a0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (c0e14e04)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (c0e279e4)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (c0e2bc18)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c0e309d0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e31428)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_get_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (c0e37230)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c0e3acec)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (c0e3e4f0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (c0e48c84)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52cdc)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (c0e54598)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (c000000000cc2728)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (c000000000cfce1c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (c000000000dce020)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (c000000000e1d6a0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (c000000000e225c4)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e24b74)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c000000000e35830)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (c000000000e3b4e0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (c000000000e53324)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (c000000000e57868)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c000000000e5e5e8)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e6029c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (c000000000e6705c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6adc0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (c000000000e6f340)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7c108)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8af10)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (c000000000e8c714)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffe0007677c2)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffe00078cc02)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffe00080d8ec)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffe000842472)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffe000845bd2)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe00084746c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (ffffffe0008524e0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffe0008563d0)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffe000864d42)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000868b1a)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cda4)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe00086e29c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_next
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffe00087268c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875bac)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffe0008784f8)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe000881160)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a82c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffe00088b942)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffff818e2e0e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8190a457)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff8199dd2f)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff819d5a86)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff819d9766)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819db1c1)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819e759b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff819eaafb)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff819fd9e9)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a0113c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a0624e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a071e7)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a0bf3a)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ff21)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a125fd)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bbf3)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a255cd)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a26b7b)
Location: include/net/addrconf.h:307
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
In drivers/net/vxlan.c (ffffffff8176bad9)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/core/neighbour.c (ffffffff8189cc4e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff818c4307)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff819577ef)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81992846)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81996526)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81997f81)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a435b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff819a78bb)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff819ba7a9)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff819bdefc)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c300e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c3fa7)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff819c8cfa)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccce1)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff819cf3bd)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d89b3)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e238d)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff819e393b)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffff81933e3e)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8195b487)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81a085cf)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81a40506)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a441e6)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a45c41)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5201b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81a5557b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff81a68469)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a6bbbc)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70cce)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a71c67)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a769ba)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a9a1)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d07d)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a86673)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9004d)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a9164f)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
```
```
In net/ipv6/output_core.c (ffffffff81a9272b)
Location: include/net/addrconf.h:307
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
In net/core/neighbour.c (ffffffff81955545)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proc_update
```
```
In net/core/netpoll.c (ffffffff8197d6a7)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/fib_semantics.c (ffffffff81a12e39)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nexthop_info
```
```
In net/ipv6/anycast.c (ffffffff81a4c15f)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
  - net/ipv6/anycast.c:ipv6_sock_ac_join
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fe8c)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a51917)
Location: include/net/addrconf.h:307
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5df6b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:inet6_dump_ifinfo
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_fill_link_af
  - net/ipv6/addrconf.c:inet6_get_link_af_size
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
  - net/ipv6/addrconf.c:ipv6_find_idev
```
```
In net/ipv6/route.c (ffffffff81a6157b)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_upper_bound_set
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ndisc.c (ffffffff81a74a59)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_allow_add
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
```
In net/ipv6/udp.c (ffffffff81a781cc)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d2de)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7e287)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a830ef)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a871df)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/exthdrs.c (ffffffff81a898cd)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a93233)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d1b1)
Location: include/net/addrconf.h:307
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
```
In net/ipv6/output_core.c (ffffffff81a9e80b)
Location: include/net/addrconf.h:307
Inline: True
```
</details>
</li>
</ul>

## Differences
