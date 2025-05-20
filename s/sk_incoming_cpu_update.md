# Function: <code>sk_incoming_cpu_update</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177eb90)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81786f56)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff817e1928)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f2273)
Location: include/net/sock.h:873
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff817ec00d)
Location: include/net/sock.h:875
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff817f4228)
Location: include/net/sock.h:875
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff8184fc68)
Location: include/net/sock.h:875
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860bb4)
Location: include/net/sock.h:875
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8181c995)
Location: include/net/sock.h:896
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81827d28)
Location: include/net/sock.h:896
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81884148)
Location: include/net/sock.h:896
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892b80)
Location: include/net/sock.h:896
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8183d16f)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818489a8)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff818aa4d9)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b915a)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff818bc958)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff818c83d0)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff8192cfe9)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c09e)
Location: include/net/sock.h:910
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8191249b)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8191e2b8)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81984c79)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81995495)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81940c75)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff8194cf1c)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bb271)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbd7a)
Location: include/net/sock.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819a524f)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819b16d6)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a29e82)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a86a)
Location: include/net/sock.h:948
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819dbf43)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819e843a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a609a2)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7140b)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac9086)
Location: include/net/sock.h:1004
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ad637f)
Location: include/net/sock.h:1004
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b574aa)
Location: include/net/sock.h:1004
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad14)
Location: include/net/sock.h:1004
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad5026)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ae26cd)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b659ca)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b797a7)
Location: include/net/sock.h:1019
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac00ac)
Location: include/net/sock.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81acd887)
Location: include/net/sock.h:1023
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b56167)
Location: include/net/sock.h:1023
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b682c5)
Location: include/net/sock.h:1023
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd1c)
Location: include/net/sock.h:1035
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81b8c264)
Location: include/net/sock.h:1035
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81c1c7e4)
Location: include/net/sock.h:1035
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ffc5)
Location: include/net/sock.h:1035
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0dd27)
Location: include/net/sock.h:1081
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81d1c86d)
Location: include/net/sock.h:1081
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81db907d)
Location: include/net/sock.h:1081
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd370)
Location: include/net/sock.h:1081
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ed36cf)
Location: include/net/sock.h:1119
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81ee3876)
Location: include/net/sock.h:1119
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81f88fee)
Location: include/net/sock.h:1119
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e452)
Location: include/net/sock.h:1119
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81f323db)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81f430e9)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81fe83af)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffeefc)
Location: include/net/sock.h:1121
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff83ab)
Location: include/net/sock.h:1098
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff82009052)
Location: include/net/sock.h:1098
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff820b6f03)
Location: include/net/sock.h:1098
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdc3a)
Location: include/net/sock.h:1098
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffff800010c8f1d4)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffff800010c9d874)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffff800010d2658c)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d397f8)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (c0d9e144)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c0dab2bc)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c0e29b88)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c0e3c338)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (c000000000d9de84)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (c000000000daf14c)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c000000000e561ec)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf04)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffe0007ef392)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fa86a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffe000866c1a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876ab8)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff8197bdb3)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819882aa)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a00032)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10a9b)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff81935873)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff81941d6a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bcdf2)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd85b)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819e6583)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819f2a7a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a6aab2)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b51b)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/ipv4/tcp_ipv4.c (ffffffff819f0243)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/udp.c (ffffffff819fcf7a)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a770c2)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87d5b)
Location: include/net/sock.h:958
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>

## Differences
