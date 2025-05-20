# Function: <code>skb_gro_postpull_rcsum</code>

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
In net/ethernet/eth.c (ffffffff817400e5)
Location: include/linux/netdevice.h:2355
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b52d)
Location: include/linux/netdevice.h:2355
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e29)
Location: include/linux/netdevice.h:2355
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800ddf)
Location: include/linux/netdevice.h:2355
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff817ace2a)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f85a6)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812f0e)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8187257b)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff817dc47a)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829456)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8184441e)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6b6b)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff817fbb26)
Location: include/linux/netdevice.h:2510
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184ac03)
Location: include/linux/netdevice.h:2510
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865c71)
Location: include/linux/netdevice.h:2510
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd5d2)
Location: include/linux/netdevice.h:2510
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff818794e6)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818ca8a6)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5da1)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819523c2)
Location: include/linux/netdevice.h:2535
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff818caec2)
Location: include/linux/netdevice.h:2621
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8192041f)
Location: include/linux/netdevice.h:2621
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c633)
Location: include/linux/netdevice.h:2621
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab955)
Location: include/linux/netdevice.h:2621
Inline: True
Inline callers:
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
In net/ethernet/eth.c (ffffffff818f6054)
Location: include/linux/netdevice.h:2715
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194f124)
Location: include/linux/netdevice.h:2715
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c314)
Location: include/linux/netdevice.h:2715
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2479)
Location: include/linux/netdevice.h:2715
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec145)
Location: include/linux/netdevice.h:2715
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
In net/ethernet/eth.c (ffffffff819556d2)
Location: include/linux/netdevice.h:2696
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b391b)
Location: include/linux/netdevice.h:2696
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d3061)
Location: include/linux/netdevice.h:2696
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a5113b)
Location: include/linux/netdevice.h:2696
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b2d8)
Location: include/linux/netdevice.h:2696
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
In net/ethernet/eth.c (ffffffff8198bb72)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ea64b)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09bd1)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87d5b)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91f08)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (ffffffff81a63772)
Location: include/linux/netdevice.h:2823
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad83d8)
Location: include/linux/netdevice.h:2823
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa341)
Location: include/linux/netdevice.h:2823
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b8320e)
Location: include/linux/netdevice.h:2823
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d0c8)
Location: include/linux/netdevice.h:2823
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
In net/ethernet/eth.c (ffffffff81a6b8c2)
Location: include/linux/netdevice.h:2972
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae58ae)
Location: include/linux/netdevice.h:2972
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b07ae1)
Location: include/linux/netdevice.h:2972
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b928ba)
Location: include/linux/netdevice.h:2972
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd28)
Location: include/linux/netdevice.h:2972
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
In net/ethernet/eth.c (ffffffff81a54022)
Location: include/linux/netdevice.h:3039
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0b2c)
Location: include/linux/netdevice.h:3039
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af32e1)
Location: include/linux/netdevice.h:3039
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81a0f)
Location: include/linux/netdevice.h:3039
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8be08)
Location: include/linux/netdevice.h:3039
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
In net/ethernet/eth.c (ffffffff81b0cd32)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f54c)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb37f1)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4da53)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c580e8)
Location: include/linux/netdevice.h:3059
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
In net/ethernet/eth.c (ffffffff81c93654)
Location: include/net/gro.h:177
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20855)
Location: include/net/gro.h:177
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d47034)
Location: include/net/gro.h:177
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee12e)
Location: include/net/gro.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df97fb)
Location: include/net/gro.h:177
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
In net/ethernet/eth.c (ffffffff81e4ed4d)
Location: include/net/gro.h:188
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7ab5)
Location: include/net/gro.h:188
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f1014c)
Location: include/net/gro.h:188
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc26f2)
Location: include/net/gro.h:188
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcde23)
Location: include/net/gro.h:188
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
In net/ethernet/eth.c (ffffffff81eaa3ed)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f47335)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe3c)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff82023670)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff82049753)
Location: include/net/gro.h:194
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
In net/ethernet/eth.c (ffffffff81f6ce9d)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d475)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8203656c)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f276b)
Location: include/net/gro.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211bac3)
Location: include/net/gro.h:194
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
In net/ethernet/eth.c (ffff800010c36bb8)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca022c)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f48)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d54940)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fbf8)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (c0d49518)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad178)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce770)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54f90)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f768)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (c000000000d2f128)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3a60)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde5cc)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d48c)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a958)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (ffffffe0007a85a8)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc93a)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818398)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c2d8)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe000895194)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (ffffffff8192b9e2)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198a4bb)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9971)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a273eb)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a31598)
Location: include/linux/netdevice.h:2709
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
In drivers/net/vxlan.c (ffffffff817712c6)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e5792)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81943f7b)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963431)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e41ab)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee788)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (ffffffff8197cb72)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f4c8b)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14211)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92f9b)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d148)
Location: include/linux/netdevice.h:2709
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
In net/ethernet/eth.c (ffffffff8199f0db)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819fee66)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ec0a)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f0ee)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa9341)
Location: include/linux/netdevice.h:2709
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
