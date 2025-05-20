# Function: <code>skb_get_new_timestamp</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da656)
Location: include/linux/skbuff.h:3587
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff8190c7a6)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff819df19f)
Location: include/linux/skbuff.h:3677
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff819deb3f)
Location: include/linux/skbuff.h:3706
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff819c4aff)
Location: include/linux/skbuff.h:3770
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff81a73f88)
Location: include/linux/skbuff.h:3807
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/ipv6/ioam6.c (ffffffff81c38fff)
Location: include/linux/skbuff.h:3807
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/socket.c (ffffffff81be6a6b)
Location: include/linux/skbuff.h:4180
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff81d939db)
Location: include/linux/skbuff.h:4076
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff81e0157b)
Location: include/linux/skbuff.h:4108
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff81ebdf28)
Location: include/linux/skbuff.h:4145
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffff800010ba14dc)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (c0cc46dc)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (c000000000c75c00)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffe0007397cc)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff818ac7a6)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff818666f6)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff818fd7a6)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff8191e816)
Location: include/linux/skbuff.h:3654
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
</details>
</li>
</ul>

## Differences
