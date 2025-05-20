# Function: <code>_vm_normal_page</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *_vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, bool with_public_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120a200)
Location: mm/memory.c:822
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8120a200-ffffffff8120a2db: _vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *_vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, bool with_public_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122b020)
Location: mm/memory.c:829
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8122b020-ffffffff8122b128: _vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *_vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte, bool with_public_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123e3e0)
Location: mm/memory.c:572
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8123e3e0-ffffffff8123e4e8: _vm_normal_page (STB_GLOBAL)
```
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
