# Function: <code>dev_ifsioc_locked</code>

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
In net/core/dev_ioctl.c (ffffffff81733cac)
Location: net/core/dev_ioctl.c:121
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
In net/core/dev_ioctl.c (ffffffff8179f745)
Location: net/core/dev_ioctl.c:121
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
In net/core/dev_ioctl.c (ffffffff817ce115)
Location: net/core/dev_ioctl.c:121
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff817ed758)
Location: net/core/dev_ioctl.c:122
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff81869998)
Location: net/core/dev_ioctl.c:123
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
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
In net/core/dev_ioctl.c (ffffffff818b95cf)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff818e0359)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff8192eaa3)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff81960d23)
Location: net/core/dev_ioctl.c:103
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_ifsioc_locked(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a33ac0)
Location: net/core/dev_ioctl.c:103
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a33ac0-ffffffff81a33cf0: dev_ifsioc_locked (STB_LOCAL)
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
In net/core/dev_ioctl.c (ffffffff81a365d0)
Location: net/core/dev_ioctl.c:104
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
In net/core/dev_ioctl.c (ffffffff81a1d77b)
Location: net/core/dev_ioctl.c:104
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
In net/core/dev_ioctl.c (ffffffff81ad1177)
Location: net/core/dev_ioctl.c:135
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
In net/core/dev_ioctl.c (ffffffff81c4e9ea)
Location: net/core/dev_ioctl.c:137
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
In net/core/dev_ioctl.c (ffffffff81e03a9a)
Location: net/core/dev_ioctl.c:137
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
In net/core/dev_ioctl.c (ffffffff81e760ee)
Location: net/core/dev_ioctl.c:137
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
In net/core/dev_ioctl.c (ffffffff81f3609e)
Location: net/core/dev_ioctl.c:138
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
In net/core/dev_ioctl.c (ffff800010c0459c)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (c0d1d9f8)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (c000000000cee3ac)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffe000783244)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff81900cf3)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff818bab23)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff81951d23)
Location: net/core/dev_ioctl.c:103
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
In net/core/dev_ioctl.c (ffffffff819735d5)
Location: net/core/dev_ioctl.c:103
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
</ul>
