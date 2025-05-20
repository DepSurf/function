# Function: <code>sock_read_timestamp</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81899770)
Location: include/net/sock.h:2310
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/compat.c (ffffffff818f3e62)
Location: include/net/sock.h:2310
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e3d3d)
Location: include/net/sock.h:2316
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81915f1d)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e946d)
Location: include/net/sock.h:2389
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e931d)
Location: include/net/sock.h:2410
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cf43d)
Location: include/net/sock.h:2446
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7deed)
Location: include/net/sock.h:2505
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bee067)
Location: include/net/sock.h:2628
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9ac2e)
Location: include/net/sock.h:2674
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
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
In net/core/sock.c (ffffffff81e093ae)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/raw.c (ffffffff81f3c0b8)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f42917)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff81fe917e)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81feda36)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff8202be19)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff8208d245)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
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
In net/core/sock.c (ffffffff81ec5d9e)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/ipv4/raw.c (ffffffff820021dc)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8200891b)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv6/udp.c (ffffffff820b6c86)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff820bb647)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
```
```
In net/packet/af_packet.c (ffffffff820fb8ca)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_recvmsg
```
```
In net/mctp/af_mctp.c (ffffffff82163706)
Location: include/net/sock.h:2652
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_recvmsg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baeed4)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccc92c)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c84bc4)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe000740a40)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b5f1d)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186fe6d)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81906f1d)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81927f4d)
Location: include/net/sock.h:2337
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
</details>
</li>
</ul>

## Differences
