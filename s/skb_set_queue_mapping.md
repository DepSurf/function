# Function: <code>skb_set_queue_mapping</code>

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
In net/core/dev.c (ffffffff8171ccd4)
Location: include/linux/skbuff.h:3403
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4bd9)
Location: include/linux/skbuff.h:3403
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a83d4)
Location: include/linux/skbuff.h:3403
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f8e99)
Location: include/linux/skbuff.h:3403
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff818036dd)
Location: include/linux/skbuff.h:3403
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
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
In net/core/dev.c (ffffffff8178546a)
Location: include/linux/skbuff.h:3610
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812845)
Location: include/linux/skbuff.h:3610
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81815ab4)
Location: include/linux/skbuff.h:3610
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868689)
Location: include/linux/skbuff.h:3610
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff8187479d)
Location: include/linux/skbuff.h:3610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
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
In net/core/dev.c (ffffffff817b2a7a)
Location: include/linux/skbuff.h:3662
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843d45)
Location: include/linux/skbuff.h:3662
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81847264)
Location: include/linux/skbuff.h:3662
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81894fb8)
Location: include/linux/skbuff.h:3662
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189b4d9)
Location: include/linux/skbuff.h:3662
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff818a8d8d)
Location: include/linux/skbuff.h:3662
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
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
In net/core/dev.c (ffffffff817d027a)
Location: include/linux/skbuff.h:3716
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:3716
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818655d5)
Location: include/linux/skbuff.h:3716
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81868c60)
Location: include/linux/skbuff.h:3716
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818bb310)
Location: include/linux/skbuff.h:3716
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c1281)
Location: include/linux/skbuff.h:3716
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff818cf91d)
Location: include/linux/skbuff.h:3716
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81849bdd)
Location: include/linux/skbuff.h:3907
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/core/netpoll.c (0)
Location: include/linux/skbuff.h:3907
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5725)
Location: include/linux/skbuff.h:3907
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff818e9194)
Location: include/linux/skbuff.h:3907
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193e326)
Location: include/linux/skbuff.h:3907
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819444ba)
Location: include/linux/skbuff.h:3907
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81954890)
Location: include/linux/skbuff.h:3907
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81893a4e)
Location: include/linux/skbuff.h:3917
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_pick_tx
```
```
In net/core/netpoll.c (ffffffff818bf414)
Location: include/linux/skbuff.h:3917
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193bfd8)
Location: include/linux/skbuff.h:3917
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff8193f6e4)
Location: include/linux/skbuff.h:3917
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8199725d)
Location: include/linux/skbuff.h:3917
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199cf7b)
Location: include/linux/skbuff.h:3917
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
In net/core/dev.c (ffffffff818b446e)
Location: include/linux/skbuff.h:4080
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_pick_tx
```
```
In net/core/netpoll.c (ffffffff818e8231)
Location: include/linux/skbuff.h:4080
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bce9)
Location: include/linux/skbuff.h:4080
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff8196f47e)
Location: include/linux/skbuff.h:4080
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cdb42)
Location: include/linux/skbuff.h:4080
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d3372)
Location: include/linux/skbuff.h:4080
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
In net/core/dev.c (ffffffff81900d8e)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81938472)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a39)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff819d8b80)
Location: include/linux/skbuff.h:4187
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c16b)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a423b9)
Location: include/linux/skbuff.h:4187
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
In net/core/dev.c (ffffffff819330be)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff8196b332)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095a9)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a0f9e0)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a72deb)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a79019)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffff81a07f27)
Location: include/linux/skbuff.h:4311
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81a3eae2)
Location: include/linux/skbuff.h:4311
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8ec9)
Location: include/linux/skbuff.h:4311
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81b032a0)
Location: include/linux/skbuff.h:4311
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d2d6)
Location: include/linux/skbuff.h:4311
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b76c09)
Location: include/linux/skbuff.h:4311
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
In net/core/dev.c (ffffffff81a0960f)
Location: include/linux/skbuff.h:4340
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81a41882)
Location: include/linux/skbuff.h:4340
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06eb9)
Location: include/linux/skbuff.h:4340
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81b11400)
Location: include/linux/skbuff.h:4340
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bd7e)
Location: include/linux/skbuff.h:4340
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b859d9)
Location: include/linux/skbuff.h:4340
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
In net/core/dev.c (ffffffff819eff7f)
Location: include/linux/skbuff.h:4404
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81a2691b)
Location: include/linux/skbuff.h:4404
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2611)
Location: include/linux/skbuff.h:4404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81aff02f)
Location: include/linux/skbuff.h:4404
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a84e)
Location: include/linux/skbuff.h:4404
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b74689)
Location: include/linux/skbuff.h:4404
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
In net/core/dev.c (ffffffff81aa13af)
Location: include/linux/skbuff.h:4443
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81adb69b)
Location: include/linux/skbuff.h:4443
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b21)
Location: include/linux/skbuff.h:4443
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81bc21fc)
Location: include/linux/skbuff.h:4443
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c326ae)
Location: include/linux/skbuff.h:4443
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ef73)
Location: include/linux/skbuff.h:4443
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
In net/core/dev.c (ffffffff81c192a9)
Location: include/linux/skbuff.h:4865
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81c5cb8f)
Location: include/linux/skbuff.h:4865
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d462e1)
Location: include/linux/skbuff.h:4865
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81d527b2)
Location: include/linux/skbuff.h:4865
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfea3)
Location: include/linux/skbuff.h:4865
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9cf8)
Location: include/linux/skbuff.h:4865
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
In net/core/dev.c (ffffffff81dca2a9)
Location: include/linux/skbuff.h:4761
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81e1328f)
Location: include/linux/skbuff.h:4761
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f6db)
Location: include/linux/skbuff.h:4761
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81f1ca97)
Location: include/linux/skbuff.h:4761
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1226)
Location: include/linux/skbuff.h:4761
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fab95a)
Location: include/linux/skbuff.h:4761
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
In net/core/dev.c (ffffffff81e3ae29)
Location: include/linux/skbuff.h:4793
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81e86bcf)
Location: include/linux/skbuff.h:4793
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f3cb)
Location: include/linux/skbuff.h:4793
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81f7c577)
Location: include/linux/skbuff.h:4793
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001ace)
Location: include/linux/skbuff.h:4793
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200c0fa)
Location: include/linux/skbuff.h:4793
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
In net/core/dev.c (ffffffff81ef91b7)
Location: include/linux/skbuff.h:4833
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff81f48bdf)
Location: include/linux/skbuff.h:4833
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035afb)
Location: include/linux/skbuff.h:4833
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff82042c67)
Location: include/linux/skbuff.h:4833
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d08d1)
Location: include/linux/skbuff.h:4833
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff820db0c4)
Location: include/linux/skbuff.h:4833
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
In net/core/dev.c (ffff800010bd10a0)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffff800010c10f2c)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2958)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffff800010ccc994)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffff800010d3b8e4)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d45f4c)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (c0cebd3c)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (c0d28d60)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (c0dce1a8)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (c0dd6fdc)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (c0e3dfcc)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e47d7c)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (c000000000caf340)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (c000000000cfe090)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde1cc)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (c000000000de7490)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6f168)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7b9f0)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffe00075b694)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffe00078dbb0)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817daa)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffe00081dd8a)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffe0008781de)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00087dde6)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffff818d30be)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff8190b302)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9349)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff819af410)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a1247b)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a186a9)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffff8188cf4e)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff818c50da)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e09)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff8196ba40)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cf23b)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d5469)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffff819240be)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff8195c332)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13be9)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a19cb0)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cefb)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a83129)
Location: include/linux/skbuff.h:4271
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
In net/core/dev.c (ffffffff8194552e)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/core/netpoll.c (ffffffff8197dce0)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5c9)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff81a24abc)
Location: include/linux/skbuff.h:4271
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a8974b)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f9f6)
Location: include/linux/skbuff.h:4271
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
</details>
</li>
</ul>

## Differences
