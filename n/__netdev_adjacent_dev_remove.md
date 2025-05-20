# Function: <code>__netdev_adjacent_dev_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715fd0)
Location: net/core/dev.c:5248
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_adjacent_dev_unlink
  - net/core/dev.c:__netdev_adjacent_dev_unlink
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff81715fd0-ffffffff81716149: __netdev_adjacent_dev_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177dee0)
Location: net/core/dev.c:5638
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink
  - net/core/dev.c:__netdev_adjacent_dev_unlink
```
**Symbols:**

```
ffffffff8177dee0-ffffffff8177e054: __netdev_adjacent_dev_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817acdf0)
Location: net/core/dev.c:5888
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff817acdf0-ffffffff817acfa3: __netdev_adjacent_dev_remove.constprop.109 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817cb9c0)
Location: net/core/dev.c:6096
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff817cb9c0-ffffffff817cbb5e: __netdev_adjacent_dev_remove.constprop.115 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81845210)
Location: net/core/dev.c:6237
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff81845210-ffffffff818453ae: __netdev_adjacent_dev_remove.constprop.118 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188e7d0)
Location: net/core/dev.c:6367
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff8188e7d0-ffffffff8188e986: __netdev_adjacent_dev_remove.constprop.134 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818af870)
Location: net/core/dev.c:6942
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff818af870-ffffffff818afa26: __netdev_adjacent_dev_remove.constprop.143 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818fb6c0)
Location: net/core/dev.c:6952
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff818fb6c0-ffffffff818fb881: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8192d810)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff8192d810-ffffffff8192d9c5: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03700)
Location: net/core/dev.c:7554
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a03700-ffffffff81a03911: __netdev_adjacent_dev_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03ca0)
Location: net/core/dev.c:7728
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a03ca0-ffffffff81a03eb1: __netdev_adjacent_dev_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb0f0)
Location: net/core/dev.c:7987
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819eb0f0-ffffffff819eb301: __netdev_adjacent_dev_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7977
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a9c0b0-ffffffff81a9c2d5: __netdev_adjacent_dev_remove (STB_LOCAL)
ffffffff81d360bc-ffffffff81d360d1: __netdev_adjacent_dev_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7508
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c15cc0-ffffffff81c15f35: __netdev_adjacent_dev_remove (STB_LOCAL)
ffffffff81f0293f-ffffffff81f02954: __netdev_adjacent_dev_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7494
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dc7010-ffffffff81dc7288: __netdev_adjacent_dev_remove (STB_LOCAL)
ffffffff820ab4ff-ffffffff820ab514: __netdev_adjacent_dev_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7499
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e36340-ffffffff81e365b6: __netdev_adjacent_dev_remove (STB_LOCAL)
ffffffff8212cb6b-ffffffff8212cb80: __netdev_adjacent_dev_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __netdev_adjacent_dev_remove(struct net_device *dev, struct net_device *adj_dev, u16 ref_nr, struct list_head *dev_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7617
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81ef4600-ffffffff81ef48a6: __netdev_adjacent_dev_remove (STB_LOCAL)
ffffffff8220e8a9-ffffffff8220e8be: __netdev_adjacent_dev_remove.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bcda50)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffff800010bcda50-ffff800010bcdc2c: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0ce6df4)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
c0ce6df4-c0ce6ff4: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000ca8e10)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
c000000000ca8e10-c000000000ca9074: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000756504)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffe000756504-ffffffe0007566ac: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818cd810)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff818cd810-ffffffff818cd9c5: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81887930)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff81887930-ffffffff81887ae5: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8191e810)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff8191e810-ffffffff8191e9c5: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81940570)
Location: net/core/dev.c:7163
Inline: True
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
  - net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour
```
**Symbols:**

```
ffffffff81940570-ffffffff81940725: __netdev_adjacent_dev_remove.constprop.0 (STB_LOCAL)
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
