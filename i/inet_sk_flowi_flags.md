# Function: <code>inet_sk_flowi_flags</code>

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
In net/ipv4/route.c (ffffffff8175538c)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764235)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
```
```
In net/ipv4/datagram.c (0)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81784ec3)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81787cf0)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/ipv4/ping.c (ffffffff817a3ba6)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:282
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff817ab71f)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff817ac1ba)
Location: include/net/inet_sock.h:282
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff817c151d)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff817ca93c)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0c9d)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff817f1294)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff817f24bd)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff817f5438)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81801e27)
Location: include/net/inet_sock.h:301
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:301
Inline: True
```
```
In net/ipv4/ping.c (ffffffff818108d7)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:301
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8181921f)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff818194fa)
Location: include/net/inet_sock.h:301
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff817f0aa8)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff817fa5b4)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800b29)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff8182232b)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81823297)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81826521)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81832dbc)
Location: include/net/inet_sock.h:302
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:302
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81841dd7)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:302
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8184aa93)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8184ad8a)
Location: include/net/inet_sock.h:302
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81810ef5)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8181a9bc)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820719)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81842f9b)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81843dd5)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81846c0b)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818540dc)
Location: include/net/inet_sock.h:306
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:306
Inline: True
```
```
In net/ipv4/ping.c (ffffffff818636ac)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:306
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8186e488)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8186e7f3)
Location: include/net/inet_sock.h:306
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff818904d5)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8189999c)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f6e9)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff818c2901)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff818c376c)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff818c663e)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d3f5c)
Location: include/net/inet_sock.h:310
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:310
Inline: True
```
```
In net/ipv4/ping.c (ffffffff818e37ec)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:310
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff818eee22)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff818ef1b3)
Location: include/net/inet_sock.h:310
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff818e3c73)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff818ede0a)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4124)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff8191856d)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81919318)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8191bf57)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8192a418)
Location: include/net/inet_sock.h:336
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:336
Inline: True
```
```
In net/ipv4/ping.c (ffffffff8193a07d)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:336
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8194573a)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81945b53)
Location: include/net/inet_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81910b53)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8191b5cb)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921c34)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81946ced)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81947bab)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a505)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81959ba8)
Location: include/net/inet_sock.h:352
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:352
Inline: True
```
```
In net/ipv4/ping.c (ffffffff8196a03b)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:352
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81975ada)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81975e73)
Location: include/net/inet_sock.h:352
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81972d99)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8197d874)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845f8)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff819ab378)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff819ac88f)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819aec08)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819be4eb)
Location: include/net/inet_sock.h:348
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:348
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819d0bc2)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:348
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff819df62d)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff819dfa02)
Location: include/net/inet_sock.h:348
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff819a9709)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819b4214)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bada8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff819e2048)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff819e344d)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e5935)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819f511b)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a0771e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81a16671)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a16a32)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81a918f1)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81a9e357)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5668)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81acf348)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81ad0d0f)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad56df)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ae38ea)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81af6f5e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81b0763e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b07a72)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81a9b771)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/route.c:build_sk_flow_key
```
```
In net/ipv4/ip_output.c (ffffffff81aa824b)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc78)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81adb34d)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81adcc6b)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1ca2)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81af046f)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81b03e00)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81b15a3d)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b15e54)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81a88509)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81a9322e)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af88)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81ac63ae)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81ac7d0b)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acb956)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81adbbaf)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81aefa80)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:343
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81b0384b)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81b03c5a)
Location: include/net/inet_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81b43d09)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81b4e65f)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563f8)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81b84bbe)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81b8656b)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8a1e6)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81b9addf)
Location: include/net/inet_sock.h:342
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:342
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81bafa90)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:342
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81bc5adb)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81bc5f0a)
Location: include/net/inet_sock.h:342
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81cd0831)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81cdbf51)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4537)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81d15455)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81d16f4d)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1daa0)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81d2c79c)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:360
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81d4305d)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:360
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81d5add3)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81d5b221)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81e909f1)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81e9c951)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74e7)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81edbc45)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81edd738)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4b45)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81ef513c)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:360
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f0c042)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:360
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f25243)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81f256b1)
Location: include/net/inet_sock.h:360
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81eef171)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81efb57c)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c87)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81f3ad15)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff81f3c99d)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f44512)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81f54a1c)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:362
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81f6bcce)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:362
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81f84de8)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81f85241)
Location: include/net/inet_sock.h:362
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81fb32eb)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81fbf4ac)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9de7)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff82000e04)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff82002be9)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a4bd)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8201ac6c)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:394
Inline: True
```
```
In net/ipv4/ping.c (ffffffff8203228c)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:394
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff8204b53a)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff8204b8f1)
Location: include/net/inet_sock.h:394
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffff800010c59184)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffff800010c64998)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca64)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffff800010c95cd8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffff800010c98074)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9e294)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010caaf70)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffff800010cc069c)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffff800010cd236c)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffff800010cd268c)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (c0d68e8c)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c0d74534)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c0d7b74c)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (c0da4450)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (c0da5ee8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da9090)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db7904)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (c0dcc978)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (c0ddc218)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (c0ddc594)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (c000000000d5b078)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (c000000000d68b84)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72398)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (c000000000da74e0)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (c000000000da9308)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000db03d0)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dc1348)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (c000000000ddb9a8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (c000000000df07e0)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (c000000000df0c60)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffe0007c3046)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffe0007cc318)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d236e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffe0007f514e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffe0007f63f2)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f810a)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffe000805bbc)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffe000816e1a)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffe0008236c6)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffe0008239d6)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81949579)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff81954084)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ac18)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff81981eb8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff819832bd)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819857a5)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81994ebb)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff819a74be)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff819b5d01)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff819b60c2)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81903069)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff8190db74)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914708)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff8193b978)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff8193cd7d)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193f265)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8194e97b)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81960f7e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81972af1)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81972eb2)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff819b3d49)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819be854)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53e8)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff819ec688)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff819eda8d)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819eff75)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff819ff75b)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a11d5e)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81a205a1)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a20962)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff819bd437)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
```
In net/ipv4/ip_output.c (ffffffff819c8198)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ceebd)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/datagram.c (ffffffff819f6572)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/raw.c (ffffffff819f79d1)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819fa7fc)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81a09865)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/ping.c (ffffffff81a1c6ce)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/inet_sock.h:349
Inline: True
```
```
In net/ipv4/syncookies.c (ffffffff81a2baa1)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/netfilter.c (ffffffff81a2be82)
Location: include/net/inet_sock.h:349
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
</details>
</li>
</ul>

## Differences
