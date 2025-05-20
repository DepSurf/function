# Function: <code>arch_dma_prep_coherent</code>

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
Location: include/linux/dma-noncoherent.h:99
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
Location: include/linux/dma-noncoherent.h:108
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
Location: include/linux/dma-noncoherent.h:106
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-noncoherent.h:106
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
Location: include/linux/dma-map-ops.h:304
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:304
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
Location: include/linux/dma-map-ops.h:317
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:317
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
Location: include/linux/dma-map-ops.h:320
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:320
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
Location: include/linux/dma-map-ops.h:320
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:320
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:320
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
Location: include/linux/dma-map-ops.h:334
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:334
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:334
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
Location: include/linux/dma-map-ops.h:397
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:397
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:397
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
Location: include/linux/dma-map-ops.h:398
Inline: True
```
```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:398
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:398
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
void arch_dma_prep_coherent(struct page *page, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dma-mapping.c (ffff8000100acb28)
Location: arch/arm64/mm/dma-mapping.c:28
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/remap.c:arch_dma_alloc
  - kernel/dma/remap.c:dma_atomic_pool_init
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff8000100acb28-ffff8000100acb70: arch_dma_prep_coherent (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:108
Inline: True
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
Location: include/linux/dma-noncoherent.h:108
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:108
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:108
Inline: True
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
Location: include/linux/dma-noncoherent.h:108
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
Location: include/linux/dma-noncoherent.h:108
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
Location: include/linux/dma-noncoherent.h:108
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
