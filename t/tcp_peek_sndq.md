# Function: <code>tcp_peek_sndq</code>

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
In net/ipv4/tcp.c (ffffffff81767944)
Location: net/ipv4/tcp.c:1361
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d3e14)
Location: net/ipv4/tcp.c:1370
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81803b57)
Location: net/ipv4/tcp.c:1402
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8182466a)
Location: net/ipv4/tcp.c:1446
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a5f33)
Location: net/ipv4/tcp.c:1517
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff818f78dd)
Location: net/ipv4/tcp.c:1503
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff81925f36)
Location: net/ipv4/tcp.c:1499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff81989ae9)
Location: net/ipv4/tcp.c:1489
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff819c0f4d)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8420)
Location: net/ipv4/tcp.c:1497
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81aa8420-ffffffff81aa84da: tcp_peek_sndq.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2990)
Location: net/ipv4/tcp.c:1515
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
**Symbols:**

```
ffffffff81ab2990-ffffffff81ab2a4a: tcp_peek_sndq.constprop.0 (STB_LOCAL)
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
In net/ipv4/tcp.c (ffffffff81aa1a09)
Location: net/ipv4/tcp.c:1517
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffffffff81b5d9aa)
Location: net/ipv4/tcp.c:1514
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffffffff81cec38a)
Location: net/ipv4/tcp.c:1530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffffffff81eb0265)
Location: net/ipv4/tcp.c:1540
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffffffff81f0e6f3)
Location: net/ipv4/tcp.c:1405
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffffffff81fd2845)
Location: net/ipv4/tcp.c:1413
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In net/ipv4/tcp.c (ffff800010c712b0)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (c0d80420)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (c000000000d785cc)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffe0007d6a68)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff81960dbd)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff8191a8ad)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff819cb58d)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/ipv4/tcp.c (ffffffff819d511d)
Location: net/ipv4/tcp.c:1490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
</ul>

## Differences
