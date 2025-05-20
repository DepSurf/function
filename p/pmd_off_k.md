# Function: <code>pmd_off_k</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f2196b)
Location: include/linux/pgtable.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
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
In mm/hugetlb_vmemmap.c (ffffffff8141406d)
Location: include/linux/pgtable.h:156
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
```
```
In mm/sparse-vmemmap.c (ffffffff820cb00e)
Location: include/linux/pgtable.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
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
In mm/hugetlb_vmemmap.c (ffffffff814475cd)
Location: include/linux/pgtable.h:164
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
```
```
In mm/sparse-vmemmap.c (ffffffff8214f29e)
Location: include/linux/pgtable.h:164
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
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
In mm/sparse-vmemmap.c (ffffffff8223216e)
Location: include/linux/pgtable.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/dma-mapping.c (c1507cf4)
Location: arch/arm/mm/mm.h:39
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
```
```
In arch/arm/mm/mmu.c (c1509268)
Location: arch/arm/mm/mm.h:39
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:__set_fixmap
```
```
In arch/arm/mm/highmem.c (c0321d5c)
Location: arch/arm/mm/mm.h:39
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
```
</details>
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
