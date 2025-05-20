# Function: <code>memblock_virt_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff81f59c85)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81f7ea17)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff81f7eddb)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (ffffffff81f887b3)
Location: include/linux/bootmem.h:162
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/sparse.c (ffffffff81f8c944)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In lib/swiotlb.c (ffffffff81f9e922)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
```
In drivers/firmware/memmap.c (ffffffff81fb62fb)
Location: include/linux/bootmem.h:162
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81f887b3-ffffffff81f887c8: memblock_virt_alloc.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff81f81c4e)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81fa7914)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff81fa7d70)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (ffffffff81fb2223)
Location: include/linux/bootmem.h:166
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff81fb6671)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In lib/swiotlb.c (ffffffff81fc9dca)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
```
In drivers/firmware/memmap.c (ffffffff81fe3802)
Location: include/linux/bootmem.h:166
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81fb2223-ffffffff81fb2238: memblock_virt_alloc.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff81fbdc8e)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff81fe3635)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff81fe3ad6)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (ffffffff81feebf5)
Location: include/linux/bootmem.h:171
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff81ff303a)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In lib/cpumask.c (ffffffff82003f90)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
```
In lib/swiotlb.c (ffffffff82006dca)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
```
In drivers/firmware/memmap.c (ffffffff820215d1)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81feebf5-ffffffff81feec0a: memblock_virt_alloc.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8209dd6d)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff820c4076)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff820c455b)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (ffffffff820d0fb3)
Location: include/linux/bootmem.h:171
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff820d574c)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In lib/swiotlb.c (ffffffff820e7e02)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
```
In drivers/firmware/memmap.c (ffffffff8210414b)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff8210f133)
Location: include/linux/bootmem.h:171
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff820d0fb3-ffffffff820d0fc8: memblock_virt_alloc.constprop.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff826a3d3e)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff826cc2cc)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff826cc7fc)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/percpu.c (ffffffff826d99b5)
Location: include/linux/bootmem.h:175
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff826de369)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:memory_present
```
```
In lib/swiotlb.c (ffffffff826f0bf4)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
```
In drivers/firmware/memmap.c (ffffffff8270d82c)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff82719524)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff826d99b5-ffffffff826d99ca: memblock_virt_alloc.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff826ccdd9)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In kernel/power/snapshot.c (ffffffff826f6438)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - kernel/power/snapshot.c:__register_nosave_region
```
```
In kernel/printk/printk.c (ffffffff826f69a2)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/swiotlb.c (ffffffff826f818b)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
```
In mm/percpu.c (ffffffff82703ea9)
Location: include/linux/bootmem.h:175
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/sparse.c (ffffffff8270886b)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:memory_present
```
```
In drivers/firmware/memmap.c (ffffffff82737ac6)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
```
In lib/cpumask.c (ffffffff82743ce1)
Location: include/linux/bootmem.h:175
Inline: True
Inline callers:
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82703ea9-ffffffff82703ebe: memblock_virt_alloc.constprop.27 (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
