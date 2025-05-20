# Function: <code>__xfrm_check_dev_nopolicy</code>

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
In net/ipv4/ip_input.c (ffffffff81cd557b)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7226)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d5c9)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffffffff81d17b44)
Location: include/net/xfrm.h:1100
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ebe0)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d25d53)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b9b4)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d1c4)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbb945)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe570)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (ffffffff81dc0a36)
Location: include/net/xfrm.h:1100
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc94d)
Location: include/net/xfrm.h:1100
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
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81e97847)
Location: include/net/xfrm.h:1141
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecde9d)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edcbed)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee071d)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb853)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81f552b2)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81f5a9d2)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87bc2)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8cbf2)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f8f847)
Location: include/net/xfrm.h:1141
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a742)
Location: include/net/xfrm.h:1141
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
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6084)
Location: include/net/xfrm.h:1147
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2ccc6)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3be16)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f9d6)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b191)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4d10)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81fba740)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe8006)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fed356)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff0086)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb106)
Location: include/net/xfrm.h:1147
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
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81fba014)
Location: include/net/xfrm.h:1147
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2516)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001f36)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/udp.c (ffffffff82005826)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff820112a1)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff820823b0)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff82087b70)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b6246)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820baf56)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820bdc56)
Location: include/net/xfrm.h:1147
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8b16)
Location: include/net/xfrm.h:1147
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
