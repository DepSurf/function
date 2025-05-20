# Function: <code>__ipv6_addr_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff817ff9e0)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/udp.c:ipv6_rcv_saddr_equal
  - net/ipv6/udp.c:ipv6_rcv_saddr_equal
  - net/ipv6/udp.c:ipv6_rcv_saddr_equal
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817ff9e0-ffffffff817ffab9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81871090)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff81871090-ffffffff81871164: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff818a55e0)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ipv6/inet6_hashtables.c:ipv6_rcv_saddr_equal
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff818a55e0-ffffffff818a56b4: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff818cc070)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff818cc070-ffffffff818cc142: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81950e20)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ip6_frag_match
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff81950e20-ffffffff81950ef2: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff819aa390)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff819aa390-ffffffff819aa462: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff819e0ea0)
Location: net/ipv6/addrconf_core.c:36
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff819e0ea0-ffffffff819e0f72: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81a4fc00)
Location: net/ipv6/addrconf_core.c:37
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ncsi/ncsi-manage.c:ncsi_inet6addr_event
```
**Symbols:**

```
ffffffff81a4fc00-ffffffff81a4fce9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81a86890)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a86890-ffffffff81a86979: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81b81910)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
**Symbols:**

```
ffffffff81b81910-ffffffff81b819f9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81b90ff0)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_output.c:ip6_forward_proxy_check
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_sit_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
```
**Symbols:**

```
ffffffff81b90ff0-ffffffff81b910d9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81b801e0)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff81b801e0-ffffffff81b802b0: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81c4c200)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff81c4c200-ffffffff81c4c2d0: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81dec470)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff81dec470-ffffffff81dec576: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81fc00e0)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_validate_gw
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff81fc00e0-ffffffff81fc01e6: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff82021060)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff82021060-ffffffff82021166: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff820f0190)
Location: net/ipv6/addrconf_core.c:38
Inline: False
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_bind2_bucket_create
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
```
**Symbols:**

```
ffffffff820f0190-ffffffff820f0296: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffff800010d52db0)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010d52db0-ffff800010d52ef4: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (c0e5381c)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0e5381c-c0e53958: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (c000000000e8b4b0)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000e8b4b0-c000000000e8b618: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffe00088acc6)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe00088acc6-ffffffe00088adb8: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81a25f20)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a25f20-ffffffff81a26009: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff819e2ce0)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:vxlan_snoop
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819e2ce0-ffffffff819e2dc9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81a91ad0)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a91ad0-ffffffff81a91bb9: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __ipv6_addr_type(const struct in6_addr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81a9db80)
Location: net/ipv6/addrconf_core.c:38
Inline: True
Direct callers:
  - net/core/utils.c:inet6_pton
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/inet_connection_sock.c:ipv6_rcv_saddr_equal
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_getname
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_chk_acast_addr_src
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/route.c:ip6_pkt_drop
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
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_redirect_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/inet6_connection_sock.c:inet6_csk_addr2sockaddr
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81a9db80-ffffffff81a9dc69: __ipv6_addr_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
