# Function: <code>skb_gro_len</code>

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
In net/core/skbuff.c (ffffffff8170c5c0)
Location: include/linux/netdevice.h:2317
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81718205)
Location: include/linux/netdevice.h:2317
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
```
```
In net/ipv4/tcp_offload.c (ffffffff817837d0)
Location: include/linux/netdevice.h:2317
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2317
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81793c3f)
Location: include/linux/netdevice.h:2317
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81800cce)
Location: include/linux/netdevice.h:2317
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: include/linux/netdevice.h:2317
Inline: True
```
```
In net/ipv6/udp_offload.c (0)
Location: include/linux/netdevice.h:2317
Inline: True
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
In net/core/skbuff.c (ffffffff8176f6ff)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81780395)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0d60)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2454
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8180136f)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866d2a)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8187245e)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872b9c)
Location: include/linux/netdevice.h:2454
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff81799513)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff817adce5)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81821af0)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2451
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8183217f)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8189942a)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6a4e)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a71bc)
Location: include/linux/netdevice.h:2451
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff817b88e5)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff817cc845)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818427b8)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2467
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81854c56)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf745)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd4c5)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdc26)
Location: include/linux/netdevice.h:2467
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff818312a5)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81845f15)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff818c2118)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/netdevice.h:2492
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d4af6)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81942815)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819522b5)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81952a26)
Location: include/linux/netdevice.h:2492
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff8187b762)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff8188e455)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8191803a)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920b3c)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8192b01a)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b5ee)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab84e)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abfe1)
Location: include/linux/netdevice.h:2578
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff8189c589)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818af405)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8194678a)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194ff12)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81958c97)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d2006)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e236f)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2bbe)
Location: include/linux/netdevice.h:2672
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff818e6e08)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818fb245)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819aadeb)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b47d0)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819bd761)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40de5)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51024)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5190a)
Location: include/linux/netdevice.h:2653
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff819191e8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff8192d395)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1abb)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb500)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819f4371)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a77a65)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c44)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8850a)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff819f2869)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81a02425)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81acf12b)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad91be)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae2c39)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71cdb)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b830f4)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83aab)
Location: include/linux/netdevice.h:2780
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff819f2859)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81a02c25)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81adb146)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5be8)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aefb06)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b80a10)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b927a2)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b93163)
Location: include/linux/netdevice.h:2929
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff819d8a89)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff819e94a5)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac6195)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0ede)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adb250)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f630)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81b818f3)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b821fc)
Location: include/linux/netdevice.h:2996
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff81a88a19)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff81a97565)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81b849a5)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f8fb)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9a600)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c376ed)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d933)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e2ac)
Location: include/linux/netdevice.h:3016
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/gro.c (ffffffff81c53645)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81d1520b)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20bea)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2c9ab)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd52ef)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee019)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeb5e)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/gro.c (ffffffff81e08ce5)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81edb3eb)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7e64)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef4274)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa69f8)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc25db)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2bae)
Location: include/net/gro.h:126
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/gro.c (ffffffff81e7b405)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff81f3a4ab)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f476ed)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53b6b)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820071d1)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff8202355a)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023b3d)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/gro.c (ffffffff81f3b695)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/core/gro.c:__skb_gro_checksum_complete
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8200059b)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d82d)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
```
```
In net/ipv4/af_inet.c (ffffffff82019f2b)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d6031)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2c9d)
Location: include/net/gro.h:132
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffff800010bc9434)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffff800010c95aec)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca1054)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffff800010caa2f8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d4109c)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffff800010d54804)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d550b4)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (c0ccfa44)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (c0ce66b4)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (c0da4254)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad580)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c0db6ab0)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e43adc)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c0e54dd4)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c0e55664)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (c000000000ca702c)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (c000000000da6e14)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3fe8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc0368)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e75998)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (c000000000e8d318)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dde4)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffe000743b26)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffe0007560d6)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4cc0)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd65c)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffe000805120)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c7f2)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c16e)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c8e8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff818b91e8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818cd395)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8198192b)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b370)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81994111)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a170f5)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a272d4)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27b9a)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff81873138)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff818874b5)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff8193b3eb)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944e30)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff8194dbd1)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3eb5)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff819e4094)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e495a)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff8190a1e8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff8191e395)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819ec0fb)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f5b40)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff819fe9b1)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a81b75)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92e84)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9374a)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
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
In net/core/skbuff.c (ffffffff8192b2e8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (ffffffff8193fa25)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/core/dev.c:__skb_gro_checksum_complete
  - net/core/dev.c:dev_gro_receive
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5fab)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffd40)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/af_inet.c (ffffffff81a0a78d)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e475)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9efc8)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f89a)
Location: include/linux/netdevice.h:2666
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
</details>
</li>
</ul>

## Differences
