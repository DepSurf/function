# Function: <code>reuseport_has_conns</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/datagram.c (ffffffff819ab0ca)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff819b05be)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a28d73)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81a3da26)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff819e1d9a)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff819e7288)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a5f8ba)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81a74696)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81acf60b)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81ad2b47)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b59602)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6e89e)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81adb60b)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81adf040)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b67c49)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b7d475)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81ac667b)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81aca091)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b55e2a)
Location: include/net/sock_reuseport.h:41
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6c059)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81b84e8b)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81b8890a)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81c1b8e1)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81c33ef2)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81d15728)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81d19dda)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81db8044)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81dd189f)
Location: include/net/sock_reuseport.h:46
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/udp.c (ffffffff81ee09b6)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81f88080)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
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
In net/ipv4/udp.c (ffffffff81f3fc1f)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81feaa97)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
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
In net/ipv4/udp.c (ffffffff820043c4)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff820b58ef)
Location: include/net/sock_reuseport.h:47
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
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
In net/ipv4/datagram.c (ffff800010c95f58)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffff800010c99be4)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffff800010d23d84)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffff800010d3d074)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (c0da4740)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (c0daaf00)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c0e29858)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (c0e402e8)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (c000000000da717c)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (c000000000dae740)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (c000000000e55d34)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (c000000000e711e0)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffe0007f4f40)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffe0007f97b6)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffe0008669fe)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffe0008798cc)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff81981c0a)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff819870f8)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819fef4a)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81a13d26)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff8193b6ca)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff81940bb8)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff819bbd0a)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff819d0ae6)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff819ec3da)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff819f18c8)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a699ca)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81a7e7a6)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
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
In net/ipv4/datagram.c (ffffffff819f628e)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/udp.c (ffffffff819fcbbf)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81a75fae)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/datagram.c (ffffffff81a8b1ca)
Location: include/net/sock_reuseport.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
</details>
</li>
</ul>

## Differences
