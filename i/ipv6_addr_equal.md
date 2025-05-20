# Function: <code>ipv6_addr_equal</code>

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
In security/selinux/netnode.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff817b944e)
Location: include/net/ipv6.h:432
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff817c391f)
Location: include/net/ipv6.h:432
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/addrlabel.c (ffffffff817d2d58)
Location: include/net/ipv6.h:432
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff817e8e2b)
Location: include/net/ipv6.h:432
Inline: True
Inline callers:
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817fae35)
Location: include/net/ipv6.h:432
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/netfilter.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/ipv6.h:432
Inline: True
```
```
In net/netlabel/netlabel_addrlist.c (0)
Location: include/net/ipv6.h:432
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
In security/selinux/netnode.c (ffffffff813830cf)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/ping.c (ffffffff8181180b)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818234a3)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81827486)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff818309ef)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81831944)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/addrconf.c (ffffffff8183ec74)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/addrlabel.c (ffffffff8184075a)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81844ed5)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8184944e)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff8184f5f3)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81850b0b)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff8185486f)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81856ace)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff818588ab)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/reassembly.c (ffffffff8185c1b9)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185efbc)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818635e0)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8186a40d)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find
  - net/ipv6/ip6mr.c:ip6mr_cache_find
```
```
In net/ipv6/netfilter.c (ffffffff8186d92d)
Location: include/net/ipv6.h:464
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872eda)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f4a2)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff81399b4f)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/ping.c (ffffffff81842d1b)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854df3)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81858c66)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff8186247f)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81863374)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/addrconf.c (ffffffff81870884)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/addrlabel.c (ffffffff818723da)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81876c45)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b2a6)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81881527)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff8188295a)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffff818865a1)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff818888d0)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff8188a2eb)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/reassembly.c (ffffffff8188e0c9)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81890ddb)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff81895bfa)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff8189d25d)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find
  - net/ipv6/ip6mr.c:ip6mr_cache_find
```
```
In net/ipv6/netfilter.c (ffffffff818a071d)
Location: include/net/ipv6.h:464
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a74fa)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3d52)
Location: include/net/ipv6.h:464
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff813affcf)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8181ff73)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8186460b)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878961)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff8187ccfe)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81886c09)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81888bdd)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/addrconf.c (ffffffff81895660)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8189714b)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8189e4a7)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0be9)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff818a7585)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff818a8e7a)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff818ac6e1)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff818aed03)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff818b0aa5)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/reassembly.c (ffffffff818b4769)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b73fa)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff818bc184)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff818c3769)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find
  - net/ipv6/ip6mr.c:ip6mr_cache_find
```
```
In net/ipv6/netfilter.c (ffffffff818c6d5d)
Location: include/net/ipv6.h:465
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce56a)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff818da6e2)
Location: include/net/ipv6.h:465
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff813d607b)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189ef63)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff818e4755)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f92b3)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff818fda5a)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81907e19)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81908fed)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/addrconf.c (ffffffff81916b14)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81918685)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81920a89)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81923522)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81929ff4)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff8192b83d)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff8192f05e)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819319f2)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff819348c5)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
```
In net/ipv6/reassembly.c (ffffffff819374d9)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a23a)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/datagram.c (ffffffff8193f25d)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
```
In net/ipv6/ip6mr.c (ffffffff81946a0c)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_find_any
  - net/ipv6/ip6mr.c:ip6mr_cache_find
  - net/ipv6/ip6mr.c:ip6mr_cache_find
```
```
In net/ipv6/netfilter.c (ffffffff8194a21d)
Location: include/net/ipv6.h:506
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953437)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819602c2)
Location: include/net/ipv6.h:506
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff8140668b)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3a06)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8193af8a)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fd8f)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff8195438d)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff8195f019)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff819602cd)
Location: include/net/ipv6.h:494
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8196e1c4)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196fef9)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81978f06)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff8197b967)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff8198231f)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81983c91)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff81987e1a)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff8198a4a0)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff8198d278)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993098)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff8199f292)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff819a31ac)
Location: include/net/ipv6.h:494
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ace6c)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9a92)
Location: include/net/ipv6.h:494
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff814221eb)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921526)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8196ac7a)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983412)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81988c28)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff8199438e)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff819950ad)
Location: include/net/ipv6.h:514
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a3d44)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5b19)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819aeb5e)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1647)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff819b89cf)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff819ba1c0)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff819be76e)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c0d40)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff819c3b2c)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c941a)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff819d5db9)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff819d9cbc)
Location: include/net/ipv6.h:514
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e23f1)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e382b)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0d62)
Location: include/net/ipv6.h:514
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff8144fdef)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81983e94)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff819d1938)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ed24a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff819f29e8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81a002e1)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81a0155d)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a10085)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a1208b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a1cd16)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1f711)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a2743e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a29313)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a2d8bc)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a2fa5b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a329b2)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37f66)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81a44e0e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81a4887c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a510b3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a5254a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a60022)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff81469c3f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ba644)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a0849b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2425a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81a298b8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81a36ec4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81a386fd)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a46dc8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48cab)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a539a3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5636f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a5de9e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a5fe71)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a64429)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a665ab)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a69502)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6eaa6)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b9fe)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81a7f45c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87cd3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8915a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96c52)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff814bde5b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa51a0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81af80df)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f426)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c03b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81b2c180)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81b2cded)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81b31670)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3dc9a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f696)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b3fa54)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4e348)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b56c6a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b58983)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b5ce99)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5f1f4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81b627f2)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b676b7)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81b767db)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81b79d2c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83186)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8428a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b92422)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff814db88b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad17c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_lookup_by_sk
  - net/ipv4/inet_hashtables.c:inet_ehash_lookup_by_sk
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf7b0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81b04f3f)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d716)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2a812)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81b3aba1)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b7fd)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81b40260)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b4c81a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
```
```
In net/ipv6/addrlabel.c (ffffffff81b4e136)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b4e534)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5cfd6)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b652da)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b66fb8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_demux_lookup
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b6b6cf)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b6d984)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81b70d22)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75eb7)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81b855a0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81b88c7f)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92832)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93aef)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba2092)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff814e21fb)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a998be)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9aac0)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81af07a3)
Location: include/net/ipv6.h:573
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b056)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1841b)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81b28881)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81b2925d)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e870)
Location: include/net/ipv6.h:573
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3a4ed)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3c11d)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b47f66)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b1f1)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b535ce)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81b5518e)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
```
```
In net/ipv6/raw.c (ffffffff81b59a1b)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81b5bd1c)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81b5f83b)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b648eb)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81b74119)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81b77a96)
Location: include/net/ipv6.h:573
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81985)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82bff)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b91172)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff8153b271)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54d3e)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b55f30)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81bb0576)
Location: include/net/ipv6.h:576
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcdfb1)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdc80b)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81bee855)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81bf03e3)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c18)
Location: include/net/ipv6.h:576
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81c00c8d)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81c02a0d)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81c0f1f7)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81c12531)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81c1aade)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81c1dc67)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81c21041)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81c23560)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81c2705b)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2caeb)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e9c8)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81c425b6)
Location: include/net/ipv6.h:576
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d9c9)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4eccf)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5d912)
Location: include/net/ipv6.h:576
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff815d2a09)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce296a)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3cdc)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81d43be0)
Location: include/net/ipv6.h:630
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d640af)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81d7358e)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81d86dd8)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81d88a74)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da35)
Location: include/net/ipv6.h:630
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d9a902)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c62d)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81da045c)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81dad563)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81db70a1)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81dba2d6)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81dbda5f)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81dc04a1)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81dc3775)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9e8d)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd130)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/netfilter.c (ffffffff81de1000)
Location: include/net/ipv6.h:630
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb4e4)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_encap_cmp
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee093)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def750)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81dff9a2)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35e4a)
Location: include/net/ipv6.h:630
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In security/selinux/netnode.c (ffffffff81680999)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea431e)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_find
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_match_addr_any
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea671c)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81f0cbf2)
Location: include/net/ipv6.h:663
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2ee1f)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3f5ae)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81f54998)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81f56874)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bb65)
Location: include/net/ipv6.h:663
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f69752)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b31d)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81f6f6bc)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7cfd3)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81f86d71)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81f8a39a)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81f8e337)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81f90bf0)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81f94965)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9ae87)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81fae5b8)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/netfilter.c (ffffffff81fb3450)
Location: include/net/ipv6.h:663
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf104)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_encap_cmp
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2632)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3820)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd4722)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
```
```
In net/mptcp/pm_userspace.c (ffffffff8200eaf4)
Location: include/net/ipv6.h:663
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In security/selinux/netnode.c (ffffffff816b8a53)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02bbe)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_find
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f04eec)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81f6c870)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f647)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9eed1)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff81fb43a8)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6273)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb925)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc97c2)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb4d3)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81fcf797)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd1e0)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81fe70b1)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81fe9faa)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff81feeb25)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff81ff106e)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81ff52e5)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffc287)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff8200fa38)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/netfilter.c (ffffffff82013b40)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020094)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_encap_cmp
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/ip6_offload.c (ffffffff820235b0)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202466b)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82050372)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b676)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
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
In security/selinux/netnode.c (ffffffff816f54a3)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6f43)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_find
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc91fc)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff82032fc0)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d3a7)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_ok
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c231)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/anycast.c (ffffffff82081c58)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff82083933)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
```
```
In net/ipv6/ip6_input.c (ffffffff82088d5c)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82096f62)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff82098cb3)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8209cff7)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:fib6_nh_del_cached_rt
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_redirect_nh_match
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab320)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff820b4f10)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff820b7b8a)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:compute_score
  - net/ipv6/udp.c:compute_score
```
```
In net/ipv6/raw.c (ffffffff820bc6f7)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw_v6_match
  - net/ipv6/raw.c:raw_v6_match
```
```
In net/ipv6/icmp.c (ffffffff820bec4e)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff820c2eb2)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c959c)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff820de9c8)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/netfilter.c (ffffffff820e2ca0)
Location: include/net/ipv6.h:664
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef1c4)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_encap_cmp
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/ipv6/ip6_offload.c (ffffffff820f26a9)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f397b)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82122a22)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
```
```
In net/mptcp/pm_userspace.c (ffffffff821613ad)
Location: include/net/ipv6.h:664
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
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
In security/selinux/netnode.c (ffff800010558360)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c354)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffff800010cc16e0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce129c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7580)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffff800010cf7c4c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffff800010cfa12c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d0995c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0c0f4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffff800010d17bbc)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffff800010d1aed4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffff800010d22f74)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffff800010d255f4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffff800010d2a2e4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffff800010d2c51c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffff800010d31054)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d373d0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffff800010d45740)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffff800010d4aa00)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffff800010d548a0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55f34)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffff800010d66104)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (c070d094)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (c0d7afa8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (c0dcb838)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (c0dea5c8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (c0df0194)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (c0dfe1b4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (c0e00380)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (c0e0fff8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c0e11e58)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c0e1d714)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (c0e202d0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c0e27594)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (c0e28ee8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c0e2e318)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c0e303b8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (c0e320ec)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c0e39678)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (c0e48154)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (c0e4bd2c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (c0e54e58)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (c0e564cc)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (c0e6498c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (c0000000006b636c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (c000000000d71880)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (c000000000ddcab4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (c000000000e03af4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (c000000000e0b5b0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (c000000000e1e660)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (c000000000e2208c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e341e8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c000000000e369fc)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c000000000e45710)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (c000000000e493a8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c000000000e52e54)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (c000000000e55750)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c000000000e5b450)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (c000000000e5e04c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (c000000000e62a8c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69b64)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (c000000000e7b160)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (c000000000e80824)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (c000000000e8d3d0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8efc8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (c000000000ea2198)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffe0003afa3a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1ae0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffe000815ad8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fde0)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffe0008363b8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffe000842eae)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffe000844954)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe0008515ac)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852f68)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffe00085caec)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffe00085f188)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffe0008649c4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffe000866586)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffe00086ab1c)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffe00086c98e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffe00086e392)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087479a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffe000880922)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffe000883b48)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c212)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d7d4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899c46)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff8146221f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195a4b4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff819a823b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c38ea)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff819c8f48)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff819d6554)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff819d7d8d)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819e6458)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e833b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819f3033)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff819f59ff)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819fd52e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff819ff501)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a03ab9)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a05c3b)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a08b92)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e136)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81a1b08e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81a1eaec)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27363)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a287ea)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a35fe2)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff81452c4f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In drivers/net/vxlan.c (ffffffff8176fc63)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_snoop
  - drivers/net/vxlan.c:vxlan_fdb_find_rdst
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81913fa4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81961cfb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff819806da)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81985d38)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81993314)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81994b4d)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a3218)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a50fb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819afdf3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff819b27bf)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819ba2ee)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff819bc2c1)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff819c0879)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff819c29fb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff819c5952)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819caef6)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff819d7e4e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff819db8ac)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4123)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e55aa)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2c02)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff8145e2bf)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c4c84)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a12adb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2e36a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81a339c8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81a40fd4)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81a4280d)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a50ed8)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52dbb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a5dab3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6047f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a67fae)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a69f81)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a6e539)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a706bb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a73612)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78bb6)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81a85b0e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81a8956c)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92f13)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9439a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa1e92)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
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
In security/selinux/netnode.c (ffffffff81475a5f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_find
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ce734)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a1d4ab)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_lookup
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39b61)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3f318)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81a4cbdf)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_sock_ac_drop
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e49d)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5ce1d)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ed36)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a69ec3)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_del_cached_rt
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:ip6_sk_dst_store_flow
  - net/ipv6/route.c:fib6_nh_find_match
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:__rt6_find_exception_spinlock
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6c93f)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a7459e)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/udp.c (ffffffff81a76591)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (ffffffff81a7ab6a)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:__raw_v6_lookup
  - net/ipv6/raw.c:__raw_v6_lookup
```
```
In net/ipv6/icmp.c (ffffffff81a7ccdb)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_route_lookup
```
```
In net/ipv6/mcast.c (ffffffff81a7fc92)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85341)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ip6mr.c (ffffffff81a92637)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
  - net/ipv6/ip6mr.c:ip6mr_hash_cmp
```
```
In net/ipv6/netfilter.c (ffffffff81a961cc)
Location: include/net/ipv6.h:572
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f066)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa04ee)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae202)
Location: include/net/ipv6.h:572
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_search_exact
```
</details>
</li>
</ul>

## Differences
