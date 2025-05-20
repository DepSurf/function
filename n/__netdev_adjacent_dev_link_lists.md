# Function: <code>__netdev_adjacent_dev_link_lists</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __netdev_adjacent_dev_link_lists(struct net_device *dev, struct net_device *upper_dev, struct list_head *up_list, struct list_head *down_list, void *private, bool master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717290)
Location: net/core/dev.c:5282
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81717290-ffffffff81717308: __netdev_adjacent_dev_link_lists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __netdev_adjacent_dev_link_lists(struct net_device *dev, struct net_device *upper_dev, struct list_head *up_list, struct list_head *down_list, void *private, bool master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177f240)
Location: net/core/dev.c:5672
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8177f240-ffffffff8177f2bf: __netdev_adjacent_dev_link_lists (STB_LOCAL)
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
In net/core/dev.c (ffffffff817ad184)
Location: net/core/dev.c:5928
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff817cbd34)
Location: net/core/dev.c:6136
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff818455c6)
Location: net/core/dev.c:6277
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff8188eba0)
Location: net/core/dev.c:6407
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff818afc40)
Location: net/core/dev.c:6982
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff818fbaa8)
Location: net/core/dev.c:6992
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff8192dea1)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81a03a64)
Location: net/core/dev.c:7594
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81a04008)
Location: net/core/dev.c:7768
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff819eb466)
Location: net/core/dev.c:8027
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81a9c443)
Location: net/core/dev.c:8017
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81c160dd)
Location: net/core/dev.c:7548
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81dc743d)
Location: net/core/dev.c:7534
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81e391d1)
Location: net/core/dev.c:7539
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffffffff81ef74c1)
Location: net/core/dev.c:7657
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
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
In net/core/dev.c (ffff800010bcf138)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (c0ce7518)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (c000000000caa674)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffe000756a96)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff818cdea1)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81887fc1)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff8191eea1)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81940c01)
Location: net/core/dev.c:7203
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_link
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
