# Function: <code>__mem_cgroup_charge</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct page *page, struct mem_cgroup *memcg, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130e630)
Location: mm/memcontrol.c:6525
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_charge
```
**Symbols:**

```
ffffffff8130e630-ffffffff8130e6df: __mem_cgroup_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b530)
Location: mm/memcontrol.c:6745
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
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
ffffffff8135b530-ffffffff8135b5a9: __mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct folio *folio, struct mm_struct *mm, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4ca0)
Location: mm/memcontrol.c:6735
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__filemap_add_folio
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
ffffffff813d4ca0-ffffffff813d4d32: __mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct folio *folio, struct mm_struct *mm, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a720)
Location: mm/memcontrol.c:6925
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8145a720-ffffffff8145a7b2: __mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct folio *folio, struct mm_struct *mm, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490380)
Location: mm/memcontrol.c:6993
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff81490380-ffffffff81490412: __mem_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mem_cgroup_charge(struct folio *folio, struct mm_struct *mm, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bfb90)
Location: mm/memcontrol.c:7285
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff814bfb90-ffffffff814bfc4c: __mem_cgroup_charge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
