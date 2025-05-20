# Function: <code>dev_get_by_index_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81713630)
Location: net/core/dev.c:822
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:skb_do_redirect
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/ping.c:ping_bind
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_getname
```
**Symbols:**

```
ffffffff81713630-ffffffff81713675: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8178476f)
Location: net/core/dev.c:826
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_get_saddr6
  - net/l3mdev/l3mdev.c:l3mdev_get_rt6_dst
```
**Symbols:**

```
ffffffff8177b2e0-ffffffff8177b334: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1d5f)
Location: net/core/dev.c:825
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff817a8940-ffffffff817a8994: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cf3b9)
Location: net/core/dev.c:832
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff817c6f90-ffffffff817c6fe6: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81848d29)
Location: net/core/dev.c:835
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff81840b60-ffffffff81840bb6: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892d88)
Location: net/core/dev.c:835
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
```
**Symbols:**

```
ffffffff8188b190-ffffffff8188b1e6: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3808)
Location: net/core/dev.c:837
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818ac1e0-ffffffff818ac236: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8190009c)
Location: net/core/dev.c:833
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818f7a90-ffffffff818f7ad9: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819323bc)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff81929810-ffffffff81929859: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a074d2)
Location: net/core/dev.c:949
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/xfrm/espintcp.c:handle_esp
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819fd760-ffffffff819fd7a0: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dd5a)
Location: net/core/dev.c:952
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_measure_rcv_mss
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/xfrm/espintcp.c:handle_esp
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819fd380-ffffffff819fd3c0: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4a76)
Location: net/core/dev.c:1000
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff819e3bf0-ffffffff819e3c30: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa63a6)
Location: net/core/dev.c:876
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff81a94490-ffffffff81a944d0: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1e153)
Location: net/core/dev.c:823
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81c0a880-ffffffff81c0a8cb: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcf593)
Location: net/core/dev.c:823
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/xfrm/espintcp.c:handle_esp
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81dba710-ffffffff81dba75b: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e401a3)
Location: net/core/dev.c:835
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:netdev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/xfrm/espintcp.c:handle_esp
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81e2aef0-ffffffff81e2af3b: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efeb26)
Location: net/core/dev.c:852
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:netdev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_xdp_check_mtu
  - net/core/filter.c:bpf_skb_check_mtu
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/netfilter/nf_queue.c:__nf_queue
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_check_bind_addr
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk
  - net/xfrm/espintcp.c:handle_esp
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81ee8f70-ffffffff81ee8fbb: dev_get_by_index_rcu (STB_GLOBAL)
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
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0348)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffff800010bc5e70-ffff800010bc5ecc: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceaeb8)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
c0ce1488-c0ce14dc: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cae028)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
c000000000ca0a60-c000000000ca0acc: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ab8e)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffe0007525b8-ffffffe000752608: dev_get_by_index_rcu (STB_GLOBAL)
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
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d23bc)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff818c9810-ffffffff818c9859: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c24c)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff81883750-ffffffff81883799: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819233bc)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff8191a810-ffffffff8191a859: dev_get_by_index_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_index_rcu(struct net *net, int ifindex);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944808)
Location: net/core/dev.c:751
Inline: True
Inline callers:
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:dev_get_by_index
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inetdev_by_index
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_bind
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/raw.c:rawv6_bind
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/seg6_local.c:input_action_end_dx2
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_getname
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_fib_rule_match
  - net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup
  - net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu
```
**Symbols:**

```
ffffffff8193bad0-ffffffff8193bb19: dev_get_by_index_rcu (STB_GLOBAL)
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
