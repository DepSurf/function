# Function: <code>ip_route_output_ports</code>

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
In net/ipv4/ip_output.c (ffffffff8175e6bf)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8176474d)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81783ccd)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81794467)
Location: include/net/route.h:148
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff817961a9)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/igmp.c:igmp_send_report
```
```
In net/ipv4/ipmr.c (ffffffff817a93b8)
Location: include/net/route.h:148
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
In net/ipv4/ip_output.c (ffffffff817ca92a)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0c8d)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff817f1284)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81801e17)
Location: include/net/route.h:148
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8180475f)
Location: include/net/route.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81816bf8)
Location: include/net/route.h:148
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
In net/ipv4/ip_output.c (ffffffff817fa5a7)
Location: include/net/route.h:147
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800b20)
Location: include/net/route.h:147
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81822322)
Location: include/net/route.h:147
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81832db3)
Location: include/net/route.h:147
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81835721)
Location: include/net/route.h:147
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81848398)
Location: include/net/route.h:147
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
In net/ipv4/ip_output.c (ffffffff8181a9b3)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820710)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81842f92)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff818540d3)
Location: include/net/route.h:150
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81856c71)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81869aba)
Location: include/net/route.h:150
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
In net/ipv4/ip_output.c (ffffffff81899993)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f6e0)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff818c28f8)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff818d3f53)
Location: include/net/route.h:150
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff818d6b21)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff818ea169)
Location: include/net/route.h:150
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
In net/ipv4/ip_output.c (ffffffff818eddd7)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f40ff)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81918555)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff8192a400)
Location: include/net/route.h:149
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8192d48b)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81940853)
Location: include/net/route.h:149
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
In net/ipv4/ip_output.c (ffffffff8191b5b0)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921c0f)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81946cd5)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81959b90)
Location: include/net/route.h:149
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8195c92b)
Location: include/net/route.h:149
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff819706de)
Location: include/net/route.h:149
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
In net/ipv4/ip_output.c (ffffffff8197d864)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819845e1)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff819ab358)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff819be4cf)
Location: include/net/route.h:150
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c162a)
Location: include/net/route.h:150
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff819d9f5a)
Location: include/net/route.h:150
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
In net/ipv4/ip_output.c (ffffffff819b4204)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bad91)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff819e2028)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff819f50ff)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f81ca)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a10e4c)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffff81a9e33f)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5651)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81acf328)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81ae38ce)
Location: include/net/route.h:157
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81ae5229)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81b02841)
Location: include/net/route.h:157
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
In net/ipv4/ip_output.c (ffffffff81aa8233)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafc61)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81adb32d)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81af0453)
Location: include/net/route.h:157
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81af20f7)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81b10c08)
Location: include/net/route.h:157
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
In net/ipv4/ip_output.c (ffffffff81a93216)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9af71)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81ac638e)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81adbb93)
Location: include/net/route.h:157
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81add8e7)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81afe841)
Location: include/net/route.h:157
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
In net/ipv4/ip_output.c (ffffffff81b4e647)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b563e1)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81b84b9e)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81b9adc3)
Location: include/net/route.h:157
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81b9cd57)
Location: include/net/route.h:157
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81bc005b)
Location: include/net/route.h:157
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
In net/ipv4/ip_output.c (ffffffff81cdbf40)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4521)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81d15440)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81d2c786)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81d2ee26)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81d54a36)
Location: include/net/route.h:171
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
In net/ipv4/ip_output.c (ffffffff81e9c940)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea74d1)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81edbc30)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81ef5126)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81ef6e86)
Location: include/net/route.h:171
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec71)
Location: include/net/route.h:171
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
In net/ipv4/ip_output.c (ffffffff81efb56b)
Location: include/net/route.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05c71)
Location: include/net/route.h:165
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81f3ad00)
Location: include/net/route.h:165
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81f54a06)
Location: include/net/route.h:165
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff81f56903)
Location: include/net/route.h:165
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81f7e771)
Location: include/net/route.h:165
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
In net/ipv4/ip_output.c (ffffffff81fbf493)
Location: include/net/route.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9dd1)
Location: include/net/route.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff82000dee)
Location: include/net/route.h:159
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff8201ac56)
Location: include/net/route.h:159
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
```
```
In net/ipv4/igmp.c (ffffffff8201cdb0)
Location: include/net/route.h:159
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff82044e12)
Location: include/net/route.h:159
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
In net/ipv4/ip_output.c (ffff800010c64980)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6ca54)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffff800010c95cc8)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffff800010caaf54)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cafdf8)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffff800010cccbb8)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (c0d74528)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c0d7b73c)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (c0da4430)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (c0db78f4)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (c0dbb78c)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (c0dd71d0)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (c000000000d68b6c)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (c000000000d7237c)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (c000000000da74c0)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (c000000000dc1328)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc5d00)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (c000000000de87c8)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffe0007cc310)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2366)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffe0007f5148)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffe000805bb6)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000808ef0)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffe00081ec84)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffff81954074)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ac01)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff81981e98)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81994e9f)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81997f6a)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff819b07dc)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffff8190db64)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819146f1)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff8193b958)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff8194e95f)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81951a2a)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff8196ce0c)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffff819be844)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c53d1)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff819ec668)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff819ff73f)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0280a)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a1b07c)
Location: include/net/route.h:151
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
In net/ipv4/ip_output.c (ffffffff819c8181)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819ceea6)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
```
```
In net/ipv4/datagram.c (ffffffff819f6552)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
```
```
In net/ipv4/af_inet.c (ffffffff81a09849)
Location: include/net/route.h:151
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0cd3a)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
```
```
In net/ipv4/ipmr.c (ffffffff81a25f5c)
Location: include/net/route.h:151
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
</details>
</li>
</ul>

## Differences
