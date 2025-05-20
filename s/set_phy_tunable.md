# Function: <code>set_phy_tunable</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b79e6)
Location: net/core/ethtool.c:2488
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff817d62af)
Location: net/core/ethtool.c:2494
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff81850940)
Location: net/core/ethtool.c:2497
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8189bd02)
Location: net/core/ethtool.c:2532
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff818bfd19)
Location: net/core/ethtool.c:2478
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8190c4ed)
Location: net/core/ethtool.c:2497
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8193ea39)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81a85209)
Location: net/ethtool/ioctl.c:2492
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8b5c0)
Location: net/ethtool/ioctl.c:2499
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8b5c0-ffffffff81a8b74a: set_phy_tunable (STB_LOCAL)
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
In net/ethtool/ioctl.c (ffffffff81a77d5c)
Location: net/ethtool/ioctl.c:2511
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81b31e83)
Location: net/ethtool/ioctl.c:2625
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81cbcab4)
Location: net/ethtool/ioctl.c:2654
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81e7b0a5)
Location: net/ethtool/ioctl.c:2681
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81ed6dd8)
Location: net/ethtool/ioctl.c:2693
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81f9aa7f)
Location: net/ethtool/ioctl.c:2742
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
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
In net/core/ethtool.c (ffff800010bdcfec)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (c0cf76c8)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (c000000000cbe340)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffe000764448)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff818dea09)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff81898849)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8192fa39)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff81951109)
Location: net/core/ethtool.c:2503
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
