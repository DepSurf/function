# Function: <code>flush_tlb_kernel_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072af0)
Location: arch/x86/mm/tlb.c:290
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:unmap_kernel_range
```
**Symbols:**

```
ffffffff81072af0-ffffffff81072b70: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072ab0)
Location: arch/x86/mm/tlb.c:410
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81072ab0-ffffffff81072b30: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076660)
Location: arch/x86/mm/tlb.c:425
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81076660-ffffffff810766e0: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074c90)
Location: arch/x86/mm/tlb.c:304
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81074c90-ffffffff81074d10: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107ae20)
Location: arch/x86/mm/tlb.c:666
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8107ae20-ffffffff8107aea0: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107dbe0)
Location: arch/x86/mm/tlb.c:679
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8107dbe0-ffffffff8107dc60: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084750)
Location: arch/x86/mm/tlb.c:791
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81084750-ffffffff810847d0: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810883e0)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff810883e0-ffffffff81088463: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089090)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81089090-ffffffff81089113: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b7a0)
Location: arch/x86/mm/tlb.c:1009
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_map_pages
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8108b7a0-ffffffff8108b823: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b7f0)
Location: arch/x86/mm/tlb.c:945
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - kernel/power/snapshot.c:safe_copy_page
  - mm/percpu.c:pcpu_map_pages
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8108b7f0-ffffffff8108b873: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c3f0)
Location: arch/x86/mm/tlb.c:989
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_map_pages
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
```
**Symbols:**

```
ffffffff8108c3f0-ffffffff8108c485: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bc30)
Location: arch/x86/mm/tlb.c:1048
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_post_unmap_tlb_flush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff8109bc30-ffffffff8109bcc5: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af0f0)
Location: arch/x86/mm/tlb.c:1022
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_post_unmap_tlb_flush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810af0f0-ffffffff810af1c1: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c94d0)
Location: arch/x86/mm/tlb.c:1045
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_post_unmap_tlb_flush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810c94d0-ffffffff810c95a1: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccb60)
Location: arch/x86/mm/tlb.c:1064
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_post_unmap_tlb_flush
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810ccb60-ffffffff810ccc2c: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d5220)
Location: arch/x86/mm/tlb.c:1066
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_post_unmap_tlb_flush
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vunmap_range
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff810d5220-ffffffff810d52ec: flush_tlb_kernel_range (STB_GLOBAL)
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
In arch/arm64/mm/mmu.c (ffff8000100af234)
Location: arch/arm64/include/asm/tlbflush.h:224
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:update_mapping_prot
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b01d0)
Location: arch/arm64/include/asm/tlbflush.h:224
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:__change_memory_common
```
```
In mm/percpu.c (ffff8000102e1e44)
Location: arch/arm64/include/asm/tlbflush.h:224
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff80001030cac8)
Location: arch/arm64/include/asm/tlbflush.h:224
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c0314394)
Location: arch/arm/kernel/smp_tlb.c:235
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:__dma_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/pageattr.c:change_memory_common
  - mm/percpu.c:pcpu_populate_chunk
  - mm/highmem.c:flush_all_zero_pkmaps
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
c0314394-c031444c: flush_tlb_kernel_range (STB_GLOBAL)
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095b84)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:76
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
```
```
In mm/percpu.c (c0000000003a1dbc)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:76
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (c0000000003dd310)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:76
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
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
In mm/percpu.c (ffffffe0001f8ad2)
Location: arch/riscv/include/asm/tlbflush.h:44
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffe000215784)
Location: arch/riscv/include/asm/tlbflush.h:44
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range
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
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088050)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81088050-ffffffff810880d3: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076cb0)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81076cb0-ffffffff81076d33: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088000)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff81088000-ffffffff81088083: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_tlb_kernel_range(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a270)
Location: arch/x86/mm/tlb.c:827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff8108a270-ffffffff8108a308: flush_tlb_kernel_range (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
