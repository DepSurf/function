# Function: <code>mem_cgroup_charge</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fe070)
Location: mm/memcontrol.c:6462
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swap_state.c:__read_swap_cache_async
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812fe070-ffffffff812fe252: mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mem_cgroup_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a510)
Location: mm/memcontrol.c:6707
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/swap_state.c:__read_swap_cache_async
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8130a510-ffffffff8130a78c: mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mem_cgroup_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813101e0)
Location: mm/memcontrol.c:6559
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff813101e0-ffffffff81310271: mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290c23)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129c18f)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812ba4e2)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff812e2eb9)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff81331f51)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81340f07)
Location: include/linux/memcontrol.h:690
Inline: True
```
```
In mm/huge_memory.c (ffffffff81344d1e)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e419)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8136704f)
Location: include/linux/memcontrol.h:690
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5eb1)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f24f2)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317b60)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813437e9)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff813a3171)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff813b7deb)
Location: include/linux/memcontrol.h:684
Inline: True
```
```
In mm/huge_memory.c (ffffffff813b9fd2)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c4b38)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff813e45ce)
Location: include/linux/memcontrol.h:684
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In kernel/events/uprobes.c (ffffffff8134fb0e)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135aaf8)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138af0b)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813bb873)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff81422dea)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff81439ac2)
Location: include/linux/memcontrol.h:666
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c122)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81447eef)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/userfaultfd.c (ffffffff8146c2a7)
Location: include/linux/memcontrol.h:666
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In kernel/events/uprobes.c (ffffffff81380ccd)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138c51c)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd539)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813f02ad)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff81457f69)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8146e7f0)
Location: include/linux/memcontrol.h:679
Inline: True
```
```
In mm/huge_memory.c (ffffffff81471512)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147d89f)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/userfaultfd.c (ffffffff814a1131)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aa096)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b5f41)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813ed9ed)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/memory.c (ffffffff8141bb14)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff814928d4)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8149d249)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1ed2)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814abc46)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/userfaultfd.c (ffffffff814d08c0)
Location: include/linux/memcontrol.h:685
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
