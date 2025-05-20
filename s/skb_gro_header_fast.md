# Function: <code>skb_gro_header_fast</code>

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
In net/core/dev.c (ffffffff8171b5ae)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81740088)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8178379e)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b5b9)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81793bcc)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4d60)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cb2)
Location: include/linux/netdevice.h:2327
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81801946)
Location: include/linux/netdevice.h:2327
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
In net/core/dev.c (ffffffff81783e3e)
Location: include/linux/netdevice.h:2464
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/netdevice.h:2464
Inline: True
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/netdevice.h:2464
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
In net/core/dev.c (ffffffff817b144e)
Location: include/linux/netdevice.h:2461
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv4/tcp_offload.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/netdevice.h:2461
Inline: True
```
```
In net/ipv6/ip6_offload.c (0)
Location: include/linux/netdevice.h:2461
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
In net/core/dev.c (ffffffff817d18ee)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817fbab9)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81842772)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184ae65)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854b98)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865ba2)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf5d6)
Location: include/linux/netdevice.h:2477
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4a9)
Location: include/linux/netdevice.h:2477
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
In net/core/dev.c (ffffffff8184bb3e)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81879479)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c20d2)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818caac5)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4a38)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5cd2)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819426a6)
Location: include/linux/netdevice.h:2502
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81952299)
Location: include/linux/netdevice.h:2502
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
In net/core/dev.c (ffffffff81895eba)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818cae4e)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81917d47)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920a4d)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192af73)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c559)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b4ed)
Location: include/linux/netdevice.h:2588
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab7ff)
Location: include/linux/netdevice.h:2588
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
In net/core/dev.c (ffffffff818b7c80)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818f5fe0)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81946477)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194fd6c)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958bf3)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c239)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1e1d)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2319)
Location: include/linux/netdevice.h:2682
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec0b1)
Location: include/linux/netdevice.h:2682
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
In net/ethernet/eth.c (ffffffff8195565e)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aaac7)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b45fd)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd6c3)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d2f89)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40bfd)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50fd8)
Location: include/linux/netdevice.h:2663
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b250)
Location: include/linux/netdevice.h:2663
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
In net/ethernet/eth.c (ffffffff8198bafe)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1797)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb32d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f42d3)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09af9)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a7787d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87bf8)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91e80)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffff81a636fe)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acee07)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad903d)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ae2b93)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa269)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71b9d)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830a8)
Location: include/linux/netdevice.h:2790
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d040)
Location: include/linux/netdevice.h:2790
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
In net/ethernet/eth.c (ffffffff81a6b84e)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adae17)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae59cd)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefa57)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07a09)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b8084d)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92755)
Location: include/linux/netdevice.h:2939
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cca0)
Location: include/linux/netdevice.h:2939
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
In net/ethernet/eth.c (ffffffff81a53fb2)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5e5b)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0cc0)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb1ab)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af320d)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f470)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818ac)
Location: include/linux/netdevice.h:3006
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd84)
Location: include/linux/netdevice.h:3006
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
In net/ethernet/eth.c (ffffffff81b0ccc2)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b8466b)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f6e0)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a55b)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb371d)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c37530)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d8ec)
Location: include/linux/netdevice.h:3026
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c58064)
Location: include/linux/netdevice.h:3026
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
In net/ethernet/eth.c (ffffffff81c935e4)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14e9b)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d209f3)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2c8f7)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d46f5d)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd50c3)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedfcf)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df9754)
Location: include/net/gro.h:136
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
In net/ethernet/eth.c (ffffffff81e4ecd4)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edaffb)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7c63)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef41b7)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f0ffb1)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa67c3)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc257b)
Location: include/net/gro.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcddc4)
Location: include/net/gro.h:136
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
In net/ethernet/eth.c (ffffffff81eaa374)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a0cb)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f474d9)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53aa7)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fca1)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff82007029)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820234fb)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff820496f4)
Location: include/net/gro.h:142
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
In net/ethernet/eth.c (ffffffff81f6ce24)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff820001bb)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d619)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff82019e67)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff820363d1)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d5e89)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f25eb)
Location: include/net/gro.h:142
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211ba64)
Location: include/net/gro.h:142
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
In net/ethernet/eth.c (ffff800010c36b20)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c95750)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0e8c)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa240)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2e4c)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d40ed4)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d547c0)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fb28)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (c0d49470)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da3f04)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad3bc)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c0db69d4)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce66c)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e438b4)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54d90)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f6a0)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (c000000000d2f078)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da6914)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3d64)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc0280)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde4b0)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e75724)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d2bc)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a878)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffe0007a850c)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f49bc)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd4de)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe000805076)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818292)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c676)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c12e)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe0008950e4)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffff8192b96e)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81981607)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b19d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81994073)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9899)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a16f0d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27288)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a31510)
Location: include/linux/netdevice.h:2676
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
In drivers/net/vxlan.c (ffffffff8177127e)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e571e)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b0c7)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944c5d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194db33)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963359)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3ccd)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4048)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee700)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffff8197cafe)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebdd7)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f596d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819fe913)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14139)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8198d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e38)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0c0)
Location: include/linux/netdevice.h:2676
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
In net/ethernet/eth.c (ffffffff8199f05e)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5c87)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffb6d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a6a5)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1eb29)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e28d)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9ef78)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa92b0)
Location: include/linux/netdevice.h:2676
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
