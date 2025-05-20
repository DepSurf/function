# Function: <code>call_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817ace52)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8180149a)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812f2e)
Location: include/linux/netdevice.h:2178
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8187259e)
Location: include/linux/netdevice.h:2178
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
In net/ethernet/eth.c (ffffffff817dc4a2)
Location: include/linux/netdevice.h:2160
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818322aa)
Location: include/linux/netdevice.h:2160
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8184443e)
Location: include/linux/netdevice.h:2160
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6b8e)
Location: include/linux/netdevice.h:2160
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
In net/ethernet/eth.c (ffffffff817fbb32)
Location: include/linux/netdevice.h:2175
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854d7c)
Location: include/linux/netdevice.h:2175
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865c91)
Location: include/linux/netdevice.h:2175
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd5d9)
Location: include/linux/netdevice.h:2175
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
In net/ethernet/eth.c (ffffffff818794f2)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4c1c)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5dc1)
Location: include/linux/netdevice.h:2191
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819523c9)
Location: include/linux/netdevice.h:2191
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
In net/ethernet/eth.c (ffffffff818caed4)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b15b)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c645)
Location: include/linux/netdevice.h:2259
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab96d)
Location: include/linux/netdevice.h:2259
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
In net/ethernet/eth.c (ffffffff818f6066)
Location: include/linux/netdevice.h:2324
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194f19a)
Location: include/linux/netdevice.h:2324
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c326)
Location: include/linux/netdevice.h:2324
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec153)
Location: include/linux/netdevice.h:2324
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
In net/ethernet/eth.c (ffffffff819556e0)
Location: include/linux/netdevice.h:2315
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b3993)
Location: include/linux/netdevice.h:2315
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d3073)
Location: include/linux/netdevice.h:2315
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b2e6)
Location: include/linux/netdevice.h:2315
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
In net/ethernet/eth.c (ffffffff8198bb80)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ea6c3)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09be3)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91f16)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (ffffffff81a63780)
Location: include/linux/netdevice.h:2414
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad843b)
Location: include/linux/netdevice.h:2414
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa353)
Location: include/linux/netdevice.h:2414
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d0d6)
Location: include/linux/netdevice.h:2414
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
In net/ethernet/eth.c (ffffffff81a6b8d0)
Location: include/linux/netdevice.h:2515
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5911)
Location: include/linux/netdevice.h:2515
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07af3)
Location: include/linux/netdevice.h:2515
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd36)
Location: include/linux/netdevice.h:2515
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
In net/ipv4/udp_offload.c (ffffffff81ad0c03)
Location: include/linux/netdevice.h:2579
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af32f3)
Location: include/linux/netdevice.h:2579
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff81b8f623)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3803)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff81d20908)
Location: include/net/gro.h:94
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d47046)
Location: include/net/gro.h:94
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff81ee7b68)
Location: include/net/gro.h:94
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f1015e)
Location: include/net/gro.h:94
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff81f473e8)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe4e)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
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
In net/ipv4/udp_offload.c (ffffffff8200d521)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8203657e)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052f08)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_gro_udp_encap_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e16b7)
Location: include/net/gro.h:100
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_gro_udp_encap_rcv
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
In net/ethernet/eth.c (ffff800010c36bc4)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca02a8)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f54)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fc04)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (c0d49524)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad1e0)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce77c)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f774)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (c000000000d2f138)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3b00)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde5dc)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a968)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (ffffffe0007a85b6)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc9ac)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe0008183a8)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe0008951a0)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (ffffffff8192b9f0)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198a533)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9983)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a315a6)
Location: include/linux/netdevice.h:2328
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
In drivers/net/vxlan.c (ffffffff8177131e)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e57a0)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81943ff3)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963443)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee796)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (ffffffff8197cb80)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f4d03)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14223)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d156)
Location: include/linux/netdevice.h:2328
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
In net/ethernet/eth.c (ffffffff8199f0e9)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819feee8)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ec1c)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa934f)
Location: include/linux/netdevice.h:2328
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
