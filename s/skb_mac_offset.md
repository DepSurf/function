# Function: <code>skb_mac_offset</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae290)
Location: include/linux/skbuff.h:2220
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826360)
Location: include/linux/skbuff.h:2307
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186fc43)
Location: include/linux/skbuff.h:2318
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff81890820)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff8194d12c)
Location: include/linux/skbuff.h:2396
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bb41c)
Location: include/linux/skbuff.h:2396
Inline: True
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
In net/socket.c (ffffffff818da722)
Location: include/linux/skbuff.h:2484
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff819b18fc)
Location: include/linux/skbuff.h:2484
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2a02c)
Location: include/linux/skbuff.h:2484
Inline: True
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
In net/socket.c (ffffffff8190c872)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff819e865c)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a60b4c)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffff819df379)
Location: include/linux/skbuff.h:2521
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81ad65d5)
Location: include/linux/skbuff.h:2521
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b59a15)
Location: include/linux/skbuff.h:2521
Inline: True
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
In net/socket.c (ffffffff819ded1e)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81ae2bb5)
Location: include/linux/skbuff.h:2542
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06851)
Location: include/linux/skbuff.h:2542
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81b68075)
Location: include/linux/skbuff.h:2542
Inline: True
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
In net/socket.c (ffffffff819c4cde)
Location: include/linux/skbuff.h:2558
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81acdad5)
Location: include/linux/skbuff.h:2558
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1f65)
Location: include/linux/skbuff.h:2558
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81b56385)
Location: include/linux/skbuff.h:2558
Inline: True
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
In net/socket.c (ffffffff81a7416a)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81b8c4a5)
Location: include/linux/skbuff.h:2587
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2475)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81c1c9f5)
Location: include/linux/skbuff.h:2587
Inline: True
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
In net/socket.c (ffffffff81be6d75)
Location: include/linux/skbuff.h:2956
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81d1cb15)
Location: include/linux/skbuff.h:2956
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45c37)
Location: include/linux/skbuff.h:2956
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81db92c5)
Location: include/linux/skbuff.h:2956
Inline: True
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
In net/socket.c (ffffffff81d93ce0)
Location: include/linux/skbuff.h:2854
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81ee3bf5)
Location: include/linux/skbuff.h:2854
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f007)
Location: include/linux/skbuff.h:2854
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81f89315)
Location: include/linux/skbuff.h:2854
Inline: True
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
In net/socket.c (ffffffff81e01880)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81f43465)
Location: include/linux/skbuff.h:2908
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6ed07)
Location: include/linux/skbuff.h:2908
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff81fe8745)
Location: include/linux/skbuff.h:2908
Inline: True
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
In net/socket.c (ffffffff81ebe23c)
Location: include/linux/skbuff.h:2915
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff820093c5)
Location: include/linux/skbuff.h:2915
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035427)
Location: include/linux/skbuff.h:2915
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
```
```
In net/ipv6/udp.c (ffffffff820b7295)
Location: include/linux/skbuff.h:2915
Inline: True
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
In net/socket.c (ffff800010ba170c)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffff800010c9daf8)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d26798)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (c0cc47bc)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (c0dab5a8)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (c0e29de8)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (c000000000c75cf8)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (c000000000daf44c)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (c000000000e5647c)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffe00073985e)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffe0007fac20)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffe000866f7c)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffff818ac872)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff819884cc)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a001dc)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffff818667c2)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff81941f8c)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bcf9c)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffff818fd872)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff819f2c9c)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6ac5c)
Location: include/linux/skbuff.h:2498
Inline: True
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
In net/socket.c (ffffffff8191e8ec)
Location: include/linux/skbuff.h:2498
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv4/udp.c (ffffffff819fd1ac)
Location: include/linux/skbuff.h:2498
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a7726c)
Location: include/linux/skbuff.h:2498
Inline: True
```
</details>
</li>
</ul>

## Differences
