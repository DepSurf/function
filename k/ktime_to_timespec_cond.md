# Function: <code>ktime_to_timespec_cond</code>

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
In net/socket.c (ffffffff816fcd29)
Location: include/linux/ktime.h:244
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81802da9)
Location: include/linux/ktime.h:244
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81763a39)
Location: include/linux/ktime.h:244
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81874139)
Location: include/linux/ktime.h:244
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81790a2a)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff818a8729)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff817ae0b4)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff818cef6d)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81826184)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff81953efd)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff8186fa59)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff819ad799)
Location: include/linux/ktime.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/socket.c (ffffffff81890639)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
```
```
In net/packet/af_packet.c (ffffffff819e4109)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff81a52ff9)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff81a89be9)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/packet/af_packet.c (ffff800010d56a20)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (c0e572ec)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (c000000000e8ff4c)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffe00088e40e)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff81a29279)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff819e6469)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff81a94e29)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
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
In net/packet/af_packet.c (ffffffff81aa10f9)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
</details>
</li>
</ul>

## Differences
