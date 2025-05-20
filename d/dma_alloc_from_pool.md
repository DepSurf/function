# Function: <code>dma_alloc_from_pool</code>

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
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113f990)
Location: kernel/dma/pool.c:269
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8113f990-ffffffff8113fa7a: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113af80)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff8113af80-ffffffff8113b06a: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113c1c0)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff8113c1c0-ffffffff8113c352: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8115f2e0)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff8115f2e0-ffffffff8115f475: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff81189560)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff81189560-ffffffff81189702: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811c5980)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811c5980-ffffffff811c5b22: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811d8630)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
```
**Symbols:**

```
ffffffff811d8630-ffffffff811d86f9: dma_alloc_from_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *dma_alloc_from_pool(struct device *dev, size_t size, void **cpu_addr, gfp_t gfp, bool (*phys_addr_ok)(struct device *, phys_addr_t, size_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff811ee140)
Location: kernel/dma/pool.c:265
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
```
**Symbols:**

```
ffffffff811ee140-ffffffff811ee209: dma_alloc_from_pool (STB_GLOBAL)
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
void *dma_alloc_from_pool(size_t size, struct page **ret_page, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffff800010197488)
Location: kernel/dma/remap.c:184
Inline: False
Direct callers:
  - kernel/dma/remap.c:arch_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffff800010197488-ffff80001019752c: dma_alloc_from_pool (STB_GLOBAL)
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
