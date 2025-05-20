# Function: <code>dev_hard_header</code>

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
In net/core/neighbour.c (ffffffff81725919)
Location: include/linux/netdevice.h:2522
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_connected_output
  - net/core/neighbour.c:neigh_xmit
```
```
In net/ipv4/arp.c (ffffffff8178bb62)
Location: include/linux/netdevice.h:2522
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff818073e6)
Location: include/linux/netdevice.h:2522
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
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
In net/core/neighbour.c (ffffffff81793298)
Location: include/linux/netdevice.h:2724
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff817f91a6)
Location: include/linux/netdevice.h:2724
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81879b8d)
Location: include/linux/netdevice.h:2724
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff817c0b68)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff8182a076)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff818ae28e)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff817df23f)
Location: include/linux/netdevice.h:2688
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff8184b2a9)
Location: include/linux/netdevice.h:2688
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff818d4c2a)
Location: include/linux/netdevice.h:2688
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81859afb)
Location: include/linux/netdevice.h:2713
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff818caf19)
Location: include/linux/netdevice.h:2713
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff819596a9)
Location: include/linux/netdevice.h:2713
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff818a50d0)
Location: include/linux/netdevice.h:2819
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81921423)
Location: include/linux/netdevice.h:2819
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff819b0768)
Location: include/linux/netdevice.h:2819
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff818c8483)
Location: include/linux/netdevice.h:2913
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81950233)
Location: include/linux/netdevice.h:2913
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff819e7fca)
Location: include/linux/netdevice.h:2913
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81914fb4)
Location: include/linux/netdevice.h:2894
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff819b4af3)
Location: include/linux/netdevice.h:2894
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81a54bb9)
Location: include/linux/netdevice.h:2894
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81947624)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff819eb823)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81a8b7a9)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81a17786)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81ad9903)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81b87531)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
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
In net/core/neighbour.c (ffffffff81a17a56)
Location: include/linux/netdevice.h:3170
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81ae6353)
Location: include/linux/netdevice.h:3170
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81b97079)
Location: include/linux/netdevice.h:3170
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
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
In net/core/neighbour.c (ffffffff819fe978)
Location: include/linux/netdevice.h:3237
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81ad1638)
Location: include/linux/netdevice.h:3237
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81b86079)
Location: include/linux/netdevice.h:3237
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
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
In net/core/neighbour.c (ffffffff81ab0b0a)
Location: include/linux/netdevice.h:3257
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81b90268)
Location: include/linux/netdevice.h:3257
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81c5242f)
Location: include/linux/netdevice.h:3257
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
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
In net/core/neighbour.c (ffffffff81c29bb0)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81d21678)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81df4439)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mctp/route.c (ffffffff81e38dfc)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
In net/core/neighbour.c (ffffffff81ddc8f0)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81ee8a88)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81fc91a9)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mctp/route.c (ffffffff8201208c)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
In net/core/neighbour.c (ffffffff81e4d63e)
Location: include/linux/netdevice.h:3136
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81f48448)
Location: include/linux/netdevice.h:3136
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff82029aae)
Location: include/linux/netdevice.h:3136
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mctp/route.c (ffffffff8208ee70)
Location: include/linux/netdevice.h:3136
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
In net/core/neighbour.c (ffffffff81f0c39b)
Location: include/linux/netdevice.h:3215
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff8200e5a5)
Location: include/linux/netdevice.h:3215
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff820f9592)
Location: include/linux/netdevice.h:3215
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mctp/route.c (ffffffff82165316)
Location: include/linux/netdevice.h:3215
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_output
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
In net/core/neighbour.c (ffff800010be8a48)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffff800010ca1394)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffff800010d5a24c)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (c0d01c04)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (c0dae280)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (c0e58d2c)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (c000000000ccb0e8)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (c000000000db4464)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (c000000000e94600)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffe00076ce74)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffe0007fd922)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffe0008900f0)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff818e75f4)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff8198b676)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81a2ae39)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff818a1434)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81945136)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff819e8029)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81938624)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff819f5e63)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81a969e9)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/neighbour.c (ffffffff81959e34)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_connected_output
```
```
In net/ipv4/arp.c (ffffffff81a00063)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_create
```
```
In net/packet/af_packet.c (ffffffff81aa3663)
Location: include/linux/netdevice.h:2907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
