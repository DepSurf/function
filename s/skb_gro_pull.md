# Function: <code>skb_gro_pull</code>

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
In net/ethernet/eth.c (ffffffff817400e0)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817837cb)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b52a)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81793d09)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e25)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cca)
Location: include/linux/netdevice.h:2322
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff817ace24)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0d5b)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f85a2)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8180145c)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812f0a)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8187245a)
Location: include/linux/netdevice.h:2459
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff817dc474)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81821aeb)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829452)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8183226c)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8184441a)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a4a)
Location: include/linux/netdevice.h:2456
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff817fbb20)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818427a8)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184abff)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854d41)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865c6d)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4c1)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff818794e0)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c2108)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818ca8a2)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4be1)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5d9d)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819522b1)
Location: include/linux/netdevice.h:2497
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff818caebc)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81917d82)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8192041b)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b154)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c62f)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab83c)
Location: include/linux/netdevice.h:2583
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ethernet/eth.c (ffffffff818f604e)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819464b3)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194f120)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958dce)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c310)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2358)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec141)
Location: include/linux/netdevice.h:2677
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
In net/ethernet/eth.c (ffffffff819556ce)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aab03)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b3915)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd88b)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d305d)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51012)
Location: include/linux/netdevice.h:2658
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b2d4)
Location: include/linux/netdevice.h:2658
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
In net/ethernet/eth.c (ffffffff8198bb6e)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e17d3)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ea645)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f449b)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09bcd)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c32)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91f04)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (ffffffff81a6376e)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acee43)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad83d0)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae2d5c)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa33d)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830e2)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d0c4)
Location: include/linux/netdevice.h:2785
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
In net/ethernet/eth.c (ffffffff81a6b8be)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adae4f)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae58a6)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefc29)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07add)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b9278e)
Location: include/linux/netdevice.h:2934
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd24)
Location: include/linux/netdevice.h:2934
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
In net/ethernet/eth.c (ffffffff81a5401e)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5e93)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0b24)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb372)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af32dd)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818e1)
Location: include/linux/netdevice.h:3001
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8be04)
Location: include/linux/netdevice.h:3001
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
In net/ethernet/eth.c (ffffffff81b0cd2e)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b846a3)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f544)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a722)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb37ed)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d921)
Location: include/linux/netdevice.h:3021
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c580e4)
Location: include/linux/netdevice.h:3021
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
In net/ethernet/eth.c (ffffffff81c93650)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14ed7)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d2084f)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2cacf)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d47030)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee001)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df97f7)
Location: include/net/gro.h:131
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
In net/ethernet/eth.c (ffffffff81e4ed47)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb040)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7aaf)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef4398)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f10148)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc25bc)
Location: include/net/gro.h:131
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcde1f)
Location: include/net/gro.h:131
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
In net/ethernet/eth.c (ffffffff81eaa3e7)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a110)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f4732f)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53c8f)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe38)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8202353c)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8204974f)
Location: include/net/gro.h:137
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
In net/ethernet/eth.c (ffffffff81f6ce97)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff82000200)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d46f)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201a04f)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff82036568)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f266e)
Location: include/net/gro.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211babf)
Location: include/net/gro.h:137
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
In net/ethernet/eth.c (ffff800010c36ba8)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c95790)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca021c)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa438)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f38)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d547f4)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fbe8)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (c0d49504)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da3f40)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad164)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c0db6c24)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce75c)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54dc8)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f754)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (c000000000d2f114)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da695c)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3a4c)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc04e4)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde5b8)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d310)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a944)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (ffffffe0007a85a4)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f49f8)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc938)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe000805296)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818396)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c150)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe000895192)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (ffffffff8192b9de)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81981643)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198a4b5)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8199423b)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a996d)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a272c2)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a31594)
Location: include/linux/netdevice.h:2671
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
In drivers/net/vxlan.c (ffffffff817712e3)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e578e)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b103)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81943f75)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194dcfb)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196342d)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4082)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee784)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (ffffffff8197cb6e)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebe13)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f4c85)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819feadb)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1420d)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e72)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d144)
Location: include/linux/netdevice.h:2671
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
In net/ethernet/eth.c (ffffffff8199f0d7)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5cc3)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819fee60)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a8cf)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ec06)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9efb6)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa933d)
Location: include/linux/netdevice.h:2671
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
