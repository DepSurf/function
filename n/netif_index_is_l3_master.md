# Function: <code>netif_index_is_l3_master</code>

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
In net/ipv4/route.c (ffffffff81756a2e)
Location: include/net/l3mdev.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_output.c (ffffffff8175f69b)
Location: include/net/l3mdev.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/route.c (ffffffff817d8cd4)
Location: include/net/l3mdev.h:96
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv4/route.c (ffffffff817c3601)
Location: include/net/l3mdev.h:149
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/ip_output.c (ffffffff817cb93b)
Location: include/net/l3mdev.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/route.c (ffffffff8184271a)
Location: include/net/l3mdev.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185da73)
Location: include/net/l3mdev.h:149
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff817f1362)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/ip_output.c (ffffffff817fb59d)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fad6)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff818127a4)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8181b96f)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6178)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81891dc4)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8189a8a8)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938efe)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff818e5cfd)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff818eed71)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992767)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81912c0f)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8191c560)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81946b6b)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81948337)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8194a7b2)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff8196a39c)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8ea1)
Location: include/net/l3mdev.h:128
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff8197535a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8197eac9)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff819ab1ba)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819acdc1)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819aee72)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819d1040)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37a01)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff819abd91)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819b545b)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff819e1e88)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819e3975)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819e5b8c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a07b9a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e539)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81a95df2)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a9f6b2)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81acf720)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ad119a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ad5940)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81af73e4)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6818a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81a9fe1e)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81aa95f6)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81adb729)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81add0fd)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ae1ecf)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81b04284)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b769b0)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81a8ad5e)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81a947c9)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81ac6795)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81ac816c)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81acbba9)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81aeff16)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6532f)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff81b45c7d)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff81b4fc49)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81b84fa5)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81b869da)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81b8a439)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81baff26)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d5b0)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/ip_output.c (ffffffff81cdd6f2)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81d15821)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81d175cb)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81d1dd31)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81d4350a)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcac0d)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/ip_output.c (ffffffff81e9e1b2)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81edba29)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81edde01)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81ee4dca)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81f0c4f6)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9bc1e)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/ip_output.c (ffffffff81efc98f)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81f3aaee)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff81f3d0a5)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff81f4484d)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81f6c183)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbf52)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/ip_output.c (ffffffff81fc08cf)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff82000be4)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff82003205)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8200a84a)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff82032753)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca825)
Location: include/net/l3mdev.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffff800010c5bea8)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffff800010c65b64)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffff800010c96004)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c983b4)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffff800010c9e4c0)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffff800010cc09dc)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37e40)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (c0d6b550)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (c0d757e0)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (c0da47d0)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da627c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c0da929c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c0dccc9c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (c0e38bac)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (c000000000d5e10c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (c000000000d6a334)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (c000000000da7280)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da9784)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (c000000000db05c4)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (c000000000ddbe04)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6947c)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffe0007c4ff2)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffe0007cd2aa)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffe0007f4fd0)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffe0007f66c6)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffe0007f833a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffe000817146)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008742dc)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff8194bc01)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819552cb)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff81981cf8)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819837e5)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819859fc)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819a793a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0dbc9)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff819056f1)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff8190edbb)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff8193b7b8)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff8193d2a5)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff8193f4bc)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819613fa)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca989)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff819b63d1)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819bfa9b)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff819ec4c8)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819edfb5)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819f01cc)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a121da)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78649)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv4/route.c (ffffffff819bfc06)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/ip_output.c (ffffffff819c941b)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/datagram.c (ffffffff819f638d)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffffffff819f7e7f)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/udp.c (ffffffff819faa5a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a1cb4a)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84db9)
Location: include/net/l3mdev.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
</details>
</li>
</ul>

## Differences
