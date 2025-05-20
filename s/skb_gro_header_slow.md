# Function: <code>skb_gro_header_slow</code>

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
In net/core/dev.c (ffffffff8171b6f9)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8174012b)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817838fb)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b768)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81793d42)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e7a)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800e27)
Location: include/linux/netdevice.h:2338
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81801ae9)
Location: include/linux/netdevice.h:2338
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
In net/core/dev.c (ffffffff81783f7e)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817acea6)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0eb2)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8ee6)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8180150e)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812ecb)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866e4f)
Location: include/linux/netdevice.h:2475
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818725f5)
Location: include/linux/netdevice.h:2475
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
In net/core/dev.c (ffffffff817b158e)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817dc4f6)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81821c42)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829db6)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8183231e)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818443db)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8189954f)
Location: include/linux/netdevice.h:2478
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6be5)
Location: include/linux/netdevice.h:2478
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
In net/core/dev.c (ffffffff817d1a3a)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817fbb90)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8184296d)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184b02d)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854bde)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865cf0)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf7ae)
Location: include/linux/netdevice.h:2494
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd71b)
Location: include/linux/netdevice.h:2494
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
In net/core/dev.c (ffffffff8184bc87)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8187954a)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c22c5)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818cac8d)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4a78)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5e1c)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8194287e)
Location: include/linux/netdevice.h:2519
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8195250d)
Location: include/linux/netdevice.h:2519
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
In net/core/dev.c (ffffffff81896011)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818caf44)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81917f12)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920c0e)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b193)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c680)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b676)
Location: include/linux/netdevice.h:2605
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba85)
Location: include/linux/netdevice.h:2605
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
In net/core/dev.c (ffffffff818b7e40)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818f60e1)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8194665b)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194fe7a)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958e15)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c388)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1f40)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e2625)
Location: include/linux/netdevice.h:2699
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec0b6)
Location: include/linux/netdevice.h:2699
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
In net/core/dev.c (ffffffff81903ccd)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81955752)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aacbd)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b4729)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd8e0)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d319e)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40d29)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512e8)
Location: include/linux/netdevice.h:2680
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b255)
Location: include/linux/netdevice.h:2680
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
In net/core/dev.c (ffffffff81936a9f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8198bbf2)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e198d)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb459)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f44f0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d0e)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a779a9)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87f08)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91e85)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffff81a02201)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
```
```
In net/ethernet/eth.c (ffffffff81a637f4)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf031)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad92a4)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ae2db7)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa4d4)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71daa)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833c5)
Location: include/linux/netdevice.h:2807
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d045)
Location: include/linux/netdevice.h:2807
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
In net/core/dev.c (ffffffff81a02a01)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
```
```
In net/ethernet/eth.c (ffffffff81a6b949)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb007)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5cc3)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefc88)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07c78)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b80ae4)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a78)
Location: include/linux/netdevice.h:2956
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cca5)
Location: include/linux/netdevice.h:2956
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
In net/core/dev.c (ffffffff819f25cc)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81a540b3)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6080)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0fb0)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb3d1)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af3486)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f705)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bcd)
Location: include/linux/netdevice.h:3023
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd89)
Location: include/linux/netdevice.h:3023
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
In net/core/dev.c (ffffffff81aa449c)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81b0cdc3)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84890)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f9cd)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a781)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3996)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c377c2)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc1d)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c58069)
Location: include/linux/netdevice.h:3043
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
In net/core/gro.c (ffffffff81c54470)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81c936e2)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d150d4)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c84)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2cb20)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d470b4)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5354)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2db)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df9759)
Location: include/net/gro.h:153
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
In net/core/gro.c (ffffffff81e09bc0)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81e4ede9)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb1fb)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7efe)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef43e9)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f101a2)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a5d)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2860)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcdeb1)
Location: include/net/gro.h:153
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
In net/core/gro.c (ffffffff81e7c386)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81eaa489)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a316)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f4778c)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53ce0)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fe92)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8200726a)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820237de)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff820497e1)
Location: include/net/gro.h:159
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
In net/core/gro.c (ffffffff81f3c6d6)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81f6cf39)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff82000406)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d8cc)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201a0a0)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff820365c2)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d60ca)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2932)
Location: include/net/gro.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211bb51)
Location: include/net/gro.h:159
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
In net/core/dev.c (ffff800010bd51d0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffff800010c36c64)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c95990)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fc0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa494)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2f98)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d41010)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a98)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fb34)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (c0cef5a8)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (c0d495a8)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da4118)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad3fc)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c0db6c4c)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce8bc)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e438f4)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e550a8)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f6ac)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (c000000000cb45d0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (c000000000d2f240)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da6c10)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3ef0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc0560)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde680)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e758a0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d620)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a880)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffe00075ec48)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffe0007a863c)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4be4)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd518)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe0008052d8)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe0008183e6)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c6b0)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c41a)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe0008950ee)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffff818d6a6f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8192ba62)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819817fd)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2c9)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81994290)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9aae)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a17039)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27598)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a31515)
Location: include/linux/netdevice.h:2693
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
In drivers/net/vxlan.c (ffffffff81771284)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/dev.c (ffffffff818908af)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818e5812)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b2bd)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944d89)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194dd50)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196356e)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3df9)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4358)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee705)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffff81927a9f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8197cbf2)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebfcd)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f5a99)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819feb30)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1434e)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a81ab9)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a93148)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0c5)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffff8194916f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8199f160)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5e7d)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffc99)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a6aa)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ed52)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e3b9)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f1c2)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa92b5)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
