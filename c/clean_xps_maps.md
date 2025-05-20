# Function: <code>clean_xps_maps</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aff70)
Location: net/core/dev.c:2206
Inline: True
```
**Symbols:**

```
ffffffff818aff70-ffffffff818b0120: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fbef0)
Location: net/core/dev.c:2216
Inline: True
```
**Symbols:**

```
ffffffff818fbef0-ffffffff818fc0d7: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192e4e0)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffffffff8192e4e0-ffffffff8192e6c7: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01460)
Location: net/core/dev.c:2494
Inline: False
```
**Symbols:**

```
ffffffff81a01460-ffffffff81a0166e: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01790)
Location: net/core/dev.c:2519
Inline: False
```
**Symbols:**

```
ffffffff81a01790-ffffffff81a0199e: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8500)
Location: net/core/dev.c:2583
Inline: False
```
**Symbols:**

```
ffffffff819e8500-ffffffff819e86ed: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99500)
Location: net/core/dev.c:2458
Inline: False
```
**Symbols:**

```
ffffffff81a99500-ffffffff81a99731: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c10600)
Location: net/core/dev.c:2435
Inline: False
```
**Symbols:**

```
ffffffff81c10600-ffffffff81c10881: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc01b0)
Location: net/core/dev.c:2420
Inline: False
```
**Symbols:**

```
ffffffff81dc01b0-ffffffff81dc0431: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2fd50)
Location: net/core/dev.c:2446
Inline: False
```
**Symbols:**

```
ffffffff81e2fd50-ffffffff81e2ffb2: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, enum xps_map_type type, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eee930)
Location: net/core/dev.c:2449
Inline: False
```
**Symbols:**

```
ffffffff81eee930-ffffffff81eeeb8f: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9a78)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffff800010bc9a78-ffff800010bc9c64: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9260)
Location: net/core/dev.c:2134
Inline: False
```
**Symbols:**

```
c0ce9260-c0ce949c: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7840)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
c000000000ca7840-c000000000ca7b08: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000758d3a)
Location: net/core/dev.c:2134
Inline: False
```
**Symbols:**

```
ffffffe000758d3a-ffffffe000758ed4: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ce4e0)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffffffff818ce4e0-ffffffff818ce6c7: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888600)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffffffff81888600-ffffffff818887e7: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191f4e0)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffffffff8191f4e0-ffffffff8191f6c7: clean_xps_maps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clean_xps_maps(struct net_device *dev, const long unsigned int *mask, struct xps_dev_maps *dev_maps, unsigned int nr_ids, u16 offset, u16 count, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941240)
Location: net/core/dev.c:2134
Inline: True
```
**Symbols:**

```
ffffffff81941240-ffffffff81941427: clean_xps_maps (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum xps_map_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>const long unsigned int *mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xps_dev_maps *dev_maps</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_ids</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_rxqs_map</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, mask, dev_maps, nr_ids, offset, count, is_rxqs_map</code> ➡️ <code>dev, type, offset, count</code>
</li>
</ul>
</details>
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
