# Function: <code>hpage_pincount_available</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff812870c2)
Location: include/linux/mm.h:893
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81287da8)
Location: include/linux/mm.h:893
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/rmap.c (ffffffff812a6b0a)
Location: include/linux/mm.h:893
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812af6f4)
Location: include/linux/mm.h:893
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c3c89)
Location: include/linux/mm.h:893
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81270ef8)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81be74a5)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812919a5)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff81299d44)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b1faa)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812bb33c)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812cf8d0)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812f7e90)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813c7fb9)
Location: include/linux/mm.h:926
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81275a2d)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81bd9328)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81296cc5)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129ec06)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b767a)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812c048b)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812dcce5)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812fe42d)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813cefe9)
Location: include/linux/mm.h:949
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/vmscan.c (ffffffff812b373f)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81cbbd6a)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d7672)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812dfe51)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f9d8a)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81303220)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff81323eed)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81347fd5)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff814204d0)
Location: include/linux/mm.h:953
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
