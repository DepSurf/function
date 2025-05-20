# Function: <code>sk_peek_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bec57)
Location: include/net/sock.h:478
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/ipv4/udp.c (ffffffff817f5c49)
Location: include/net/sock.h:469
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8182c70a)
Location: include/net/sock.h:469
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818511bc)
Location: include/net/sock.h:469
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81826f85)
Location: include/net/sock.h:490
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8185e1c1)
Location: include/net/sock.h:490
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81883008)
Location: include/net/sock.h:490
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81847133)
Location: include/net/sock.h:507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff818833b2)
Location: include/net/sock.h:507
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff818a7eb9)
Location: include/net/sock.h:507
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff818c6b93)
Location: include/net/sock.h:511
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81903ab2)
Location: include/net/sock.h:511
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff8192a969)
Location: include/net/sock.h:511
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff8191d236)
Location: include/net/sock.h:518
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8195bbd7)
Location: include/net/sock.h:518
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81982c97)
Location: include/net/sock.h:518
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff8194b7e6)
Location: include/net/sock.h:538
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819903f7)
Location: include/net/sock.h:538
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819b9333)
Location: include/net/sock.h:538
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819afedb)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fbad3)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a27e43)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819e6b71)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a32763)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a5e8a8)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81ad43bf)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b272fc)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b57e0d)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81ae093b)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b35be7)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b664ce)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81acc9e7)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b237c2)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81b54647)
Location: include/net/sock.h:589
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81b8b357)
Location: include/net/sock.h:601
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81be7c75)
Location: include/net/sock.h:601
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81c1bace)
Location: include/net/sock.h:601
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81d1bcfb)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7f539)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81db8252)
Location: include/net/sock.h:640
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81ee2beb)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81f4d229)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81f88282)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff81f4247e)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81facc13)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe8b9c)
Location: include/net/sock.h:673
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff8200846e)
Location: include/net/sock.h:656
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8207b079)
Location: include/net/sock.h:656
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b66db)
Location: include/net/sock.h:656
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffff800010c9d088)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf1f10)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffff800010d25dc4)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (c0daa5e4)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (c0df9e44)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (c0e2a19c)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (c000000000dac168)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (c000000000e18294)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (c000000000e539a0)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffe0007f9112)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083f078)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffe000865070)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819869e1)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d1df3)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819fdf38)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819404a1)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198ebb3)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff819bacf8)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819f11b1)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3c873)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a689b8)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In net/ipv4/udp.c (ffffffff819fae91)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a47e27)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81a74fa3)
Location: include/net/sock.h:540
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
</details>
</li>
</ul>

## Differences
