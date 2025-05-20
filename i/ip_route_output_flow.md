# Function: <code>ip_route_output_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81756e10)
Location: net/ipv4/route.c:2382
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81756e10-ffffffff81756e5a: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c30b0)
Location: net/ipv4/route.c:2405
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff817c30b0-ffffffff817c30fa: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1830)
Location: net/ipv4/route.c:2440
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff817f1830-ffffffff817f187a: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818130c0)
Location: net/ipv4/route.c:2534
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff818130c0-ffffffff81813107: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81892700)
Location: net/ipv4/route.c:2555
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81892700-ffffffff81892747: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e66c0)
Location: net/ipv4/route.c:2579
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff818e66c0-ffffffff818e670e: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81913510)
Location: net/ipv4/route.c:2581
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81913510-ffffffff8191355e: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81975b50)
Location: net/ipv4/route.c:2711
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81975b50-ffffffff81975ba3: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ac560)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff819ac560-ffffffff819ac5b3: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a969f0)
Location: net/ipv4/route.c:2759
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81a969f0-ffffffff81a96aa2: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa0aa0)
Location: net/ipv4/route.c:2736
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81aa0aa0-ffffffff81aa0b73: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8b9d0)
Location: net/ipv4/route.c:2737
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81a8b9d0-ffffffff81a8baa3: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b46960)
Location: net/ipv4/route.c:2855
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81b46960-ffffffff81b46a33: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd39d0)
Location: net/ipv4/route.c:2879
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81cd39d0-ffffffff81cd3aaa: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e93bf0)
Location: net/ipv4/route.c:2870
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81e93bf0-ffffffff81e93cca: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef23a0)
Location: net/ipv4/route.c:2866
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81ef23a0-ffffffff81ef247a: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb6500)
Location: net/ipv4/route.c:2869
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81fb6500-ffffffff81fb65da: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5c668)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffff800010c5c668-ffff800010c5c6e4: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6bd84)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
c0d6bd84-c0d6bdf0: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5eaf0)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
c000000000d5eaf0-c000000000d5eb98: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c55d6)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffe0007c55d6-ffffffe0007c563c: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194c3d0)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff8194c3d0-ffffffff8194c423: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81905ec0)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_get_route
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81905ec0-ffffffff81905f13: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b6ba0)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff819b6ba0-ffffffff819b6bf3: ip_route_output_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rtable *ip_route_output_flow(struct net *net, struct flowi4 *flp4, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819c0410)
Location: net/ipv4/route.c:2720
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/netfilter.c:nf_ip_route
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff819c0410-ffffffff819c0463: ip_route_output_flow (STB_GLOBAL)
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
