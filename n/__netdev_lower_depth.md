# Function: <code>__netdev_lower_depth</code>

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
In net/core/dev.c (ffffffff8192dbe5)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffff81a03e63)
Location: net/core/dev.c:7342
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
In net/core/dev.c (ffffffff81a044a8)
Location: net/core/dev.c:7504
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
In net/core/dev.c (ffffffff819eb910)
Location: net/core/dev.c:7763
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
u8 __netdev_lower_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7753
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a98df0-ffffffff81a98e87: __netdev_lower_depth (STB_LOCAL)
ffffffff81d35f06-ffffffff81d35f2e: __netdev_lower_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 __netdev_lower_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7274
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c10460-ffffffff81c10507: __netdev_lower_depth (STB_LOCAL)
ffffffff81f026f0-ffffffff81f02718: __netdev_lower_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 __netdev_lower_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7260
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dbfcd0-ffffffff81dbfd77: __netdev_lower_depth (STB_LOCAL)
ffffffff820ab2e5-ffffffff820ab30d: __netdev_lower_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 __netdev_lower_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7265
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e2fb80-ffffffff81e2fc27: __netdev_lower_depth (STB_LOCAL)
ffffffff8212c924-ffffffff8212c94c: __netdev_lower_depth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 __netdev_lower_depth(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7383
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81eee760-ffffffff81eee807: __netdev_lower_depth (STB_LOCAL)
ffffffff8220e6c0-ffffffff8220e6e8: __netdev_lower_depth.cold (STB_LOCAL)
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
In net/core/dev.c (ffff800010bcdd5c)
Location: net/core/dev.c:6951
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
In net/core/dev.c (c0ce722c)
Location: net/core/dev.c:6951
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
In net/core/dev.c (c000000000ca9200)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffe00075685e)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffff818cdbe5)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffff81887d05)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffff8191ebe5)
Location: net/core/dev.c:6951
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
In net/core/dev.c (ffffffff81940945)
Location: net/core/dev.c:6951
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
