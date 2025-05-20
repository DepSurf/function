# Function: <code>p4d_bad</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
```
In mm/mprotect.c (ffffffff811ff678)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:836
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206c3d)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
```
```
In mm/memory.c (ffffffff8120879a)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217c82)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f0a)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121af49)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121fe4e)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
```
```
In mm/swapfile.c (ffffffff81228c57)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8122744d)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
```
```
In mm/memory.c (ffffffff812297da)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239a6e)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a8e8)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123ce16)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
```
```
In mm/vmalloc.c (ffffffff812410b9)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
```
```
In mm/swapfile.c (ffffffff81249f76)
Location: arch/x86/include/asm/pgtable.h:885
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123abf0)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/memory.c (ffffffff8123ccea)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d389)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eaeb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812512c8)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81255799)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/swapfile.c (ffffffff8125e5b6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124c640)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff8124e955)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8125fb8b)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e40)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812635a8)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81267afc)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff8127b819)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125ab70)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff8125cef2)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8126e44b)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f5d9)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81272070)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8127644c)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff8128b2f9)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128918f)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d524)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8129ee6d)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129faf6)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a2c91)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a7e3b)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdcea)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/gup.c (ffffffff81292e6f)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f9d5)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812aa22d)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf86)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812ae5b1)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812b2f0b)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812c980e)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/gup.c (ffffffff8129886f)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a5250)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812af67a)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03bf)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812b3982)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812b8b92)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d047e)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff812d92d0)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e67ad)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812f0eaa)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c01)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812f5502)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812fb144)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813159c9)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff813392a9)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d79b)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff81354a1e)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557c6)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813593a9)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff81362649)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81380f56)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff813b0916)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b67bb)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff813cef7c)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff36)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813d3c79)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff813ddfdf)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff813ff7a1)
Location: arch/x86/include/asm/pgtable.h:907
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff813e4d46)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb1d9)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8140367c)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814049f9)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81408649)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff8141283f)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81432800)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff8140f812)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81415202)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8142fbfc)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430fc9)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81434d69)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff8143f2af)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff8146bc20)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:29
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nopud.h:32
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812531c0)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff81255542)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81266a9b)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c29)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a6c0)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126ea9c)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff812838d9)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245edc)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff81247c96)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81258954)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259f81)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c5b3)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126041c)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff81275792)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81250f60)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff812532e2)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8126483b)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659c9)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81268460)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126c83c)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff812816e9)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812608da)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/memory.c (ffffffff81262cf2)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812741fb)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8127536b)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277de0)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8127c37c)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
```
```
In mm/swapfile.c (ffffffff81291424)
Location: arch/x86/include/asm/pgtable.h:927
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
