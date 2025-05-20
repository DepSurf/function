# Function: <code>memblock_virt_alloc_try_nid_nopanic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b3af)
Location: mm/memblock.c:1337
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff81f8b3af-ffffffff81f8b419: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4ff3)
Location: mm/memblock.c:1338
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - lib/swiotlb.c:swiotlb_init
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffff81fb4ff3-ffffffff81fb505d: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff19da)
Location: mm/memblock.c:1338
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - lib/swiotlb.c:swiotlb_init
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffff81ff19da-ffffffff81ff1a44: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3e46)
Location: mm/memblock.c:1360
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - lib/swiotlb.c:swiotlb_init
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffff820d3e46-ffffffff820d3eb5: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc8c4)
Location: mm/memblock.c:1370
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - lib/swiotlb.c:swiotlb_init
  - lib/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffff826dc8c4-ffffffff826dc948: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memblock_virt_alloc_try_nid_nopanic(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706e03)
Location: mm/memblock.c:1379
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/sparse.c:sparse_early_usemaps_alloc_node
```
**Symbols:**

```
ffffffff82706e03-ffffffff82706e87: memblock_virt_alloc_try_nid_nopanic (STB_GLOBAL)
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
