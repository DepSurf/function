# Function: <code>dma_alloc_contiguous</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:148
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:159
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:159
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:159
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:160
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:160
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:161
Inline: True
```
```
In kernel/dma/ops_helpers.c (0)
Location: include/linux/dma-map-ops.h:161
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:161
Inline: True
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
struct page *dma_alloc_contiguous(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffff8000101954f0)
Location: kernel/dma/contiguous.c:231
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffff8000101954f0-ffff8000101955b4: dma_alloc_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *dma_alloc_contiguous(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (c03e2064)
Location: kernel/dma/contiguous.c:231
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
c03e2064-c03e2100: dma_alloc_contiguous (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *dma_alloc_contiguous(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffe0001271c6)
Location: kernel/dma/contiguous.c:231
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffe0001271c6-ffffffe0001272aa: dma_alloc_contiguous (STB_GLOBAL)
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
struct page *dma_alloc_contiguous(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffff81127ed0)
Location: kernel/dma/contiguous.c:231
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81127ed0-ffffffff81127f47: dma_alloc_contiguous (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-contiguous.h:160
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
