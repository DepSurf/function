# Function: <code>flush_cache_vunmap</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:69
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:69
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:94
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:100
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:100
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:100
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:100
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:100
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:100
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:102
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:102
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:102
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:102
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:101
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:101
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
In mm/percpu.c (0)
Location: arch/arm64/include/asm/cacheflush.h:173
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/arm64/include/asm/cacheflush.h:173
Inline: True
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
In mm/percpu.c (c0506edc)
Location: arch/arm/include/asm/cacheflush.h:349
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/vmalloc.c (c05283b4)
Location: arch/arm/include/asm/cacheflush.h:349
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_unmap_vmap_area
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (0)
Location: arch/riscv/include/asm/cacheflush.h:58
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/riscv/include/asm/cacheflush.h:58
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:94
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:94
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:94
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
In mm/percpu.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/cacheflush.h:94
Inline: True
```
</details>
</li>
</ul>

## Differences
