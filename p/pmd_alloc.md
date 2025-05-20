# Function: <code>pmd_alloc</code>

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
In arch/x86/kernel/tboot.c (ffffffff81f6a346)
Location: include/linux/mm.h:1515
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811becd9)
Location: include/linux/mm.h:1515
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mremap.c (ffffffff811c94a3)
Location: include/linux/mm.h:1515
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811cdf6a)
Location: include/linux/mm.h:1515
Inline: True
```
```
In mm/hugetlb.c (ffffffff811de41f)
Location: include/linux/mm.h:1515
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff81207779)
Location: include/linux/mm.h:1515
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff813eb124)
Location: include/linux/mm.h:1515
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
In arch/x86/kernel/tboot.c (ffffffff81f92623)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811dab90)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811e5893)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eab4c)
Location: include/linux/mm.h:1631
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fcbe4)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffffffff8122d04d)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff814314fe)
Location: include/linux/mm.h:1631
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff81fcd8ef)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811ea752)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811f5ac9)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811fbd87)
Location: include/linux/mm.h:1605
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120d6c4)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffffffff8123f56d)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff8144d76e)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff820adf39)
Location: include/linux/mm.h:1658
Inline: True
```
```
In mm/memory.c (ffffffff811f576a)
Location: include/linux/mm.h:1658
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff812008ac)
Location: include/linux/mm.h:1658
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81206a8b)
Location: include/linux/mm.h:1658
Inline: True
```
```
In mm/hugetlb.c (ffffffff81219514)
Location: include/linux/mm.h:1658
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffffffff8124aec1)
Location: include/linux/mm.h:1658
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff818ed41f)
Location: include/linux/mm.h:1658
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff826b4449)
Location: include/linux/mm.h:1760
Inline: True
```
```
In mm/memory.c (ffffffff8120e6ef)
Location: include/linux/mm.h:1760
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81219084)
Location: include/linux/mm.h:1760
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8121fad8)
Location: include/linux/mm.h:1760
Inline: True
```
```
In mm/hugetlb.c (ffffffff81234513)
Location: include/linux/mm.h:1760
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff81249f8e)
Location: include/linux/mm.h:1760
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8126b140)
Location: include/linux/mm.h:1760
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff8197354d)
Location: include/linux/mm.h:1760
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff826ddbc6)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff8122ff22)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8123aa3b)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81240b89)
Location: include/linux/mm.h:1847
Inline: True
```
```
In mm/hugetlb.c (ffffffff812574b5)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff8126eefc)
Location: include/linux/mm.h:1847
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8128fb2e)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff819cf9eb)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff8289400e)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff81241c18)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8124ec44)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8125546e)
Location: include/linux/mm.h:1925
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126bb35)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812835ac)
Location: include/linux/mm.h:1925
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a4a4e)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a08ec6)
Location: include/linux/mm.h:1925
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff828ab7bc)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff8125457b)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81260f9c)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812677c0)
Location: include/linux/mm.h:1920
Inline: True
```
```
In mm/hugetlb.c (ffffffff81286e34)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffffffff812c000d)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a787d0)
Location: include/linux/mm.h:1920
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff828ae7ca)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff81262adb)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8126f735)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81276120)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffff81296a34)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812af02e)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d1f5d)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81aafb80)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff81047a46)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff8129484d)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8129fcca)
Location: include/linux/mm.h:2145
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c9fed)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812e50c9)
Location: include/linux/mm.h:2145
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81307d4a)
Location: include/linux/mm.h:2145
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81bd4ccc)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff8129f0cd)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812ab7c3)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812d5c2d)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812f048c)
Location: include/linux/mm.h:2163
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313a7a)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81bc7115)
Location: include/linux/mm.h:2171
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff812a418a)
Location: include/linux/mm.h:2171
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
```
```
In mm/mremap.c (ffffffff812b0bbd)
Location: include/linux/mm.h:2171
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff812dc8fe)
Location: include/linux/mm.h:2171
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812f67a3)
Location: include/linux/mm.h:2171
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81319c26)
Location: include/linux/mm.h:2171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81c9a718)
Location: include/linux/mm.h:2200
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff812e54b6)
Location: include/linux/mm.h:2200
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_pmd_range
```
```
In mm/mremap.c (ffffffff812f25f6)
Location: include/linux/mm.h:2200
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81323ac8)
Location: include/linux/mm.h:2200
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff81340ded)
Location: include/linux/mm.h:2200
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813669d3)
Location: include/linux/mm.h:2200
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81e49b82)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff813477f9)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff81354ac6)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81356491)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff813916b4)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate_device.c (ffffffff813b7ccc)
Location: include/linux/mm.h:2278
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e3d62)
Location: include/linux/mm.h:2278
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81067ed0)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff813bfb86)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff813cf025)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d0ab9)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8140e76b)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate_device.c (ffffffff8143998b)
Location: include/linux/mm.h:2442
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b786)
Location: include/linux/mm.h:2442
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81069780)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff813f4850)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff814036f9)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814054d8)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81441b27)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate_device.c (ffffffff8146e733)
Location: include/linux/mm.h:2762
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0589)
Location: include/linux/mm.h:2762
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81070cc0)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In mm/memory.c (ffffffff81420e84)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff8142fc79)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814319f3)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff8147bd97)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate_device.c (ffffffff8149d1a4)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/userfaultfd.c (ffffffff814cfc29)
Location: include/linux/mm.h:2803
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b0ea0)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
```
```
In mm/memory.c (ffff8000102f9bf8)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffff800010305f40)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffff80001030c2d8)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffff8000103335c0)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffff800010377d94)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffff800010d89658)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/arm/mm/pgd.c (0)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1892
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/linux/mm.h:1892
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b75c)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000094820)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a582c)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In mm/memory.c (c0000000003c3bb0)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (c0000000003d3d4c)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (c0000000003dc480)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_page_range_noflush
```
```
In mm/migrate.c (c000000000432750)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (c00000000046a3e4)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (c000000000eca0cc)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In mm/memory.c (ffffffe0002098c2)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffe000211b54)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffe0002157fe)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffe0002311fc)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/userfaultfd.c (ffffffe00024fa4c)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffe0008b30f8)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/tboot.c (ffffffff8289c7e9)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff8125b12b)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81267d85)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126e770)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128f014)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812a760e)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812ca53d)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a4e9d0)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff828949bc)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff8124d348)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8125a094)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81260853)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffff81280d62)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff8129905d)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bb577)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a0bab9)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff828af7ac)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff81258ecb)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81265b25)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126c510)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128ce24)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812a541e)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c834d)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81abadc0)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff828af7da)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff812688cb)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff812754c7)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8127c050)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129cbf4)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/migrate.c (ffffffff812b4b4e)
Location: include/linux/mm.h:1892
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d905d)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81ac7210)
Location: include/linux/mm.h:1892
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
