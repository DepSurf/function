# Function: <code>tlb_finish_mmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bcaa0)
Location: mm/memory.c:271
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/mmap.c:exit_mmap
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811bcaa0-ffffffff811bcae6: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d7860)
Location: mm/memory.c:275
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811d7860-ffffffff811d78a6: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7560)
Location: mm/memory.c:275
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811e7560-ffffffff811e75a6: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2750)
Location: mm/memory.c:414
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff811f2750-ffffffff811f2780: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209800)
Location: mm/memory.c:415
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81209800-ffffffff81209830: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a670)
Location: mm/memory.c:430
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8122a670-ffffffff8122a6a0: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124d0d0)
Location: mm/mmu_gather.c:247
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8124d0d0-ffffffff8124d100: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125f3a0)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8125f3a0-ffffffff8125f417: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126dbb0)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8126dbb0-ffffffff8126dc27: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8129de00)
Location: mm/mmu_gather.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8129de00-ffffffff8129dfe1: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812a9180)
Location: mm/mmu_gather.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812a9180-ffffffff812a9361: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae5f0)
Location: mm/mmu_gather.c:312
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812ae5f0-ffffffff812ae7b0: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812efd90)
Location: mm/mmu_gather.c:312
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812efd90-ffffffff812eff50: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813532a0)
Location: mm/mmu_gather.c:325
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813532a0-ffffffff8135343e: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd560)
Location: mm/mmu_gather.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813cd560-ffffffff813cd6fb: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401ec0)
Location: mm/mmu_gather.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81401ec0-ffffffff8140205b: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e510)
Location: mm/mmu_gather.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8142e510-ffffffff8142e689: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304db8)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffff800010304db8-ffff800010304e68: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0522fe8)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - fs/exec.c:setup_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c0522fe8-c0523198: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0000000003d1c30)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c0000000003d1c30-c0000000003d1cf4: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210f8c)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffe000210f8c-ffffffe00021106c: tlb_finish_mmu (STB_GLOBAL)
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
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81266200)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81266200-ffffffff81266277: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258620)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81258620-ffffffff81258697: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263fa0)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81263fa0-ffffffff81264017: tlb_finish_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_finish_mmu(struct mmu_gather *tlb, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81273960)
Location: mm/mmu_gather.c:243
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81273960-ffffffff812739d7: tlb_finish_mmu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
