# Function: <code>dev_get_cma_area</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-contiguous.h:120
Inline: True
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
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:123
Inline: True
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
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (0)
Location: include/linux/dma-map-ops.h:137
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffff8000101955dc)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
```
In kernel/dma/remap.c (ffff800011447fa8)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - kernel/dma/remap.c:dma_atomic_pool_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c031c510)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:__dma_alloc
  - arch/arm/mm/dma-mapping.c:atomic_pool_init
```
```
In kernel/dma/contiguous.c (c03e2114)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/contiguous.c (ffffffe0001272c8)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
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
In kernel/dma/contiguous.c (ffffffff81127f6d)
Location: include/linux/dma-contiguous.h:62
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
</details>
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
