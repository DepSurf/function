# Function: <code>dma_free_from_pool</code>

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
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113fa80)
Location: kernel/dma/pool.c:287
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff8113fa80-ffffffff8113fb13: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113b070)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8113b070-ffffffff8113b103: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113c360)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8113c360-ffffffff8113c3f2: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8115f480)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8115f480-ffffffff8115f512: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff81189710)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff81189710-ffffffff811897ae: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811c5b40)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff811c5b40-ffffffff811c5bde: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811d8710)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff811d8710-ffffffff811d87ae: dma_free_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dma_free_from_pool(struct device *dev, void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811ee220)
Location: kernel/dma/pool.c:283
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_dyn_free
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
```
**Symbols:**

```
ffffffff811ee220-ffffffff811ee2be: dma_free_from_pool (STB_GLOBAL)
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
bool dma_free_from_pool(void *start, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffff800010197530)
Location: kernel/dma/remap.c:206
Inline: False
Direct callers:
  - kernel/dma/remap.c:arch_dma_free
  - drivers/iommu/dma-iommu.c:__iommu_dma_free
```
**Symbols:**

```
ffff800010197530-ffff8000101975b0: dma_free_from_pool (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
