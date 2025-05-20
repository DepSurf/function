# Function: <code>skb_gro_frag0_invalidate</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b15a2)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817dc50f)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81821c5f)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829dc6)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81832334)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818443f5)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8189955f)
Location: include/linux/netdevice.h:2472
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6bfd)
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d1a4e)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff817fbba9)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81842986)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184b09f)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81854bf8)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865d0a)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf7e5)
Location: include/linux/netdevice.h:2488
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd680)
Location: include/linux/netdevice.h:2488
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
In net/core/dev.c (ffffffff8184bca1)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8187956b)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c22e6)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818cacff)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff818d4a98)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5e3c)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819428b5)
Location: include/linux/netdevice.h:2513
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81952472)
Location: include/linux/netdevice.h:2513
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
In net/core/dev.c (ffffffff81896026)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818caf58)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81917f26)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920c22)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b1a7)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c698)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b68a)
Location: include/linux/netdevice.h:2599
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab9e6)
Location: include/linux/netdevice.h:2599
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
In net/core/dev.c (ffffffff818b7e4f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818f60ef)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8194666a)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194fe88)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958e23)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c39a)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1f4e)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e258f)
Location: include/linux/netdevice.h:2693
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec0c8)
Location: include/linux/netdevice.h:2693
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
In net/core/dev.c (ffffffff81903ce0)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81955760)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aaccb)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b473b)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd8ee)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d31b0)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40d3b)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51251)
Location: include/linux/netdevice.h:2674
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b267)
Location: include/linux/netdevice.h:2674
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
In net/core/dev.c (ffffffff81936ab2)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8198bc00)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e199b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb46b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f44fe)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d20)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a779bb)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87e71)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91e97)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (ffffffff81a02214)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
```
```
In net/ethernet/eth.c (ffffffff81a63802)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf03e)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad92b6)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81ae2dc5)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa4e6)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71dbc)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b833d6)
Location: include/linux/netdevice.h:2801
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d057)
Location: include/linux/netdevice.h:2801
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
In net/core/dev.c (ffffffff81a02a14)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/core/dev.c:napi_frags_skb
```
```
In net/ethernet/eth.c (ffffffff81a6b957)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb015)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5cd5)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefc96)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07c8a)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b80af6)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b929de)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9ccb7)
Location: include/linux/netdevice.h:2950
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
In net/core/dev.c (ffffffff819f25d9)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81a540c1)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac608d)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0fbe)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb3df)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af3498)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f713)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81bde)
Location: include/linux/netdevice.h:3017
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8bd9b)
Location: include/linux/netdevice.h:3017
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
In net/core/dev.c (ffffffff81aa44a9)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81b0cdd1)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b8489d)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f9db)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a78f)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb39a8)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c377d0)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc2e)
Location: include/linux/netdevice.h:3037
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c5807b)
Location: include/linux/netdevice.h:3037
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
In net/core/gro.c (ffffffff81c5447d)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81c936f0)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d150e2)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20c92)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2cb2e)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d470c6)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd5362)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2eb)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81df976b)
Location: include/net/gro.h:147
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
In net/core/gro.c (ffffffff81e09bcd)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81e4edf7)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb211)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7f0c)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef43f7)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f101b4)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa6a6b)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2872)
Location: include/net/gro.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81fcdebf)
Location: include/net/gro.h:147
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
In net/core/gro.c (ffffffff81e7c393)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81eaa497)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a328)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f4779a)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53cee)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fea4)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff82007278)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820237f0)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff820497ef)
Location: include/net/gro.h:153
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
In net/core/gro.c (ffffffff81f3c6e3)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff81f6cf47)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff82000418)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d8da)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201a0ae)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff820365d4)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d60d8)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2944)
Location: include/net/gro.h:153
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff8211bb5f)
Location: include/net/gro.h:153
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
In net/core/dev.c (ffff800010bd51e0)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffff800010c36c74)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c959a0)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0fd0)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa4a4)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc2ff8)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d41020)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a1c)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fb44)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (c0cef5bc)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (c0d495bc)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da412c)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad410)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c0db6c60)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce8d0)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e43908)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e5502c)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f6c0)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (c000000000cb45e4)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (c000000000d2f254)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da6c24)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3f04)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc0574)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde694)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e758b4)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d58c)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9a894)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (ffffffe00075ec54)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffe0007a864c)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4bf4)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd524)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe0008052e4)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe0008184bc)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c6bc)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c3a8)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe0008950fa)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (ffffffff818d6a82)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8192ba70)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8198180b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b2db)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8199429e)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9ac0)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a1704b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27501)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a31527)
Location: include/linux/netdevice.h:2687
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
In drivers/net/vxlan.c (ffffffff81771297)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/dev.c (ffffffff818908c2)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff818e5820)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b2cb)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944d9b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194dd5e)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963580)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3e0b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e42c1)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee717)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (ffffffff81927ab2)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8197cc00)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebfdb)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f5aab)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819feb3e)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a14360)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a81acb)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a930b1)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d0d7)
Location: include/linux/netdevice.h:2687
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
In net/core/dev.c (ffffffff81949182)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
```
In net/ethernet/eth.c (ffffffff8199f16e)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5e8b)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffcab)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a6bc)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ed64)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e3cb)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f1d3)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa92c7)
Location: include/linux/netdevice.h:2687
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
