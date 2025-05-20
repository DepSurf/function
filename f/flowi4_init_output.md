# Function: <code>flowi4_init_output</code>

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
In net/ipv4/route.c (ffffffff81754d15)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8175e6e6)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764251)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c4a5)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81783cf2)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81784ee2)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81787d0b)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8179448c)
Location: include/net/flow.h:93
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff817961b1)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ping.c (ffffffff817a3bb3)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff817a93b8)
Location: include/net/flow.h:93
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff817ab733)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff817c2ffc)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817cb98d)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0cb2)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e9de2)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff817f12a9)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff817f24dc)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f5454)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81801f67)
Location: include/net/flow.h:93
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8180475f)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff818108ec)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81816bf8)
Location: include/net/flow.h:93
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81819231)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff817f16cb)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff817fb5f3)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800b43)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a57f)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81822345)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818232bd)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81826503)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81832f45)
Location: include/net/flow.h:95
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8183573e)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81841df3)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818483c2)
Location: include/net/flow.h:95
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8184aaa5)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81812f7d)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8181b9c5)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820733)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183acdc)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81842fb5)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81843e09)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81846c12)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818540f6)
Location: include/net/flow.h:95
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81856c8e)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff818636c8)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81869acb)
Location: include/net/flow.h:95
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8186e4a1)
Location: include/net/flow.h:95
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff818925bd)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8189a8fe)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f703)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba90c)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff818c291b)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff818c3795)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c6645)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d3f76)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d6b3e)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff818e3808)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff818ea178)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff818eee3b)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff818e6586)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818eedc3)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4124)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f3cd)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8191856d)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81919339)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191bf57)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8192a418)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192d490)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff8193a083)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81940858)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81945786)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff819133e2)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8191c5b2)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921c34)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d7fd)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81946ced)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81947bcc)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a505)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81959ba8)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195c930)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff8196a05c)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819706e3)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81975b26)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81975a11)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197e8d8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845f8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1bfe)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ab378)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819ac8b7)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819aec08)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819be4eb)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c162f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff819d0be3)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819d9f5f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff819df68a)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff819ac421)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b5278)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bada8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d88be)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819e2048)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e3475)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e5935)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819f511b)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f81cf)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a07737)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a10e51)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a166cf)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81a963f6)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81a9f4d3)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5668)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5321)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81acf348)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ad0d37)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad56df)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ae36f1)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/igmp.c (ffffffff81ae522e)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81af6f64)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b02846)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b0769c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81aa0496)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81aa9413)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc78)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0fd2)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81adb34d)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81adcc93)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1ca2)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81af0271)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/igmp.c (ffffffff81af2101)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81b03e23)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81b10c0d)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b15a99)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81a8b3d6)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81a945da)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af88)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbfa0)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81ac63ae)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac7d2d)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb956)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81adb921)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81add8f1)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81aefaa3)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81afe846)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81b038a7)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81b46316)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81b4fa5a)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563f8)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b790a0)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81b84bbe)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b8658d)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8a1e6)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81b9ab61)
Location: include/net/flow.h:96
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81b9cd61)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81bafab3)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81bc0060)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81bc5b39)
Location: include/net/flow.h:96
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81cd315f)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81cdd4dc)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4541)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08614)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d15463)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d16f6d)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1daa0)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81d2c7a6)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81d2ee30)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81d4307a)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81d54a3b)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae1e)
Location: include/net/flow.h:97
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81e93297)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81e9df9e)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74f1)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81eceb51)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81edbc53)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edd758)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4b61)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ef5146)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81ef6e90)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81f0c05f)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec81)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81f2528e)
Location: include/net/flow.h:92
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81ef1a37)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81efc768)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c91)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ceed)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81f3ad23)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3c9ce)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f4457c)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81f54a26)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81f5690d)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81f6bd3a)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81f7e781)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81f84e2a)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81fb5b87)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81fc06a8)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9dfe)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1d5e)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff82000e25)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff82002c52)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a55a)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8201ac83)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff8201cdba)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff82032303)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff82044e29)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff8204b5a0)
Location: include/net/flow.h:93
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffff800010c5c510)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c659f8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca64)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d67c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffff800010c95cd8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c9807c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9e294)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010caaf74)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cafdfc)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffff800010cc06b0)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffff800010ccccec)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffff800010cd2370)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (c0d6bc38)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d75670)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c0d7b764)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c0d9b624)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c0da4460)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5ef0)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da9090)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db7924)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (c0dbb790)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (c0dcc99c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c0dd71d4)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (c0ddc21c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (c000000000d5e94c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d6a16c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c000000000d723f8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9a06c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c000000000da7540)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da9318)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000db041c)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dc13a4)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc5d10)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (c000000000ddba00)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (c000000000de87d0)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (c000000000df07f4)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffe0007c54d2)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007cd146)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2382)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ecffc)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffe0007f5166)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f63fc)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f810e)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffe000805d08)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000808f02)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffe000816e32)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffe00081ec96)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffe0008236fa)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff8194c291)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819550e8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ac18)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197872e)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81981eb8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819832e5)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819857a5)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81994ebb)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81997f6f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff819a74d7)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff819b07e1)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff819b5d5f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff81905d81)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190ebd8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914708)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819321ee)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8193b978)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193cda5)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193f265)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8194e97b)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81951a2f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81960f97)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff8196ce11)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81972b4f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff819b6a61)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819bf8b8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53e8)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2efe)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ec688)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819edab5)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819eff75)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819ff75b)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0280f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a11d77)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a1b081)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a205ff)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
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
In net/ipv4/route.c (ffffffff819c02d1)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c9237)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ceebd)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed01e)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819f6572)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f79fc)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa7fc)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a09865)
Location: include/net/flow.h:98
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0cd3f)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ping.c (ffffffff81a1c6e9)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffffffff81a25f61)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/syncookies.c (ffffffff81a2baff)
Location: include/net/flow.h:98
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
</details>
</li>
</ul>

## Differences
