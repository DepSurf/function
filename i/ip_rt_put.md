# Function: <code>ip_rt_put</code>

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
In net/ipv4/route.c (ffffffff8175331a)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_negative_advice
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8175f880)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817642f3)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c76b)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81784020)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81784ffd)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8178783a)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8178c796)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8178e877)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8179465f)
Location: include/net/route.h:217
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff817956d0)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff817a3c62)
Location: include/net/route.h:217
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff817a9591)
Location: include/net/route.h:217
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
In net/ipv4/route.c (ffffffff817c3068)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff817cbb20)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d099d)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea0aa)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff817f15b1)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f25f5)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f4f93)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff817f9d91)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff817fbeb8)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81802005)
Location: include/net/route.h:220
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818030c0)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff818109a1)
Location: include/net/route.h:220
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81816dd1)
Location: include/net/route.h:220
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
In net/ipv4/route.c (ffffffff817f17fe)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff817fb79b)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800821)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a831)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81822190)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818233e0)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81826060)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8182ac61)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8182ce08)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81832fda)
Location: include/net/route.h:219
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81834060)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81841eae)
Location: include/net/route.h:219
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818485ac)
Location: include/net/route.h:219
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
In net/ipv4/route.c (ffffffff81813092)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8181bb64)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820404)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b017)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81842e00)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81843ef6)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81846827)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8184be65)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8184e28b)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81854300)
Location: include/net/route.h:227
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8185563a)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81863777)
Location: include/net/route.h:227
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81869bfa)
Location: include/net/route.h:227
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
In net/ipv4/route.c (ffffffff818926d2)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8189aa9d)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f3c4)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bac47)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff818c2763)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c3675)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c625a)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff818cbb0b)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff818cdfb7)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff818d4180)
Location: include/net/route.h:230
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d54da)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff818e38b7)
Location: include/net/route.h:230
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818ea2b8)
Location: include/net/route.h:230
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
In net/ipv4/route.c (ffffffff818e66aa)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818eef61)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3e01)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f6bc)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819183ab)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81919481)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191ba64)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921ff2)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819246c3)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8192a699)
Location: include/net/route.h:233
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192be7f)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff8193a141)
Location: include/net/route.h:233
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819409a0)
Location: include/net/route.h:233
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
In net/ipv4/route.c (ffffffff819134fa)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8191c751)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921921)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193dae3)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81946b01)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947d53)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a069)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81950e22)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819532db)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81959e29)
Location: include/net/route.h:232
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195b30f)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81969eea)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff8197086b)
Location: include/net/route.h:232
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff81975b23)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197ea7c)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819842ea)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1eea)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ab17a)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819aca41)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819ae5f1)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819b56ee)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819b7e27)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819be7af)
Location: include/net/route.h:238
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819bffa2)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff819d0df0)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819da0b3)
Location: include/net/route.h:238
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff819ac533)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b540e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819baa9a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8ba0)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819e1e48)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e35ff)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e530f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819ec40e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819eeb27)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819f53df)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f6b42)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81a0794a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a10fa2)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff81a96dcf)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81a9f66f)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5c14)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac55e7)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81acf6be)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ad0ebb)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad5129)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ada363)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81adc8b1)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81ae3775)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/igmp.c (ffffffff81ae5122)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81af718f)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b028f3)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81a31275)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81aa0ec2)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81aa95af)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0254)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1265)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81adb6c3)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adce17)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae16a6)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6e03)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ae95cc)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81af02f5)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/igmp.c (ffffffff81af1ff2)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81b0402e)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b10cc1)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81a182b5)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81a8be48)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81a9477c)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b429)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc256)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81ac6733)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac7eb6)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb3cc)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad20d1)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81ad4cd1)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81adb9a5)
Location: include/net/route.h:249
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81add7e2)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81aefcba)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81afe7c0)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81acba1b)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81b46dd5)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81b4fbfc)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56899)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79356)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81b84f43)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b86716)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b89c5c)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b90d21)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81b939bf)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81b9abe5)
Location: include/net/route.h:249
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81b9cc52)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81bafcca)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81bbffd6)
Location: include/net/route.h:249
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81c4766a)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81cd3e93)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff81cdd68b)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce41be)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d088ab)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d157ec)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d170f8)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1d4c7)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d236dd)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81d247e7)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2c601)
Location: include/net/route.h:263
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81d2ed01)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81d43292)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81d54987)
Location: include/net/route.h:263
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81dfbbca)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81e940d3)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff81e9e147)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea780e)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecee0f)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81edb9ce)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edd8f3)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee45de)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81eeaced)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81eebfc7)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef4f36)
Location: include/net/route.h:258
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ef6d51)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81f0c272)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f1ebb5)
Location: include/net/route.h:258
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81e6cacd)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81ef2883)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_tunnel
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff81efc924)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05fa3)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d196)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81f3aa93)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3cb47)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f43f10)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81f4a64d)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81f4bdc7)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f54816)
Location: include/net/route.h:252
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81f567c1)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff81f6befd)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f7e6b5)
Location: include/net/route.h:252
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/core/filter.c (ffffffff81f2c3a7)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/ipv4/route.c (ffffffff81fb5cc0)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_negative_advice
```
```
In net/ipv4/ip_output.c (ffffffff81fc0864)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca14c)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff202f)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff82000b89)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff82002db9)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff82009e93)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8201075d)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff82011ed7)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201aa70)
Location: include/net/route.h:246
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8201cc71)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
```
```
In net/ipv4/ping.c (ffffffff820324cd)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff82044d60)
Location: include/net/route.h:246
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffff800010c5c634)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c65b18)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d154)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d7d0)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffff800010c95ee8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c98178)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9dfbc)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1f64)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffff800010ca4cf4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010cab128)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cad664)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffff800010cc0810)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffff800010cccca4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (c0d6bd58)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d757a4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (c0d7b4d8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c0d9b820)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c0da46a4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da6040)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da8c4c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c0daed44)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c0db0e2c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c0db7b04)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (c0dba56c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (c0dccb28)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c0dd72f8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (c000000000d5eaa8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d6a2c4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (c000000000d71fa0)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9a284)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c000000000da70e8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da9450)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000daff5c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (c000000000db52b8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c000000000db80f8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (c000000000dc15ac)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc3c2c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (c000000000ddbb98)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c000000000de890c)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffe0007c55be)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007cd276)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1f4e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed176)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffe0007f4eda)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f64f8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f7eda)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffe0007fdbc4)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffe0007fff54)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffe000805d5c)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000807abe)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffe000816fec)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffe00081edda)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff8194c3a3)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8195527e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195a90a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978a10)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81981cb8)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8198346f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8198517f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff8198c23e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff8198e8c7)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8199517f)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819968e2)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff819a76ea)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819b0932)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In drivers/net/vxlan.c (ffffffff8177264d)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_get_route
```
```
In net/ipv4/route.c (ffffffff81905e93)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190ed6e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819143fa)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819324d0)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8193b778)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193cf2f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193ec3f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81945cfe)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81948387)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff8194ec3f)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819503a2)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff819611aa)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel.c (ffffffff819679a5)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev
```
```
In net/ipv4/ipmr.c (ffffffff8196cf62)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff819b6b73)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819bfa4e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c50da)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e31e0)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ec488)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819edc3f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819ef94f)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff819f6a4e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff819f9167)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff819ffa1f)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a01182)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81a11f8a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1b1d2)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
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
In net/ipv4/route.c (ffffffff819c03e3)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c93cd)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cebaa)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed300)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819f634a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f7b81)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa18b)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81a00c6e)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffffffff81a0303a)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a09b29)
Location: include/net/route.h:239
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0b672)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_find_dev
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff81a1c8fc)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a260b2)
Location: include/net/route.h:239
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
</ul>

## Differences
