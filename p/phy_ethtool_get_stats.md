# Function: <code>phy_ethtool_get_stats</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8189dc36)
Location: include/linux/phy.h:1103
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
In net/core/ethtool.c (ffffffff818c04b1)
Location: include/linux/phy.h:1126
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
In net/core/ethtool.c (ffffffff8190ccc9)
Location: include/linux/phy.h:1218
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
In net/core/ethtool.c (ffffffff8193f402)
Location: include/linux/phy.h:1233
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
In net/ethtool/ioctl.c (ffffffff81a81c02)
Location: include/linux/phy.h:1503
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188d680)
Location: drivers/net/phy/phy.c:550
Inline: False
```
**Symbols:**

```
ffffffff8188d680-ffffffff8188d6ea: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8186ffc0)
Location: drivers/net/phy/phy.c:550
Inline: False
```
**Symbols:**

```
ffffffff8186ffc0-ffffffff8187002a: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900540)
Location: drivers/net/phy/phy.c:498
Inline: False
```
**Symbols:**

```
ffffffff81900540-ffffffff819005aa: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a521e0)
Location: drivers/net/phy/phy.c:503
Inline: False
```
**Symbols:**

```
ffffffff81a521e0-ffffffff81a5225b: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdb470)
Location: drivers/net/phy/phy.c:532
Inline: False
```
**Symbols:**

```
ffffffff81bdb470-ffffffff81bdb4eb: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c31e80)
Location: drivers/net/phy/phy.c:545
Inline: False
```
**Symbols:**

```
ffffffff81c31e80-ffffffff81c31efb: phy_ethtool_get_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_ethtool_get_stats(struct phy_device *phydev, struct ethtool_stats *stats, u64 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce6b70)
Location: drivers/net/phy/phy.c:599
Inline: False
```
**Symbols:**

```
ffffffff81ce6b70-ffffffff81ce6beb: phy_ethtool_get_stats (STB_GLOBAL)
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
In net/core/ethtool.c (ffff800010bde484)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (c0cf9004)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (c000000000cbec80)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (ffffffe0007654a2)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (ffffffff818df3d2)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (ffffffff81899212)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (ffffffff81930402)
Location: include/linux/phy.h:1233
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
In net/core/ethtool.c (ffffffff81951ad2)
Location: include/linux/phy.h:1233
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
