# Function: <code>flush_tlb_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072ad0)
Location: arch/x86/mm/tlb.c:274
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81072ad0-ffffffff81072aee: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072a90)
Location: arch/x86/mm/tlb.c:394
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81072a90-ffffffff81072aae: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076640)
Location: arch/x86/mm/tlb.c:409
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81076640-ffffffff8107665e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074c70)
Location: arch/x86/mm/tlb.c:288
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81074c70-ffffffff81074c8e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107ae00)
Location: arch/x86/mm/tlb.c:650
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8107ae00-ffffffff8107ae1e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107dbc0)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8107dbc0-ffffffff8107dbde: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084730)
Location: arch/x86/mm/tlb.c:775
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81084730-ffffffff8108474e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810883c0)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810883c0-ffffffff810883de: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089070)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81089070-ffffffff8108908e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b780)
Location: arch/x86/mm/tlb.c:993
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8108b780-ffffffff8108b79e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b7d0)
Location: arch/x86/mm/tlb.c:929
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8108b7d0-ffffffff8108b7ee: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c3c0)
Location: arch/x86/mm/tlb.c:973
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8108c3c0-ffffffff8108c3e7: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bc00)
Location: arch/x86/mm/tlb.c:1032
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8109bc00-ffffffff8109bc27: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af0b0)
Location: arch/x86/mm/tlb.c:1006
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810af0b0-ffffffff810af0e6: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c9480)
Location: arch/x86/mm/tlb.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810c9480-ffffffff810c94b6: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccb10)
Location: arch/x86/mm/tlb.c:1048
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810ccb10-ffffffff810ccb46: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d51d0)
Location: arch/x86/mm/tlb.c:1050
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_optimize_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore_folios
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_restore_folios
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810d51d0-ffffffff810d5206: flush_tlb_all (STB_GLOBAL)
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
In arch/arm64/mm/mmu.c (ffff8000100af280)
Location: arch/arm64/include/asm/tlbflush.h:139
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:update_mapping_prot
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0230)
Location: arch/arm64/include/asm/tlbflush.h:139
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:__change_memory_common
```
```
In mm/percpu.c (ffff8000102e1eec)
Location: arch/arm64/include/asm/tlbflush.h:139
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff80001030cb18)
Location: arch/arm64/include/asm/tlbflush.h:139
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In drivers/xen/balloon.c (ffff80001082e85c)
Location: arch/arm64/include/asm/tlbflush.h:139
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c0313fe0)
Location: arch/arm/kernel/smp_tlb.c:178
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:ftrace_arch_code_modify_post_process
```
**Symbols:**

```
c0313fe0-c0314068: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba4e6)
Location: arch/riscv/mm/tlbflush.c:8
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:unmap_kernel_range
```
**Symbols:**

```
ffffffe0000ba4e6-ffffffe0000ba50e: flush_tlb_all (STB_GLOBAL)
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
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088030)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81088030-ffffffff8108804e: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076c90)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81076c90-ffffffff81076cae: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087fe0)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81087fe0-ffffffff81087ffe: flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a250)
Location: arch/x86/mm/tlb.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:cpa_flush
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8108a250-ffffffff8108a26e: flush_tlb_all (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
