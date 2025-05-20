# Function: <code>tcp_rmem_pressure</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa963b)
Location: include/net/tcp.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81ab8e09)
Location: include/net/tcp.h:1423
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81ab39bd)
Location: include/net/tcp.h:1432
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81ac418d)
Location: include/net/tcp.h:1432
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81a9ea05)
Location: include/net/tcp.h:1424
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf283)
Location: include/net/tcp.h:1424
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81b5a715)
Location: include/net/tcp.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81b6bf93)
Location: include/net/tcp.h:1417
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81ce8b3e)
Location: include/net/tcp.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81cfb175)
Location: include/net/tcp.h:1460
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81ead1ce)
Location: include/net/tcp.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81ebfca5)
Location: include/net/tcp.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81f0b8ee)
Location: include/net/tcp.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f1e1d5)
Location: include/net/tcp.h:1476
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
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
In net/ipv4/tcp.c (ffffffff81fcf99e)
Location: include/net/tcp.h:1546
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fe28b5)
Location: include/net/tcp.h:1546
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_ready
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
