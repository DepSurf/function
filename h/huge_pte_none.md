# Function: <code>huge_pte_none</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:55
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/hugetlb.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fbeed)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120c996)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
```
```
In mm/hugetlb.c (ffffffff81218303)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:56
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:56
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
In mm/mincore.c (0)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
```
```
In mm/hugetlb.c (ffffffff81233187)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
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
In mm/mincore.c (ffffffff81231cc4)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81256d22)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812905ed)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff812f14dc)
Location: arch/x86/include/asm/hugetlb.h:57
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81245494)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8126b2cb)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812a55c7)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81305e9c)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81257514)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812865a2)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812c0a07)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81327434)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81265a64)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81296187)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812d2b1f)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff8133a214)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81295d97)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812c9704)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff813089a5)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff8137458e)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff812a0c87)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812d5313)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff81314782)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff813824e6)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff812a6567)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812dc0e5)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff8131a92f)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff8138956c)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff812e7a37)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81323251)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff8136782b)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff813d6866)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81348c97)
Location: include/asm-generic/hugetlb.h:95
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81390b8a)
Location: include/asm-generic/hugetlb.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:95
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:95
Inline: True
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
In mm/mincore.c (ffffffff813c1047)
Location: include/asm-generic/hugetlb.h:95
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81412461)
Location: include/asm-generic/hugetlb.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:95
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:95
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6609)
Location: include/asm-generic/hugetlb.h:95
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In mm/hugetlb.c (ffffffff81445a29)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6cf)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147a062)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/hugetlb.h:102
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81667b9f)
Location: include/asm-generic/hugetlb.h:102
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (c0000000003c7b3c)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (c00000000040fcd0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (c00000000046b354)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (c000000000501668)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:77
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:77
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
In mm/mincore.c (ffffffff8125e0b4)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8128e767)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812cb0ff)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff813327f4)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff81250544)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81280526)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812bc05b)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff813233ae)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff8125be54)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8128c577)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812c8f0f)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff813302c4)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/mincore.c (ffffffff8126b844)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8129c362)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/userfaultfd.c (ffffffff812d9c0b)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81342c1b)
Location: include/asm-generic/hugetlb.h:77
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
</ul>

## Differences
