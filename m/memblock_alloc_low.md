# Function: <code>memblock_alloc_low</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828a3342)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828bb66b)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828c7c78)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828c1b29)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828d0256)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff82cf1590)
Location: include/linux/memblock.h:396
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
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
In kernel/dma/swiotlb.c (ffffffff82fddfd9)
Location: include/linux/memblock.h:429
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
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
In kernel/dma/swiotlb.c (ffffffff831e8b42)
Location: include/linux/memblock.h:429
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
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
In kernel/dma/swiotlb.c (ffffffff832cd058)
Location: include/linux/memblock.h:430
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
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
In kernel/dma/swiotlb.c (ffffffff83480a8d)
Location: include/linux/memblock.h:446
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
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
In kernel/dma/swiotlb.c (ffffffff83ead232)
Location: include/linux/memblock.h:446
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
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
In kernel/dma/swiotlb.c (ffffffff836d2292)
Location: include/linux/memblock.h:445
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
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
In kernel/dma/swiotlb.c (ffffffff83903fbf)
Location: include/linux/memblock.h:457
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800011447ea8)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c00000000136cfa4)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
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
In kernel/dma/swiotlb.c (ffffffe000009752)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828acaff)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828b9107)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828a4dc6)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828b1658)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828bf9fe)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828cbe8a)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff828c2b4b)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
```
In kernel/dma/swiotlb.c (ffffffff828d1284)
Location: include/linux/memblock.h:390
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
</details>
</li>
</ul>

## Differences
