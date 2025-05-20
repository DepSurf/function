# Function: <code>__netdev_upper_depth</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192db81)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81a03e06)
Location: net/core/dev.c:7322
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81a0444b)
Location: net/core/dev.c:7484
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff819eb8b3)
Location: net/core/dev.c:7743
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u8 __netdev_upper_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7733
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a98b50-ffffffff81a98be7: __netdev_upper_depth (STB_LOCAL)
ffffffff81d35ec9-ffffffff81d35ef1: __netdev_upper_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 __netdev_upper_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c10180-ffffffff81c10227: __netdev_upper_depth (STB_LOCAL)
ffffffff81f026b3-ffffffff81f026db: __netdev_upper_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 __netdev_upper_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7240
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dbfdd0-ffffffff81dbfe77: __netdev_upper_depth (STB_LOCAL)
ffffffff820ab30d-ffffffff820ab335: __netdev_upper_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 __netdev_upper_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7245
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e2f890-ffffffff81e2f937: __netdev_upper_depth (STB_LOCAL)
ffffffff8212c8d9-ffffffff8212c901: __netdev_upper_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 __netdev_upper_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7363
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81eee470-ffffffff81eee517: __netdev_upper_depth (STB_LOCAL)
ffffffff8220e675-ffffffff8220e69d: __netdev_upper_depth.cold (STB_LOCAL)
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
In net/core/dev.c (ffff800010bcdcf8)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (c0ce71c0)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (c000000000ca9180)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffe000756814)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff818cdb81)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81887ca1)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff8191eb81)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff819408e1)
Location: net/core/dev.c:6931
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
