# Function: <code>skb_clear_hash_if_not_l4</code>

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
In net/ipv4/ip_tunnel_core.c (ffffffff817a4b9a)
Location: include/linux/skbuff.h:957
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a83b6)
Location: include/linux/skbuff.h:957
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f8e7b)
Location: include/linux/skbuff.h:957
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81812838)
Location: include/linux/skbuff.h:1054
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81815a96)
Location: include/linux/skbuff.h:1054
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8186866b)
Location: include/linux/skbuff.h:1054
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81843d38)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81847246)
Location: include/linux/skbuff.h:1069
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81894f90)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189b4bb)
Location: include/linux/skbuff.h:1069
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff818655c8)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81868c42)
Location: include/linux/skbuff.h:1062
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818bb2ef)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c1263)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff818e5718)
Location: include/linux/skbuff.h:1136
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e9176)
Location: include/linux/skbuff.h:1136
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193e305)
Location: include/linux/skbuff.h:1136
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8194449c)
Location: include/linux/skbuff.h:1136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff8193bfbb)
Location: include/linux/skbuff.h:1141
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8193f6cd)
Location: include/linux/skbuff.h:1141
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81997246)
Location: include/linux/skbuff.h:1141
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199cf64)
Location: include/linux/skbuff.h:1141
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff8196bcd5)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196f467)
Location: include/linux/skbuff.h:1161
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cdb2b)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d335b)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a25)
Location: include/linux/skbuff.h:1213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819d8b65)
Location: include/linux/skbuff.h:1213
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c150)
Location: include/linux/skbuff.h:1213
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a4239e)
Location: include/linux/skbuff.h:1213
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a09595)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a0f9c5)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a72dd0)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a78ffe)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af8eb5)
Location: include/linux/skbuff.h:1241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b03285)
Location: include/linux/skbuff.h:1241
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d2bd)
Location: include/linux/skbuff.h:1241
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b76bee)
Location: include/linux/skbuff.h:1241
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81b06ea5)
Location: include/linux/skbuff.h:1258
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b113e5)
Location: include/linux/skbuff.h:1258
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bd65)
Location: include/linux/skbuff.h:1258
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b859be)
Location: include/linux/skbuff.h:1258
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af2604)
Location: include/linux/skbuff.h:1266
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81aff014)
Location: include/linux/skbuff.h:1266
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a835)
Location: include/linux/skbuff.h:1266
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b7466e)
Location: include/linux/skbuff.h:1266
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b14)
Location: include/linux/skbuff.h:1279
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bc21e1)
Location: include/linux/skbuff.h:1279
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32695)
Location: include/linux/skbuff.h:1279
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ef58)
Location: include/linux/skbuff.h:1279
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81d462d4)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d5279b)
Location: include/linux/skbuff.h:1586
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfe8a)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ce1)
Location: include/linux/skbuff.h:1586
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f6c4)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1ca80)
Location: include/linux/skbuff.h:1430
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa120d)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fab943)
Location: include/linux/skbuff.h:1430
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f3b4)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7c560)
Location: include/linux/skbuff.h:1449
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001ab5)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200c0e3)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff82035ae4)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82042c50)
Location: include/linux/skbuff.h:1456
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d08b8)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff820db0ad)
Location: include/linux/skbuff.h:1456
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffff800010cc2938)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010ccc980)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffff800010d3b8d4)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d45f38)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (c0dce178)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dd6fcc)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (c0e3dfcc)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e47d74)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (c000000000dde1a4)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c000000000de7474)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6f154)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7b9d4)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffe000817d9c)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffe00081dd6e)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffe0008781c8)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00087ddca)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff819a9335)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819af3f5)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a12460)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a1868e)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81962df5)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196ba25)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cf220)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d544e)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a13bd5)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a19c95)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cee0)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8310e)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5b5)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a24aa1)
Location: include/linux/skbuff.h:1209
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a89730)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f9db)
Location: include/linux/skbuff.h:1209
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
</details>
</li>
</ul>

## Differences
