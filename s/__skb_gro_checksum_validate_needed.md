# Function: <code>__skb_gro_checksum_validate_needed</code>

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
In net/ipv4/tcp_offload.c (ffffffff81783a6c)
Location: include/linux/netdevice.h:2375
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8178b5d4)
Location: include/linux/netdevice.h:2375
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4ebf)
Location: include/linux/netdevice.h:2375
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818012fd)
Location: include/linux/netdevice.h:2375
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8180195e)
Location: include/linux/netdevice.h:2375
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
In net/ipv4/tcp_offload.c (ffffffff817f102c)
Location: include/linux/netdevice.h:2512
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff817f8d5d)
Location: include/linux/netdevice.h:2512
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81812f7c)
Location: include/linux/netdevice.h:2512
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81866cbe)
Location: include/linux/netdevice.h:2512
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872b3d)
Location: include/linux/netdevice.h:2512
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
In net/ipv4/tcp_offload.c (ffffffff81821dbc)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81829c2d)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8184448c)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818993be)
Location: include/linux/netdevice.h:2514
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a715d)
Location: include/linux/netdevice.h:2514
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
In net/ipv4/tcp_offload.c (ffffffff81842a3c)
Location: include/linux/netdevice.h:2530
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8184ae7d)
Location: include/linux/netdevice.h:2530
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81865d39)
Location: include/linux/netdevice.h:2530
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff818bf5f2)
Location: include/linux/netdevice.h:2530
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdbd1)
Location: include/linux/netdevice.h:2530
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
In net/ipv4/tcp_offload.c (ffffffff818c239c)
Location: include/linux/netdevice.h:2555
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff818caadd)
Location: include/linux/netdevice.h:2555
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff818e5e6b)
Location: include/linux/netdevice.h:2555
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819426c2)
Location: include/linux/netdevice.h:2555
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819529d1)
Location: include/linux/netdevice.h:2555
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
In net/ipv4/tcp_offload.c (ffffffff81917fec)
Location: include/linux/netdevice.h:2641
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81920a7b)
Location: include/linux/netdevice.h:2641
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8193c6ed)
Location: include/linux/netdevice.h:2641
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff8199b51b)
Location: include/linux/netdevice.h:2641
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf7d)
Location: include/linux/netdevice.h:2641
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
In net/ipv4/tcp_offload.c (ffffffff8194673c)
Location: include/linux/netdevice.h:2735
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8194fdb1)
Location: include/linux/netdevice.h:2735
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff8196c3d4)
Location: include/linux/netdevice.h:2735
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d1e62)
Location: include/linux/netdevice.h:2735
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b5d)
Location: include/linux/netdevice.h:2735
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
In net/ipv4/tcp_offload.c (ffffffff819aad9d)
Location: include/linux/netdevice.h:2716
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819b464e)
Location: include/linux/netdevice.h:2716
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819d3136)
Location: include/linux/netdevice.h:2716
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a40c44)
Location: include/linux/netdevice.h:2716
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a5189e)
Location: include/linux/netdevice.h:2716
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
In net/ipv4/tcp_offload.c (ffffffff819e1a6d)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819eb37e)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a09ca6)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a778c4)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a8849e)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffff81acf0dd)
Location: include/linux/netdevice.h:2843
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad9077)
Location: include/linux/netdevice.h:2843
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81afa41a)
Location: include/linux/netdevice.h:2843
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b71bca)
Location: include/linux/netdevice.h:2843
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83a3e)
Location: include/linux/netdevice.h:2843
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
In net/ipv4/tcp_offload.c (ffffffff81adb0ed)
Location: include/linux/netdevice.h:2992
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5a07)
Location: include/linux/netdevice.h:2992
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81b07bc4)
Location: include/linux/netdevice.h:2992
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b8087d)
Location: include/linux/netdevice.h:2992
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b930fe)
Location: include/linux/netdevice.h:2992
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
In net/ipv4/tcp_offload.c (ffffffff81ac612e)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0cf6)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81af33d0)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f499)
Location: include/linux/netdevice.h:3059
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b8218e)
Location: include/linux/netdevice.h:3059
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
In net/ipv4/tcp_offload.c (ffffffff81b8493e)
Location: include/linux/netdevice.h:3079
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f716)
Location: include/linux/netdevice.h:3079
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81bb38e0)
Location: include/linux/netdevice.h:3079
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81c37559)
Location: include/linux/netdevice.h:3079
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e23e)
Location: include/linux/netdevice.h:3079
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
In net/ipv4/tcp_offload.c (ffffffff81d151ad)
Location: include/net/gro.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81d20a23)
Location: include/net/gro.h:197
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81d47111)
Location: include/net/gro.h:197
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81dd50ef)
Location: include/net/gro.h:197
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deeafd)
Location: include/net/gro.h:197
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
In net/ipv4/tcp_offload.c (ffffffff81edb38d)
Location: include/net/gro.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7c93)
Location: include/net/gro.h:208
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f10036)
Location: include/net/gro.h:208
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81fa67ef)
Location: include/net/gro.h:208
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2b4d)
Location: include/net/gro.h:208
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
In net/ipv4/tcp_offload.c (ffffffff81f3a44d)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81f47509)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81f6fd26)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff82007055)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023add)
Location: include/net/gro.h:214
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
In net/ipv4/tcp_offload.c (ffffffff8200053d)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8200d649)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff82036456)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff820d5eb5)
Location: include/net/gro.h:214
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2c3d)
Location: include/net/gro.h:214
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
In net/ipv4/tcp_offload.c (ffff800010c95a8c)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffff800010ca0edc)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffff800010cc302c)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffff800010d40f24)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d55054)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (c0da41fc)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (c0dad444)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (c0dce854)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c0e4393c)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c0e55600)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (c000000000da6da8)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (c000000000db3db8)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (c000000000dde6e4)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (c000000000e75780)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dd78)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffe0007f4c8e)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd538)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffe000818454)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffe00087c6d0)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c8b6)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffff819818dd)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff8198b1ee)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff819a9a46)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a16f54)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27b2e)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffff8193b39d)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff81944cae)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81963506)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff819d3d14)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e48ee)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffff819ec0ad)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819f59be)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a142e6)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a819d4)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a936de)
Location: include/linux/netdevice.h:2729
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
In net/ipv4/tcp_offload.c (ffffffff819f5f5d)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/udp_offload.c (ffffffff819ffbbe)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff81a1ecea)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/udp_offload.c (ffffffff81a8e2d4)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f82e)
Location: include/linux/netdevice.h:2729
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
</details>
</li>
</ul>

## Differences
