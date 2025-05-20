# Function: <code>dma_direct_optimal_gfp_mask</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 dma_mask, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113d7a0)
Location: kernel/dma/direct.c:48
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8113d7a0-ffffffff8113d844: dma_direct_optimal_gfp_mask (STB_LOCAL)
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
In kernel/dma/direct.c (ffffffff81138789)
Location: kernel/dma/direct.c:47
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff81139882)
Location: kernel/dma/direct.c:47
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 dma_mask, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8115c560-ffffffff8115c62e: dma_direct_optimal_gfp_mask (STB_LOCAL)
ffffffff81cb0380-ffffffff81cb039e: dma_direct_optimal_gfp_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 dma_mask, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811862b0-ffffffff811863a3: dma_direct_optimal_gfp_mask (STB_LOCAL)
ffffffff81e61022-ffffffff81e61040: dma_direct_optimal_gfp_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 dma_mask, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811c1ca0-ffffffff811c1d93: dma_direct_optimal_gfp_mask (STB_LOCAL)
ffffffff8205a7a7-ffffffff8205a7c5: dma_direct_optimal_gfp_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811d47e0-ffffffff811d48d1: dma_direct_optimal_gfp_mask (STB_LOCAL)
ffffffff820d901b-ffffffff820d9039: dma_direct_optimal_gfp_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
gfp_t dma_direct_optimal_gfp_mask(struct device *dev, u64 *phys_limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:47
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811e96d0-ffffffff811e97c3: dma_direct_optimal_gfp_mask (STB_LOCAL)
ffffffff821b47c8-ffffffff821b47e6: dma_direct_optimal_gfp_mask.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 dma_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, dma_mask, phys_limit</code> ➡️ <code>dev, phys_limit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
