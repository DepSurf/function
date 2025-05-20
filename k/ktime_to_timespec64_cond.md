# Function: <code>ktime_to_timespec64_cond</code>

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
In net/socket.c (ffffffff818da4cf)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff8190c61f)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff819df12d)
Location: include/linux/ktime.h:208
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81b869d2)
Location: include/linux/ktime.h:208
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_set_timestamp
  - net/packet/af_packet.c:__packet_set_timestamp
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
In net/socket.c (ffffffff819deacd)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81b96412)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/packet/af_packet.c:__packet_set_timestamp
  - net/packet/af_packet.c:__packet_set_timestamp
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
In net/socket.c (ffffffff819c4a8d)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81b845a9)
Location: include/linux/ktime.h:209
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
In net/socket.c (ffffffff81a73f0d)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81c50a39)
Location: include/linux/ktime.h:209
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
In net/socket.c (ffffffff81be6b3c)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81df1509)
Location: include/linux/ktime.h:209
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
In net/socket.c (ffffffff81d93aa5)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81fc5489)
Location: include/linux/ktime.h:209
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
In net/socket.c (ffffffff81e01645)
Location: include/linux/ktime.h:209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff82026099)
Location: include/linux/ktime.h:209
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
In net/socket.c (ffffffff81ebdff7)
Location: include/linux/ktime.h:207
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff820f5aa9)
Location: include/linux/ktime.h:207
Inline: True
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
In net/socket.c (ffff800010ba1538)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (c0cc455c)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (c000000000c75a78)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffe0007396ae)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff818ac61f)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff8186656f)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff818fd61f)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
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
In net/socket.c (ffffffff8191e68f)
Location: include/linux/ktime.h:245
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
</details>
</li>
</ul>

## Differences
