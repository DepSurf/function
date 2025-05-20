# Function: <code>dst_negative_advice</code>

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
In net/ipv4/tcp_timer.c (ffffffff8177a08f)
Location: include/net/sock.h:1729
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
In net/core/sock.c (ffffffff8176b3da)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff817e72a6)
Location: include/net/sock.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff817984ad)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81817c97)
Location: include/net/sock.h:1752
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff817b6049)
Location: include/net/sock.h:1757
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff818381fb)
Location: include/net/sock.h:1757
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8182e0a6)
Location: include/net/sock.h:1771
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff818b790c)
Location: include/net/sock.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8187896d)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d3c6)
Location: include/net/sock.h:1782
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8189940c)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b79b)
Location: include/net/sock.h:1867
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff818e370c)
Location: include/net/sock.h:1879
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fb54)
Location: include/net/sock.h:1879
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819158ec)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff819d672b)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819e8a7c)
Location: include/net/sock.h:1938
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac26ce)
Location: include/net/sock.h:1938
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff819e8bca)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff819ced00)
Location: include/net/sock.h:1985
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff81a7e41c)
Location: include/net/sock.h:2025
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff81bf1f27)
Location: include/net/sock.h:2146
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff81d9f6cf)
Location: include/net/sock.h:2183
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0d647)
Location: include/net/sock.h:2171
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81eca7d8)
Location: include/net/sock.h:2161
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
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
In net/core/sock.c (ffff800010bae9bc)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffff800010c8965c)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (c0ccc1d8)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (c0d9869c)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (c000000000c84798)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (c000000000d96994)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffe000740800)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea4d8)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff818b58ec)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8197659b)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8186f83c)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff8193005b)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff819068ec)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0d6b)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/core/sock.c (ffffffff8192791e)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff819eaa2b)
Location: include/net/sock.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
</ul>

## Differences
