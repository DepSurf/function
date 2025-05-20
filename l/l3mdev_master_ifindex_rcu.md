# Function: <code>l3mdev_master_ifindex_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81816e90)
Location: net/l3mdev/l3mdev.c:20
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
**Symbols:**

```
ffffffff81816e90-ffffffff81816ed2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff8188bb80)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/xfrm4_policy.c:_decode_session4
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:_decode_session6
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8188bb80-ffffffff8188bbc2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff818bfd30)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff818bfd30-ffffffff818bfd72: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff818e66a0)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff818e66a0-ffffffff818e66e2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff8196bb40)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff8196bb40-ffffffff8196bb82: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff819c55d0)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff819c55d0-ffffffff819c5612: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff819fcc80)
Location: net/l3mdev/l3mdev.c:21
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff819fcc80-ffffffff819fccc2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81a6bf00)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff81a6bf00-ffffffff81a6bf42: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81aa28c0)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff81aa28c0-ffffffff81aa2902: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81b9e3ae)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81b9e2a0-ffffffff81b9e2e2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81badda3)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81badb70-ffffffff81badbb2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81b9cf03)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81b9ccd0-ffffffff81b9cd12: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81c6a423)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81c6a1f0-ffffffff81c6a232: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81e0dae0)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81e0d840-ffffffff81e0d89b: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81fe3e10)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81fe3b20-ffffffff81fe3b7b: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff82060130)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmpv4_xrlim_allow
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff8205fe40-ffffffff8205fe9b: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff82133051)
Location: net/l3mdev/l3mdev.c:110
Inline: True
Inline callers:
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_lookup
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmpv4_xrlim_allow
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup
  - net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_lookup
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk
  - net/ipv6/tcp_ao.c:tcp_v6_ao_lookup
```
**Symbols:**

```
ffffffff82132d80-ffffffff82132dd7: l3mdev_master_ifindex_rcu (STB_GLOBAL)
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
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffff800010d74310)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffff800010d74310-ffff800010d7436c: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (c0e70ef4)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
c0e70ef4-c0e70f48: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (c000000000eb3890)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
c000000000eb3890-c000000000eb3924: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffe0008a42ee)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffe0008a42ee-ffffffe0008a4346: l3mdev_master_ifindex_rcu (STB_GLOBAL)
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
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81a41c50)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff81a41c50-ffffffff81a41c92: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff819fe840)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff819fe840-ffffffff819fe882: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81aadb00)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff81aadb00-ffffffff81aadb42: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int l3mdev_master_ifindex_rcu(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/l3mdev/l3mdev.c (ffffffff81ab9e70)
Location: net/l3mdev/l3mdev.c:17
Inline: True
Direct callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_process
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/devinet.c:inet_select_addr
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:fib_info_nh_uses_dev
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/addrconf.c:ipv6_dev_get_saddr
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:__ip6_datagram_connect
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
  - net/l3mdev/l3mdev.c:l3mdev_update_flow
```
**Symbols:**

```
ffffffff81ab9e70-ffffffff81ab9eb2: l3mdev_master_ifindex_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net_device *dev</code> ➡️ <code>const struct net_device *dev</code>
</li>
</ul>
</details>
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
