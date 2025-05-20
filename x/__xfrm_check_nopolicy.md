# Function: <code>__xfrm_check_nopolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5565)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7212)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d5b3)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b30)
Location: include/net/xfrm.h:1091
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebcc)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d25d3f)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b9a6)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d1af)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbb931)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe560)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0a22)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc939)
Location: include/net/xfrm.h:1091
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/ip_input.c (ffffffff81e9546e)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81e97847)
Location: include/net/xfrm.h:1132
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecde8a)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edcbda)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee070a)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb853)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f552b2)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81f5a9d2)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87b62)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8cb92)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f8f847)
Location: include/net/xfrm.h:1132
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a6e2)
Location: include/net/xfrm.h:1132
Inline: True
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
In net/ipv4/ip_input.c (ffffffff81ef3c4c)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6084)
Location: include/net/xfrm.h:1138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ccb3)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3be03)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f9c3)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b191)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4d10)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81fba740)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe7ff3)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fed343)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff0086)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb0f3)
Location: include/net/xfrm.h:1138
Inline: True
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
In net/ipv4/ip_input.c (ffffffff81fb7bdc)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81fba014)
Location: include/net/xfrm.h:1138
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2503)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001f23)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82005813)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff820112a1)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff820823b0)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff82087b70)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b6233)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820baf43)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820bdc56)
Location: include/net/xfrm.h:1138
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8b03)
Location: include/net/xfrm.h:1138
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
