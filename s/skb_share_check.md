# Function: <code>skb_share_check</code>

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
In net/core/skbuff.c (ffffffff8170a04c)
Location: include/linux/skbuff.h:1310
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81758ea9)
Location: include/linux/skbuff.h:1310
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a4e6)
Location: include/linux/skbuff.h:1310
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8178d216)
Location: include/linux/skbuff.h:1310
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c8ad3)
Location: include/linux/skbuff.h:1310
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81806888)
Location: include/linux/skbuff.h:1310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8180959f)
Location: include/linux/skbuff.h:1310
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81771809)
Location: include/linux/skbuff.h:1411
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff817c5249)
Location: include/linux/skbuff.h:1411
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6945)
Location: include/linux/skbuff.h:1411
Inline: True
```
```
In net/ipv4/arp.c (ffffffff817fa7d6)
Location: include/linux/skbuff.h:1411
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81835d43)
Location: include/linux/skbuff.h:1411
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81878898)
Location: include/linux/skbuff.h:1411
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8187b0af)
Location: include/linux/skbuff.h:1411
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8179e939)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff817f4d59)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6445)
Location: include/linux/skbuff.h:1426
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8182b6a6)
Location: include/linux/skbuff.h:1426
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81867863)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff818ac998)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818af96f)
Location: include/linux/skbuff.h:1426
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff817bd92c)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff818151ea)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81816869)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8184cab6)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8188bff2)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff818d2578)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff818d6167)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81836f7c)
Location: include/linux/skbuff.h:1501
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff818943ba)
Location: include/linux/skbuff.h:1501
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81895a09)
Location: include/linux/skbuff.h:1501
Inline: True
```
```
In net/ipv4/arp.c (ffffffff818cc776)
Location: include/linux/skbuff.h:1501
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff8190d2e2)
Location: include/linux/skbuff.h:1501
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff81957498)
Location: include/linux/skbuff.h:1501
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8195bd07)
Location: include/linux/skbuff.h:1501
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8188142c)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff818e85d6)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9c18)
Location: include/linux/skbuff.h:1512
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81922c0f)
Location: include/linux/skbuff.h:1512
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819646e3)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/packet/af_packet.c (ffffffff819ae5c8)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819b550b)
Location: include/linux/skbuff.h:1512
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818a1f5c)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81915116)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81916e35)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81951a0f)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81999092)
Location: include/linux/skbuff.h:1581
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e51b8)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819ec7db)
Location: include/linux/skbuff.h:1581
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818ecbcc)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81977626)
Location: include/linux/skbuff.h:1671
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978e15)
Location: include/linux/skbuff.h:1671
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819b62da)
Location: include/linux/skbuff.h:1671
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a04f94)
Location: include/linux/skbuff.h:1671
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a54338)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a5b97a)
Location: include/linux/skbuff.h:1671
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8191ecec)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff819adfb6)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819af785)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819ecffa)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bb64)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8b058)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a925aa)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f1f1c)
Location: include/linux/skbuff.h:1692
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81a97e5a)
Location: include/linux/skbuff.h:1692
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9960f)
Location: include/linux/skbuff.h:1692
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/skbuff.h:1692
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b30fe7)
Location: include/linux/skbuff.h:1692
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81b86ad8)
Location: include/linux/skbuff.h:1692
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8da5a)
Location: include/linux/skbuff.h:1692
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819f1f3c)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81aa1dba)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa357f)
Location: include/linux/skbuff.h:1713
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/skbuff.h:1713
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b3fc17)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81b96518)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b9d710)
Location: include/linux/skbuff.h:1713
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff819d822c)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81a8ccea)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e6ef)
Location: include/linux/skbuff.h:1729
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/skbuff.h:1729
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81b2da47)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81b85388)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81b8c81c)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81a8807c)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81b47e22)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b498df)
Location: include/linux/skbuff.h:1758
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/skbuff.h:1758
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81bf3c9b)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81c51698)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81c58bdc)
Location: include/linux/skbuff.h:1758
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81bfd50c)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81cd5092)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f0a)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/arp.c (ffffffff81d22e1c)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81d8c9be)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81df386c)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81dfa2e7)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81dac4fd)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81e95562)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974aa)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/arp.c (ffffffff81eea31c)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81f5abce)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff81fc8647)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81fcea07)
Location: include/linux/skbuff.h:1967
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81e1bc7d)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81ef3d62)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5cda)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/arp.c (ffffffff81f49c4c)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81fba97e)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff82026ed7)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8204a347)
Location: include/linux/skbuff.h:2003
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81ed923d)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81fb7cf2)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9c8a)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/arp.c (ffffffff8200fd6c)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff82087dae)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffff820f7d67)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff8211c7b7)
Location: include/linux/skbuff.h:2010
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffff800010bb9510)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffff800010c5e008)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5ffd8)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffff800010ca2a78)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffff800010cfd130)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d59bec)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffff800010d60324)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c0cd5fa0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (c0d6d8f0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6f7c0)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (c0daf8dc)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (c0e04298)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (c0e583a0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c0e5fe28)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (c000000000c91ac0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (c000000000d60c2c)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d62db8)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (c000000000db61d8)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (c000000000e24be0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (c000000000e912a0)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (c000000000e9b340)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffe000748a90)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffe0007c6bac)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c808e)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffe0007fea1e)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffe0008474be)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/packet/af_packet.c (ffffffe00088eb3c)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffe00089579c)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff818becec)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff8194de26)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f5f5)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8198cdb6)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff819db1f4)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2a6e8)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a31c3a)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81878c2c)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff81907916)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819090e5)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81946876)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81997fb4)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e78d8)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff819eee2a)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff8190fcec)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff819b85f6)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9dc5)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffff819f763a)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a45c74)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a96298)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81a9d7ea)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/skbuff.c (ffffffff81930e1c)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/ipv4/ip_input.c (ffffffff819c1e56)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c3805)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81a0185f)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81a5194c)
Location: include/linux/skbuff.h:1681
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa2f08)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/8021q/vlan_core.c (ffffffff81aa99ea)
Location: include/linux/skbuff.h:1681
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
