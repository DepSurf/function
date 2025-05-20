# Function: <code>alloc_pages_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e1fe0)
Location: mm/mempolicy.c:1959
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811e1fe0-ffffffff811e2211: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812009d0)
Location: mm/mempolicy.c:1976
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812009d0-ffffffff81200c08: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812123e0)
Location: mm/mempolicy.c:1970
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812123e0-ffffffff8121262d: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121d770)
Location: mm/mempolicy.c:1891
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8121d770-ffffffff8121d952: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238960)
Location: mm/mempolicy.c:1953
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
**Symbols:**

```
ffffffff81238960-ffffffff81238b42: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125be90)
Location: mm/mempolicy.c:2010
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
**Symbols:**

```
ffffffff8125be90-ffffffff8125c04a: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270750)
Location: mm/mempolicy.c:2050
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
**Symbols:**

```
ffffffff81270750-ffffffff8127090a: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128b940)
Location: mm/mempolicy.c:2095
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128b940-ffffffff8128bac4: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129b4b0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8129b4b0-ffffffff8129b6a6: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cefc0)
Location: mm/mempolicy.c:2194
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812cefc0-ffffffff812cf221: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812daa40)
Location: mm/mempolicy.c:2169
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812daa40-ffffffff812daca1: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e22a0)
Location: mm/mempolicy.c:2175
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812e22a0-ffffffff812e2501: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2085
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81cc0519-ffffffff81cc055f: alloc_pages_vma.cold (STB_LOCAL)
ffffffff813293b0-ffffffff81329726: alloc_pages_vma (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033a3b0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffff80001033a3b0-ffff80001033a5c4: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000414ad0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c000000000414ad0-c000000000414da8: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81293a90)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81293a90-ffffffff81293c86: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812856a0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812856a0-ffffffff81285896: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812918a0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812918a0-ffffffff81291a96: alloc_pages_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct *vma, long unsigned int addr, int node, bool hugepage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a16b0)
Location: mm/mempolicy.c:2098
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812a16b0-ffffffff812a18a6: alloc_pages_vma (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool hugepage</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool hugepage</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
