# Function: <code>ipv6_addr_type</code>

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
In net/core/netpoll.c (ffffffff817386d0)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/ping.c (ffffffff817a2a08)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff817c2bb9)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff817c4421)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff817c69df)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff817c90b4)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff817ca495)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2872)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d3b27)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff817df344)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff817e17bc)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/udp.c:ipv6_rcv_saddr_equal
  - net/ipv6/udp.c:ipv6_rcv_saddr_equal
```
```
In net/ipv6/raw.c (ffffffff817e51b1)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff817e77bb)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff817ece0a)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffff817ed9c1)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef130)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff817f266e)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff817f325f)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff817f40f5)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6633)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff817ff780)
Location: include/net/ipv6.h:334
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81802871)
Location: include/net/ipv6.h:334
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
In net/core/netpoll.c (ffffffff817a49c0)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/ping.c (ffffffff8181137f)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8182fc1a)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff818314d1)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81833ad8)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81836294)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff8183b3cc)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff81840931)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8184152c)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ndisc.c (ffffffff8184f980)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81853491)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81855bc9)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8185bd6b)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8185c202)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185da48)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff818613b3)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818620ef)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff8186384f)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81865804)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff8186f0ed)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872e55)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
```
```
In net/ipv6/mcast_snoop.c (ffffffff81873b70)
Location: include/net/ipv6.h:351
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188e3d6)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/netpoll.c (ffffffff817d3430)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/ping.c (ffffffff8184288f)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8186169a)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81862f41)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81865552)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81867da4)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff8186cdaa)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/addrlabel.c (ffffffff818725b1)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81878ab8)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81881542)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff818851a1)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81887989)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8188dc6b)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8188e112)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fa89)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff818932f3)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81893f4f)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81895e9e)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897ed4)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff818a2058)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7475)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
```
```
In net/ipv6/mcast_snoop.c (ffffffff818a81f0)
Location: include/net/ipv6.h:351
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c26b6)
Location: include/net/ipv6.h:351
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff817e7319)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/netpoll.c (ffffffff817f2774)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8181fedd)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8186403c)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81885dd4)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81887751)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81889d2e)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8188c5b3)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff818916e5)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8189733d)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8189dd8d)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a75a1)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff818ab592)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff818adf8a)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818b431c)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff818b47b2)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b612b)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff818b98b6)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818ba672)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff818bc42d)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818be262)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff818c86f2)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff818cea31)
Location: include/net/ipv6.h:352
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff818e9046)
Location: include/net/ipv6.h:352
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff81862259)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/netpoll.c (ffffffff8186dd34)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189eecd)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff818e417c)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81906f87)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81908981)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff8190af1e)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8190d8a3)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81913315)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81917ff9)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819190db)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff8192a00f)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff8192e132)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81930c0a)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8193708c)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81937522)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_match
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938eaa)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff8193c836)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8193d652)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff8193f512)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819413a2)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff8194bcb7)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff819538e1)
Location: include/net/ipv6.h:393
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196e5b6)
Location: include/net/ipv6.h:393
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff818aded9)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff818b4aea)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff818bee81)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3925)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8193aa3b)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8195e9c5)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff8195fb35)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81962416)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81964c48)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff8196aafd)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196f82f)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81970865)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81982696)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81986dca)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff8198982d)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198fdcd)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff8199074b)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199274a)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff819958b4)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81996537)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81998314)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8199a0da)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/syncookies.c (ffffffff819a4fbe)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff819ad2fc)
Location: include/net/ipv6.h:381
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c8006)
Location: include/net/ipv6.h:381
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff818d2149)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff818da6aa)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff818e7c84)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921445)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8196a72b)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81993525)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81994865)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff819973e9)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8199a0da)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff8199facd)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a543f)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819a6495)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819b8d43)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff819bd6ea)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c014b)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c6667)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c6e98)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8e84)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff819cc196)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819cce47)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819ceca4)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d066c)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff819d99da)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819dba88)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e3c9d)
Location: include/net/ipv6.h:401
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff819ffc66)
Location: include/net/ipv6.h:401
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff8191f3d8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81929e3b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81937608)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81983db5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff819d13db)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819fefd1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a003b5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81a033cc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a0604c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81a0bdb3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a11923)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a12bc1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a274ed)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81a2c182)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a2ef86)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a3547a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a36167)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37844)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81a3ac73)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a3b920)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a3d970)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f671)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81a48248)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a4a73a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a52b11)
Location: include/net/ipv6.h:459
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a6ef35)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
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
In net/core/utils.c (ffffffff81951618)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff8195c1cb)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff8196a4c8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ba565)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a07f3b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a35bd1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a36f95)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81a39f9c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3cbbc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81a42a63)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48543)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a497b1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a5df4d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81a62ce2)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a65ad6)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6bfba)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6cc87)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e36e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81a718f3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a725a0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a745e0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a762e1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81a7edf8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a8130e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a896f1)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff81a22488)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81a2ff6b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81a3e388)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa50b5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81af68d8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81b2ac8c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b2c215)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f7e4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b3225c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81b32991)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f3d1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b45b96)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b56d1c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81b5b5a2)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5e417)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b64f2a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b66343)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68012)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b6b1e6)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cc72)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6e7e8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7043d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81b79a48)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b7bfbc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84a0d)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff81a22808)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81a31c6b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81a41192)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf6ce)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81b03758)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06c8d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81b3961d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b3ac35)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e238)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
```
```
In net/ipv6/ip6_input.c (ffffffff81b40e82)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81b412b1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4de61)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b5453c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b6538c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81b69dcd)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b6cbee)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b736ca)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b74baf)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76834)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b79c66)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b701)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b7d2a8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f2ee)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81b88996)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b8afed)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b9436d)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff81a09b38)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81a18adb)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81a25df8)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9a9de)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81aeef98)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af23c3)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81b272e7)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81b28915)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c9a8)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2eda9)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81b3a154)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b901)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b41ca2)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81b5367d)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81b580bd)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81b5af55)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5ee21)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b636e1)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b651a8)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81b68793)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a1c4)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81b6be8c)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6db72)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81b776ca)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81b79e50)
Location: include/net/ipv6.h:460
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b8342e)
Location: include/net/ipv6.h:460
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
In net/core/utils.c (ffffffff81abc018)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81aca2eb)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81adab64)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b55e4e)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81baf368)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb28d3)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81bed221)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81bee8e5)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2af3)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf50d9)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81c008f4)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81c02191)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81c099d2)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81c1ab8d)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81c20097)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81c22665)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c265c6)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2b1a1)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d3e8)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81c3045d)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81c32024)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81c33d25)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35a32)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81c4219b)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81c44b1c)
Location: include/net/ipv6.h:463
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f4fe)
Location: include/net/ipv6.h:463
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
In net/core/utils.c (ffffffff81c36a50)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81c476fb)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81c5c267)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3bcd)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81d426d8)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d460a8)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81d8571b)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81d86e55)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b6b2)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8df38)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81d9a50a)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c130)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81da4ba3)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81db7166)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81dbcdc3)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81dbf41d)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc421f)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc8454)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca7ef)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81dcdb59)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf820)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81dd15b5)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd34cb)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81de0b6f)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81de3b1d)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81deff39)
Location: include/net/ipv6.h:517
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/utils.c (ffffffff81dea1e2)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81dfbdcb)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81e128ba)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81eaa40d)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81f0b588)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f488)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81f531db)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81f54a25)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81f596de)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5c0a8)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81f6930a)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6ae00)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81f74053)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81f86e36)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81f8cdd3)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81f8fb6d)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f9437f)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f991e4)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b829)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81f9ed8c)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0ba4)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81fa2bd5)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4a7b)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81fb2faf)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81fb619d)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc4059)
Location: include/net/ipv6.h:550
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/utils.c (ffffffff81e5b9d2)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81e6f8bb)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81e860ce)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f08c1c)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81f6b168)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f178)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2c46)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81fb4435)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81fb938f)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbe58)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81fc937a)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcae30)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81fd4133)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81fe7176)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81fed5c9)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81ff039d)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81ff4cff)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9bb4)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbbf1)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81fff851)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff820000c1)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff82003486)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8200532b)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff8201369f)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff820168b5)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff82025079)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/utils.c (ffffffff81f1ad92)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81f2f08b)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff81f480d7)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7993)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fccf72)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff82031c58)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_check_bind_addr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820358a8)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/af_inet6.c (ffffffff82080426)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff82081ce5)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff8208690f)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82089288)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff82096b1a)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff820985d0)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff820a1a45)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff820b4fd5)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff820bb1c9)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff820bdf6d)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff820c28cf)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c7824)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca2ff)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff820ce61e)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff820cee51)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff820d225d)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d412d)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff820e2802)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff820e58c8)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f4359)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/utils.c (ffff800010bf3334)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffff800010bfe0cc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffff800010c118f4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c278)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffff800010cc1190)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffff800010cf66c4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffff800010cf7da4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffff800010cfaf28)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfdee0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffff800010d05000)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0b89c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffff800010d11edc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffff800010d23020)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffff800010d27f54)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffff800010d2bb88)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d33a20)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d35948)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37cdc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffff800010d3a358)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3ae78)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffff800010d3d008)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3f604)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffff800010d4a6f4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffff800010d4c9f0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffff800010d564f0)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (c0d0bb5c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (c0d1880c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (c0d285ec)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (c0d7aeb4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (c0dcceb4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c0dfcfb4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c0dfe2b8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (c0e01838)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e059c0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (c0e0c17c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c0e1178c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c0e12cc8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (c0e27af4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (c0e2c9c4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c0e2f9d8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e366b8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e37bf8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c0e38934)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (c0e3c87c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3d7b4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c0e40244)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (c0e4225c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (c0e4b608)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c0e4dd54)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (c0e56ae0)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (c000000000cd82ac)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (c000000000ce5b30)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (c000000000cfce58)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (c000000000d717f0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (c000000000ddc418)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1cc2c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (c000000000e1e7a4)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (c000000000e223dc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e261b0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (c000000000e2ef2c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c000000000e3607c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c000000000e37f10)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (c000000000e52f30)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (c000000000e59094)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (c000000000e5d1c8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e66120)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e67a28)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69224)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (c000000000e6d584)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c000000000e6e638)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (c000000000e710fc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73b18)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (c000000000e7ffa0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c000000000e83260)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f73c)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffe000774c90)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffe00078016c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffe00078cc26)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1a96)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffe000816180)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffe000841dfc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffe000842f70)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffe000845ab0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000848328)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffe00084f5ac)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852934)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffe000853ece)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffe000864a78)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffe00086979a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffe00086be82)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe000871c50)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000872e04)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087412e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffe000876ff2)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe000877bf6)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffe00087982c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b386)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffe00088359a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffe00088575e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088dd62)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff818f15e8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff818fc19b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff8190a498)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195a3d5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff819a7cdb)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d5261)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819d6625)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff819d962c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dc24c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff819e20f3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e7bd3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819e8e41)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819fd5dd)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81a02372)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a05166)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a0b64a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c317)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d9fe)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81a10f83)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a11c30)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a13c70)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15971)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81a1e488)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a2099e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28d81)
Location: include/net/ipv6.h:459
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
In drivers/net/vxlan.c (ffffffff8176ba61)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_snoop
```
```
In net/core/utils.c (ffffffff818ab428)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff818b5fcb)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff818c4348)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81913ec5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff8196179b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967870)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
```
```
In net/ipv6/af_inet6.c (ffffffff81992021)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff819933e5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff819963ec)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8199900c)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff8199eeb3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a4993)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819a5c01)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff819ba39d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff819bf132)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff819c1f26)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c840a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c90d7)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca7be)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff819cdd43)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ce9f0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff819d0a30)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2731)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff819db248)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff819dd75e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5f71)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff81942618)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff8194d1cb)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff8195b4c8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c4ba5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a1257b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fce1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a410a5)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81a440ac)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46ccc)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81a4cb73)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52653)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a538c1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a6805d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81a6cdf2)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a6fbe6)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a760ca)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a76d97)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7847e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81a7ba03)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c6b0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a7e6f0)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a803f1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81a88f08)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a8b41e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94931)
Location: include/net/ipv6.h:459
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
In net/core/utils.c (ffffffff81963f18)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff8196eb8b)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/netpoll.c (ffffffff8197d6e8)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ce655)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
```
```
In net/ipv4/ping.c (ffffffff81a1cf7a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b822)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
```
In net/ipv6/anycast.c (ffffffff81a4cc95)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fd4d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a52a4d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/addrconf.c (ffffffff81a58ae3)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e65a)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a5f8b1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/ndisc.c (ffffffff81a7464d)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
```
In net/ipv6/raw.c (ffffffff81a7943e)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_bind
```
```
In net/ipv6/icmp.c (ffffffff81a7c212)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a827fa)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a833b7)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84bee)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
```
In net/ipv6/ping.c (ffffffff81a88253)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a88f00)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/datagram.c (ffffffff81a8af90)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8cda1)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/netfilter.c (ffffffff81a95b68)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffffffff81a98027)
Location: include/net/ipv6.h:459
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0a91)
Location: include/net/ipv6.h:459
Inline: True
```
</details>
</li>
</ul>

## Differences
