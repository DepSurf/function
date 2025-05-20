# Function: <code>skb_gro_flush_final</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817fbb69)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854bc7)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd613)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffff8187952b)
Location: include/linux/netdevice.h:2701
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4a67)
Location: include/linux/netdevice.h:2701
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81952405)
Location: include/linux/netdevice.h:2701
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
In net/ethernet/eth.c (ffffffff818caf03)
Location: include/linux/netdevice.h:2787
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8192045c)
Location: include/linux/netdevice.h:2787
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b15b)
Location: include/linux/netdevice.h:2787
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c672)
Location: include/linux/netdevice.h:2787
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab99c)
Location: include/linux/netdevice.h:2787
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
In net/ethernet/eth.c (ffffffff818f6098)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194f16c)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958dd1)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c356)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e24cd)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec17f)
Location: include/linux/netdevice.h:2881
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
In net/ethernet/eth.c (ffffffff81955710)
Location: include/linux/netdevice.h:2862
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b3969)
Location: include/linux/netdevice.h:2862
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd6f0)
Location: include/linux/netdevice.h:2862
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d30a3)
Location: include/linux/netdevice.h:2862
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a5118c)
Location: include/linux/netdevice.h:2862
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b312)
Location: include/linux/netdevice.h:2862
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
In net/ethernet/eth.c (ffffffff8198bbb0)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ea699)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f4300)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09c13)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87dac)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91f42)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffff81a637b0)
Location: include/linux/netdevice.h:2989
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8423)
Location: include/linux/netdevice.h:2989
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ae2bc4)
Location: include/linux/netdevice.h:2989
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa383)
Location: include/linux/netdevice.h:2989
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83262)
Location: include/linux/netdevice.h:2989
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d102)
Location: include/linux/netdevice.h:2989
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
In net/ethernet/eth.c (ffffffff81a6b905)
Location: include/linux/netdevice.h:3138
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae58f9)
Location: include/linux/netdevice.h:3138
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81aefa8d)
Location: include/linux/netdevice.h:3138
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07b28)
Location: include/linux/netdevice.h:3138
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92913)
Location: include/linux/netdevice.h:3138
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd67)
Location: include/linux/netdevice.h:3138
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
In net/ethernet/eth.c (ffffffff81a54071)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0b73)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81adb1dd)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af3328)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81a6c)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8be57)
Location: include/linux/netdevice.h:3205
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
In net/ethernet/eth.c (ffffffff81b0cd81)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f593)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81b9a58d)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3838)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dab0)
Location: include/linux/netdevice.h:3225
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c58137)
Location: include/linux/netdevice.h:3225
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
In net/ethernet/eth.c (ffffffff81c9369e)
Location: include/net/gro.h:343
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20897)
Location: include/net/gro.h:343
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81d2caeb)
Location: include/net/gro.h:343
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d47073)
Location: include/net/gro.h:343
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee17c)
Location: include/net/gro.h:343
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df9790)
Location: include/net/gro.h:343
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
In net/ethernet/eth.c (ffffffff81e4ed9d)
Location: include/net/gro.h:348
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7af7)
Location: include/net/gro.h:348
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ef43b4)
Location: include/net/gro.h:348
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f0ff6b)
Location: include/net/gro.h:348
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2748)
Location: include/net/gro.h:348
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcde6d)
Location: include/net/gro.h:348
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
In net/ethernet/eth.c (ffffffff81eaa43d)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f47377)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81f53cab)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fc5b)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820236c6)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8204979d)
Location: include/net/gro.h:354
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
In net/ethernet/eth.c (ffffffff81f6ceed)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d4b7)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8201a06b)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8203638b)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f27bc)
Location: include/net/gro.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211bb0d)
Location: include/net/gro.h:354
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
In net/ethernet/eth.c (ffff800010c36bf4)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca026c)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa27c)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f84)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d54978)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fb68)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (c0d49550)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad1b4)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c0db6a18)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce7a8)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54fc4)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f6e8)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (c000000000d2f16c)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3aa8)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc02c4)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde614)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d4cc)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a8c8)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffe0007a85ea)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fc97c)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe0008050b6)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe0008183da)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c30e)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe00089511c)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffff8192ba20)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198a509)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819940a0)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a99b3)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2743c)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a315d2)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffff818e57d0)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81943fc9)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194db60)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963473)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e41fc)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee7c2)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffff8197cbb0)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f4cd9)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819fe940)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14253)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92fec)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d182)
Location: include/linux/netdevice.h:2875
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
In net/ethernet/eth.c (ffffffff8199f11e)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819feeb9)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a713)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ec52)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f147)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa9380)
Location: include/linux/netdevice.h:2875
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
