# Function: <code>tcp_rtx_queue_purge</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a6642)
Location: net/ipv4/tcp.c:2335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff818fb6e3)
Location: net/ipv4/tcp.c:2504
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81929633)
Location: net/ipv4/tcp.c:2506
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff8198c568)
Location: net/ipv4/tcp.c:2517
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff819c2ebe)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81aae514)
Location: net/ipv4/tcp.c:2591
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81ab8772)
Location: net/ipv4/tcp.c:2844
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81aa3a72)
Location: net/ipv4/tcp.c:2898
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81b5fc22)
Location: net/ipv4/tcp.c:2923
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81cee708)
Location: net/ipv4/tcp.c:2951
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81eb19cd)
Location: net/ipv4/tcp.c:3048
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81f0fff3)
Location: net/ipv4/tcp.c:2934
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81fd41f3)
Location: net/ipv4/tcp.c:2946
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffff800010c75cb4)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (c0d84360)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (c000000000d7d568)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffe0007d8ed6)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff81962d2e)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff8191c81e)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff819cd4fe)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
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
In net/ipv4/tcp.c (ffffffff819d708e)
Location: net/ipv4/tcp.c:2519
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
</details>
</li>
</ul>

## Differences
