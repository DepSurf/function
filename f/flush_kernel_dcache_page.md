# Function: <code>flush_kernel_dcache_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
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
In fs/exec.c (0)
Location: include/linux/highmem.h:134
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:134
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
In fs/exec.c (0)
Location: include/linux/highmem.h:134
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:134
Inline: True
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_kernel_dcache_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/flush.c (0)
Location: arch/arm/mm/flush.c:357
Inline: False
Direct callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
  - lib/scatterlist.c:sg_miter_stop
```
**Symbols:**

```
c031e864-c031e87c: flush_kernel_dcache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
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
In fs/exec.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/highmem.h:21
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
