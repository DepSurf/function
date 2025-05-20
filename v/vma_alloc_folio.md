# Function: <code>vma_alloc_folio</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct folio *vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2153
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81e72922-ffffffff81e7295c: vma_alloc_folio.cold (STB_LOCAL)
ffffffff813986d0-ffffffff81398a6f: vma_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct folio *vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2168
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff820671b7-ffffffff820671f1: vma_alloc_folio.cold (STB_LOCAL)
ffffffff81418500-ffffffff814188ce: vma_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct folio *vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2179
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_folio
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff820e6a79-ffffffff820e6ab3: vma_alloc_folio.cold (STB_LOCAL)
ffffffff8144ba50-ffffffff8144be21: vma_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81485ce0)
Location: mm/mempolicy.c:2164
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff81485ce0-ffffffff81485db8: vma_alloc_folio (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
