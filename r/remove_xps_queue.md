# Function: <code>remove_xps_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xps_map *remove_xps_queue(struct xps_dev_maps *dev_maps, int cpu, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715730)
Location: net/core/dev.c:1936
Inline: False
Direct callers:
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:netif_set_xps_queue
```
**Symbols:**

```
ffffffff81715730-ffffffff817157b8: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xps_map *remove_xps_queue(struct xps_dev_maps *dev_maps, int cpu, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d760)
Location: net/core/dev.c:1957
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
```
**Symbols:**

```
ffffffff8177d760-ffffffff8177d7e5: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aae60)
Location: net/core/dev.c:1990
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
**Symbols:**

```
ffffffff817aae60-ffffffff817aaede: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c94d0)
Location: net/core/dev.c:2024
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
**Symbols:**

```
ffffffff817c94d0-ffffffff817c954f: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842050)
Location: net/core/dev.c:2044
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
**Symbols:**

```
ffffffff81842050-ffffffff818420cf: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c3f0)
Location: net/core/dev.c:2088
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
```
**Symbols:**

```
ffffffff8188c3f0-ffffffff8188c46e: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad5d0)
Location: net/core/dev.c:2142
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff818ad5d0-ffffffff818ad64e: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8ee0)
Location: net/core/dev.c:2152
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff818f8ee0-ffffffff818f8f5e: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b040)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8192b040-ffffffff8192b0be: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0150c)
Location: net/core/dev.c:2430
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff819fed90-ffffffff819fee14: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0183c)
Location: net/core/dev.c:2455
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff819fea40-ffffffff819feac4: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e85b2)
Location: net/core/dev.c:2518
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff819e52b0-ffffffff819e5367: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a995c7)
Location: net/core/dev.c:2393
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81a95b00-ffffffff81a95bb7: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c106d1)
Location: net/core/dev.c:2370
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81c0c480-ffffffff81c0c596: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc0281)
Location: net/core/dev.c:2355
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81dbc230-ffffffff81dbc346: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2fe1a)
Location: net/core/dev.c:2381
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81e2ca40-ffffffff81e2cb53: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, struct xps_dev_maps *old_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eee9fa)
Location: net/core/dev.c:2385
Inline: True
Inline callers:
  - net/core/dev.c:clean_xps_maps
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81eeacc0-ffffffff81eeadce: remove_xps_queue (STB_LOCAL)
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
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc78d0)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffff800010bc78d0-ffff800010bc79a8: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2f58)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
c0ce2f58-c0ce3004: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca3030)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
c000000000ca3030-c000000000ca3128: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753e9a)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
```
**Symbols:**

```
ffffffe000753e9a-ffffffe000753f5c: remove_xps_queue (STB_LOCAL)
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
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb040)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff818cb040-ffffffff818cb0be: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884f80)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81884f80-ffffffff81884ffe: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c040)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8191c040-ffffffff8191c0be: remove_xps_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool remove_xps_queue(struct xps_dev_maps *dev_maps, int tci, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d520)
Location: net/core/dev.c:2070
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8193d520-ffffffff8193d59e: remove_xps_queue (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int tci</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct xps_map *</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<code>struct xps_dev_maps *old_maps</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev_maps, tci, index</code> ➡️ <code>dev_maps, old_maps, tci, index</code>
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
