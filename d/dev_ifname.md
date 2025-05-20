# Function: <code>dev_ifname</code>

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
In net/core/dev_ioctl.c (ffffffff81733b1e)
Location: net/core/dev_ioctl.c:20
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff8179f5ce)
Location: net/core/dev_ioctl.c:20
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff817cdf9e)
Location: net/core/dev_ioctl.c:20
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_ifname(struct net *net, struct ifreq *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff817ecf40)
Location: net/core/dev_ioctl.c:20
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817ecf40-ffffffff817ecfe2: dev_ifname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_ifname(struct net *net, struct ifreq *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81869130)
Location: net/core/dev_ioctl.c:21
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81869130-ffffffff818691d2: dev_ifname (STB_LOCAL)
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
In net/core/dev_ioctl.c (ffffffff818b972f)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff818e04be)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff8192ea78)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81960cf8)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81a344a3)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81a3671e)
Location: net/core/dev_ioctl.c:22
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81a1d88e)
Location: net/core/dev_ioctl.c:22
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81ad12c5)
Location: net/core/dev_ioctl.c:24
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81c4eb18)
Location: net/core/dev_ioctl.c:26
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81e03bc8)
Location: net/core/dev_ioctl.c:26
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81e7630e)
Location: net/core/dev_ioctl.c:26
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81f362be)
Location: net/core/dev_ioctl.c:27
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffff800010c04684)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (c0d1db7c)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (c000000000cee5d0)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffe000783310)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81900cc8)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff818baaf8)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81951cf8)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff819737f7)
Location: net/core/dev_ioctl.c:21
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
