# Function: <code>get_phy_tunable</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (ffffffff817b62a0)
Location: net/core/ethtool.c:2454
Inline: True
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff817b62a0-ffffffff817b63f9: get_phy_tunable.isra.15 (STB_LOCAL)
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
In net/core/ethtool.c (ffffffff817d63f6)
Location: net/core/ethtool.c:2460
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
In net/core/ethtool.c (ffffffff8185120e)
Location: net/core/ethtool.c:2463
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
In net/core/ethtool.c (ffffffff8189d48c)
Location: net/core/ethtool.c:2498
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
In net/core/ethtool.c (ffffffff818bfdff)
Location: net/core/ethtool.c:2444
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
In net/core/ethtool.c (ffffffff8190b825)
Location: net/core/ethtool.c:2463
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
In net/core/ethtool.c (ffffffff8193de53)
Location: net/core/ethtool.c:2469
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/ethtool/ioctl.c (ffffffff81a83890)
Location: net/ethtool/ioctl.c:2458
Inline: True
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a83890-ffffffff81a83a24: get_phy_tunable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8d360)
Location: net/ethtool/ioctl.c:2460
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8d360-ffffffff81a8d556: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a763d0)
Location: net/ethtool/ioctl.c:2472
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a763d0-ffffffff81a765c6: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2d9d0)
Location: net/ethtool/ioctl.c:2586
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b2d9d0-ffffffff81b2dbc6: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cbaff0)
Location: net/ethtool/ioctl.c:2615
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cbaff0-ffffffff81cbb1f0: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e79380)
Location: net/ethtool/ioctl.c:2642
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e79380-ffffffff81e79580: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed2360)
Location: net/ethtool/ioctl.c:2654
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed2360-ffffffff81ed255e: get_phy_tunable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_phy_tunable(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f997a0)
Location: net/ethtool/ioctl.c:2703
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81f997a0-ffffffff81f9999e: get_phy_tunable (STB_LOCAL)
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
In net/core/ethtool.c (ffff800010bdcef8)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (c0cf7ef4)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (c000000000cbe1f8)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (ffffffe000764a9a)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (ffffffff818dde23)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (ffffffff81897c63)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (ffffffff8192ee53)
Location: net/core/ethtool.c:2469
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
In net/core/ethtool.c (ffffffff81950523)
Location: net/core/ethtool.c:2469
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
