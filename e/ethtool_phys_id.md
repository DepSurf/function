# Function: <code>ethtool_phys_id</code>

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
In net/core/ethtool.c (ffffffff8172140e)
Location: net/core/ethtool.c:1362
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8178a7cd)
Location: net/core/ethtool.c:1831
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff817b7eeb)
Location: net/core/ethtool.c:1845
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
In net/core/ethtool.c (ffffffff817d6f6d)
Location: net/core/ethtool.c:1853
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
In net/core/ethtool.c (ffffffff81850dc4)
Location: net/core/ethtool.c:1856
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
In net/core/ethtool.c (ffffffff8189c5fd)
Location: net/core/ethtool.c:1877
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
In net/core/ethtool.c (ffffffff818bfbf1)
Location: net/core/ethtool.c:1819
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
In net/core/ethtool.c (ffffffff8190b673)
Location: net/core/ethtool.c:1827
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
In net/core/ethtool.c (ffffffff8193dca1)
Location: net/core/ethtool.c:1828
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a814e0)
Location: net/ethtool/ioctl.c:1827
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a814e0-ffffffff81a81683: ethtool_phys_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8b0e0)
Location: net/ethtool/ioctl.c:1831
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8b0e0-ffffffff81a8b27b: ethtool_phys_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a74410)
Location: net/ethtool/ioctl.c:1843
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a74410-ffffffff81a745aa: ethtool_phys_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:1957
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b2e640-ffffffff81b2e7f6: ethtool_phys_id (STB_LOCAL)
ffffffff81d39633-ffffffff81d39647: ethtool_phys_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:1988
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cb90d0-ffffffff81cb929b: ethtool_phys_id (STB_LOCAL)
ffffffff81f05d9b-ffffffff81f05db0: ethtool_phys_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:1981
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e77f50-ffffffff81e7811a: ethtool_phys_id (STB_LOCAL)
ffffffff820adacb-ffffffff820adae0: ethtool_phys_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:1993
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed40d0-ffffffff81ed429a: ethtool_phys_id (STB_LOCAL)
ffffffff8212ed11-ffffffff8212ed26: ethtool_phys_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethtool_phys_id(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:2042
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81f97ae0-ffffffff81f97caa: ethtool_phys_id (STB_LOCAL)
ffffffff82210a8a-ffffffff82210a9f: ethtool_phys_id.cold (STB_LOCAL)
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
In net/core/ethtool.c (ffff800010bdcb3c)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (c0cf743c)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (c000000000cbce08)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (ffffffe000763fc0)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (ffffffff818ddc71)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (ffffffff81897ab1)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (ffffffff8192eca1)
Location: net/core/ethtool.c:1828
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
In net/core/ethtool.c (ffffffff81950371)
Location: net/core/ethtool.c:1828
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
