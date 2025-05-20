# Function: <code>sk_can_gso</code>

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
In net/core/sock.c (ffffffff817008e7)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/tcp.c (ffffffff81765e74)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_send_mss
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8176ef21)
Location: include/net/sock.h:1788
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/core/sock.c (ffffffff817672a5)
Location: include/net/sock.h:1749
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/tcp.c (ffffffff817d6688)
Location: include/net/sock.h:1749
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff817d8cb6)
Location: include/net/sock.h:1749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/core/sock.c (ffffffff81794325)
Location: include/net/sock.h:1811
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/tcp.c (ffffffff818065da)
Location: include/net/sock.h:1811
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818094c5)
Location: include/net/sock.h:1811
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/core/sock.c (ffffffff817b26fc)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/tcp.c (ffffffff81826882)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818299ce)
Location: include/net/sock.h:1836
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/core/sock.c (ffffffff8182a8bf)
Location: include/net/sock.h:1850
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/tcp.c (ffffffff818a48f8)
Location: include/net/sock.h:1850
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_send_mss
```
```
In net/ipv4/tcp_input.c (ffffffff818a8c59)
Location: include/net/sock.h:1850
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
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
In net/core/sock.c (ffffffff81874a37)
Location: include/net/sock.h:1861
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895249)
Location: include/net/sock.h:1946
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff818df779)
Location: include/net/sock.h:1958
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81911949)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff819e3789)
Location: include/net/sock.h:2017
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff819e32de)
Location: include/net/sock.h:2036
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff819c932b)
Location: include/net/sock.h:2053
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81a786cb)
Location: include/net/sock.h:2093
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81bebfe4)
Location: include/net/sock.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81d989b4)
Location: include/net/sock.h:2248
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81e0817e)
Location: include/net/sock.h:2236
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81ec4bd4)
Location: include/net/sock.h:2226
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffff800010ba95d4)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (c0cca5f0)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (c000000000c7e5f0)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffe00073c956)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff818b1949)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff8186b899)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff81902949)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
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
In net/core/sock.c (ffffffff819238e9)
Location: include/net/sock.h:1968
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
</details>
</li>
</ul>

## Differences
