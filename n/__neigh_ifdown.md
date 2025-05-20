# Function: <code>__neigh_ifdown</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c6fa0)
Location: net/core/neighbour.c:351
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff818c6fa0-ffffffff818c7099: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81913120)
Location: net/core/neighbour.c:351
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81913120-ffffffff8191321a: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81945780)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81945780-ffffffff8194587a: __neigh_ifdown (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff81a15700)
Location: net/core/neighbour.c:348
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81a15700-ffffffff81a15819: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81a159f0)
Location: net/core/neighbour.c:350
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81a159f0-ffffffff81a15b09: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff819fc560)
Location: net/core/neighbour.c:354
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff819fc560-ffffffff819fc679: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81aae580)
Location: net/core/neighbour.c:354
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81aae580-ffffffff81aae69e: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81c272a0)
Location: net/core/neighbour.c:397
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81c272a0-ffffffff81c273d3: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd9df0)
Location: net/core/neighbour.c:434
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81dd9df0-ffffffff81dd9f2f: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4ab50)
Location: net/core/neighbour.c:434
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81e4ab50-ffffffff81e4ac8f: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81f09870)
Location: net/core/neighbour.c:442
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81f09870-ffffffff81f099af: __neigh_ifdown.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be4680)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffff800010be4680-ffff800010be47f4: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cff390)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
c0cff390-c0cff4c4: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc8760)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
c000000000cc8760-c000000000cc8904: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076b69e)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffe00076b69e-ffffffe00076b794: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e5750)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff818e5750-ffffffff818e584a: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189f590)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff8189f590-ffffffff8189f68a: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81936780)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81936780-ffffffff8193687a: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __neigh_ifdown(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81957f10)
Location: net/core/neighbour.c:348
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_carrier_down
```
**Symbols:**

```
ffffffff81957f10-ffffffff8195800a: __neigh_ifdown (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
