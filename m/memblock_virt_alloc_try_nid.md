# Function: <code>memblock_virt_alloc_try_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b419)
Location: mm/memblock.c:1367
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81f8b419-ffffffff81f8b4a9: memblock_virt_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb505d)
Location: mm/memblock.c:1368
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81fb505d-ffffffff81fb50ed: memblock_virt_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1a44)
Location: mm/memblock.c:1368
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
  - lib/cpumask.c:alloc_bootmem_cpumask_var
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - drivers/firmware/memmap.c:firmware_map_add_early
```
**Symbols:**

```
ffffffff81ff1a44-ffffffff81ff1ad4: memblock_virt_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3eb5)
Location: mm/memblock.c:1390
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:__earlyonly_bootmem_alloc
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff820d3eb5-ffffffff820d3f4a: memblock_virt_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc948)
Location: mm/memblock.c:1406
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff826dc948-ffffffff826dc9ed: memblock_virt_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706e87)
Location: mm/memblock.c:1415
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/power/snapshot.c:__register_nosave_region
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_index_alloc
  - drivers/firmware/memmap.c:firmware_map_add_early
  - lib/cpumask.c:alloc_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82706e87-ffffffff82706f2c: memblock_virt_alloc_try_nid (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
