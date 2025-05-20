# Function: <code>dma_free_contiguous</code>

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
In kernel/dma/direct.c (ffffffff8112321e)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff8112f65e)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff8113e234)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792030)
Location: include/linux/dma-contiguous.h:166
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
In kernel/dma/direct.c (ffffffff81138fe9)
Location: include/linux/dma-map-ops.h:152
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff81139cc1)
Location: include/linux/dma-map-ops.h:152
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be8c5)
Location: include/linux/dma-map-ops.h:152
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
In kernel/dma/direct.c (ffffffff8113a0c9)
Location: include/linux/dma-map-ops.h:152
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ade1)
Location: include/linux/dma-map-ops.h:152
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1768)
Location: include/linux/dma-map-ops.h:152
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
In kernel/dma/direct.c (ffffffff8115d16d)
Location: include/linux/dma-map-ops.h:153
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dd11)
Location: include/linux/dma-map-ops.h:153
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182a218)
Location: include/linux/dma-map-ops.h:153
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
In kernel/dma/direct.c (ffffffff81186f9a)
Location: include/linux/dma-map-ops.h:153
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff81187ce1)
Location: include/linux/dma-map-ops.h:153
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196bd62)
Location: include/linux/dma-map-ops.h:153
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
In kernel/dma/direct.c (ffffffff811c2a6a)
Location: include/linux/dma-map-ops.h:164
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811c39e1)
Location: include/linux/dma-map-ops.h:164
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6892)
Location: include/linux/dma-map-ops.h:164
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
In kernel/dma/direct.c (ffffffff811d55aa)
Location: include/linux/dma-map-ops.h:165
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811d6531)
Location: include/linux/dma-map-ops.h:165
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b25062)
Location: include/linux/dma-map-ops.h:165
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
In kernel/dma/direct.c (ffffffff811ea49a)
Location: include/linux/dma-map-ops.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb561)
Location: include/linux/dma-map-ops.h:166
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_free_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7bcf2)
Location: include/linux/dma-map-ops.h:166
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
void dma_free_contiguous(struct device *dev, struct page *page, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffff8000101955b8)
Location: kernel/dma/contiguous.c:264
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:__iommu_dma_free
```
**Symbols:**

```
ffff8000101955b8-ffff800010195654: dma_free_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_free_contiguous(struct device *dev, struct page *page, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (c03e2100)
Location: kernel/dma/contiguous.c:264
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
c03e2100-c03e2178: dma_free_contiguous (STB_GLOBAL)
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
In kernel/dma/direct.c (c0000000001f542c)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_free_contiguous(struct device *dev, struct page *page, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffe0001272aa)
Location: kernel/dma/contiguous.c:264
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffe0001272aa-ffffffe000127326: dma_free_contiguous (STB_GLOBAL)
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
void dma_free_contiguous(struct device *dev, struct page *page, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffff81127f50)
Location: kernel/dma/contiguous.c:264
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81127f50-ffffffff81127fc3: dma_free_contiguous (STB_GLOBAL)
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
In kernel/dma/direct.c (ffffffff8111a69e)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff81125b2e)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff8113216e)
Location: include/linux/dma-contiguous.h:166
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
