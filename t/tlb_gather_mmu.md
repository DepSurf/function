# Function: <code>tlb_gather_mmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bc9d0)
Location: mm/memory.c:217
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
ffffffff811bc9d0-ffffffff811bca80: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d7780)
Location: mm/memory.c:220
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
ffffffff811d7780-ffffffff811d7839: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7490)
Location: mm/memory.c:220
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
ffffffff811e7490-ffffffff811e7539: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2730)
Location: mm/memory.c:407
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
ffffffff811f2730-ffffffff811f274f: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812097e0)
Location: mm/memory.c:408
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
ffffffff812097e0-ffffffff812097ff: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a650)
Location: mm/memory.c:423
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
ffffffff8122a650-ffffffff8122a66f: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124d010)
Location: mm/mmu_gather.c:240
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
ffffffff8124d010-ffffffff8124d0c9: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125f2e0)
Location: mm/mmu_gather.c:206
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
ffffffff8125f2e0-ffffffff8125f391: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126daf0)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffff8126daf0-ffffffff8126dba1: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8129dd30)
Location: mm/mmu_gather.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
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
ffffffff8129dd30-ffffffff8129de00: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812a90b0)
Location: mm/mmu_gather.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
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
ffffffff812a90b0-ffffffff812a9180: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae500)
Location: mm/mmu_gather.c:284
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812ae500-ffffffff812ae58b: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812efca0)
Location: mm/mmu_gather.c:284
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812efca0-ffffffff812efd2b: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81353190)
Location: mm/mmu_gather.c:297
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81353190-ffffffff81353227: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd440)
Location: mm/mmu_gather.c:335
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/mprotect.c:do_mprotect_pkey
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/mempolicy.c:change_prot_numa
  - mm/userfaultfd.c:uffd_wp_range
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813cd440-ffffffff813cd4d7: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401da0)
Location: mm/mmu_gather.c:335
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
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
ffffffff81401da0-ffffffff81401e37: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e3f0)
Location: mm/mmu_gather.c:336
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
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
ffffffff8142e3f0-ffffffff8142e487: tlb_gather_mmu (STB_GLOBAL)
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
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304cd8)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffff800010304cd8-ffff800010304db8: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0522f54)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - fs/exec.c:setup_arg_pages
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c0522f54-c0522fe8: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0000000003d1b40)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
c0000000003d1b40-c0000000003d1c2c: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210efe)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffe000210efe-ffffffe000210f8c: tlb_gather_mmu (STB_GLOBAL)
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
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81266140)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffff81266140-ffffffff812661f1: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258560)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffff81258560-ffffffff81258611: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263ee0)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffff81263ee0-ffffffff81263f91: tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812738a0)
Location: mm/mmu_gather.c:206
Inline: False
Direct callers:
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
ffffffff812738a0-ffffffff81273951: tlb_gather_mmu (STB_GLOBAL)
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
