# Function: <code>skb_gro_offset</code>

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
In net/core/skbuff.c (ffffffff8170c598)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2312
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81740073)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81783785)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b47b)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81793bb5)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4d4c)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800c99)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2312
Inline: True
```
```
In net/ipv6/udp_offload.c (ffffffff8180192e)
Location: include/linux/netdevice.h:2312
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/skbuff.c (ffffffff8176f6d8)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817acdb3)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0d15)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8d36)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818012e5)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812dc5)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866c8e)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81872429)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2449
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
In net/core/skbuff.c (ffffffff817994ec)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2446
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817dc403)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81821aa5)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829c06)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818320f5)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818442d5)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8189938e)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a19)
Location: include/linux/netdevice.h:2446
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2446
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
In net/core/skbuff.c (ffffffff817b88be)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2462
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817fbaa3)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8184275c)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184ae56)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854b85)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865b85)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf5be)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd489)
Location: include/linux/netdevice.h:2462
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2462
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
In net/core/skbuff.c (ffffffff8183127e)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2487
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81879463)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c20bc)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818caab6)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4a25)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5cb5)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8194268e)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81952279)
Location: include/linux/netdevice.h:2487
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2487
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
In net/core/skbuff.c (ffffffff8187b75f)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81895856)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818cae35)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81917d25)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920a35)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192af55)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c552)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b4d5)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab7d5)
Location: include/linux/netdevice.h:2573
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2573
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
In net/core/skbuff.c (ffffffff8189c586)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818b74d7)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818f5fc5)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81946455)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194fd55)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958bd5)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c232)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1e05)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e22f5)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2667
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff819ec095)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff818e6e06)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81903308)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81955645)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aaaa5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b45e5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd6a5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d2f82)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40be5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50fb5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2648
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a5b235)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff819191e6)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff819360b8)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8198bae5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1775)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb315)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f42b5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09af2)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a77865)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87bd5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a91e65)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff819f2866)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff81a0ae21)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81a636e5)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf1db)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad916e)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae2b75)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa540)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71c72)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83085)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83b4e)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d025)
Location: include/linux/netdevice.h:2775
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff819f2856)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff81a0c06d)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81a6b835)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb1e1)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b85)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefa35)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07ce9)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b809a6)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92735)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93200)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cc85)
Location: include/linux/netdevice.h:2924
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff819d8a86)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff819f2222)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81a53f95)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6234)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e75)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb185)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af34f5)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f5c4)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81885)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8229b)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd65)
Location: include/linux/netdevice.h:2991
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff81a88a16)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive_list
```
```
In net/core/dev.c (ffffffff81aa40f2)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81b0cca5)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84a44)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f892)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a535)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3a05)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c37681)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d8c5)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e34b)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c58045)
Location: include/linux/netdevice.h:3011
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/gro.c (ffffffff81c54168)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81c935c5)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d152a2)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b92)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2c8d5)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d4722a)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5216)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedfa5)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deebf2)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df9735)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/gro.c (ffffffff81e0984c)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81e4ecb5)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb482)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e0c)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef4195)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f10273)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa691f)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2555)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2c42)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcdda5)
Location: include/net/gro.h:121
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/gro.c (ffffffff81e7c016)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81eaa355)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a542)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f47695)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53a85)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6ff63)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff82007170)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820234d5)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023bd1)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff820496d5)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/gro.c (ffffffff81f3c366)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ethernet/eth.c (ffffffff81f6ce05)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff82000632)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d7d5)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff82019e45)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff82036693)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052e75)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
```
```
In net/ipv6/udp_offload.c (ffffffff820d5fd0)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1615)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff820f25c5)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2d31)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211ba45)
Location: include/net/gro.h:127
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffff800010bb22a0)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffff800010bc9428)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffff800010c36b18)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c95748)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0e84)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa238)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2e44)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d40ecc)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d547b4)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffff800010d5fb20)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (c0ccfa1c)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (c0ce66b0)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (c0d49460)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da3ef4)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad3ac)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c0db69c0)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce66c)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e438a0)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54d7c)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (c0e5f690)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (c000000000c87f9c)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (c000000000ca7024)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (c000000000d2f064)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da6900)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3d50)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc0268)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde4a4)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e75710)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d29c)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (c000000000e9a864)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffe000743b12)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffe0007560d2)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffe0007a8500)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f49b4)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd4da)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe000805070)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818280)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c672)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c122)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffe0008950da)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff818b91e6)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818d6088)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8192b955)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819815e5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b185)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81994055)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9892)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a16ef5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27265)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a314f5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In drivers/net/vxlan.c (ffffffff81771277)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/skbuff.c (ffffffff81873136)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff8188fec8)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e5705)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b0a5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944c45)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194db15)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963352)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3cb5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4025)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff819ee6e5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff8190a1e6)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff819270b8)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8197cae5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebdb5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f5955)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819fe8f5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14132)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a81975)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e15)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0a5)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/skbuff.c (ffffffff8192b2e6)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81948727)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8199f045)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5c65)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffb55)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a685)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1eb22)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e275)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9ef55)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2661
Inline: True
```
```
In net/8021q/vlan_core.c (ffffffff81aa9295)
Location: include/linux/netdevice.h:2661
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
