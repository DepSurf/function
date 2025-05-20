# Function: <code>__pkru_allows_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b448)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81071aa3)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811d5ec3)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dacf5)
Location: arch/x86/include/asm/mmu_context.h:209
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8106f0f5)
Location: arch/x86/include/asm/mmu_context.h:223
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81075623)
Location: arch/x86/include/asm/mmu_context.h:223
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811e479f)
Location: arch/x86/include/asm/mmu_context.h:223
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea8ba)
Location: arch/x86/include/asm/mmu_context.h:223
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8106e8be)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff811f0b14)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f6797)
Location: arch/x86/include/asm/pgtable.h:1193
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
In arch/x86/mm/fault.c (ffffffff81073965)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81205681)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120ec3c)
Location: arch/x86/include/asm/pgtable.h:1229
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
In arch/x86/mm/fault.c (ffffffff8107629e)
Location: arch/x86/include/asm/pgtable.h:1295
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81226ae5)
Location: arch/x86/include/asm/pgtable.h:1295
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81230384)
Location: arch/x86/include/asm/pgtable.h:1295
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8107c562)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81239be6)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242d34)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8107faf7)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124ae16)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81254bbd)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff81080b87)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81259306)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8126318a)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff81087b5f)
Location: arch/x86/include/asm/pgtable.h:1403
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8128a9b0)
Location: arch/x86/include/asm/pgtable.h:1403
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294ef9)
Location: arch/x86/include/asm/pgtable.h:1403
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8108826d)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81294670)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f7e8)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff81088d98)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8129a0c0)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a47eb)
Location: arch/x86/include/asm/pgtable.h:1399
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8109822a)
Location: arch/x86/include/asm/pgtable.h:1344
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff812daa50)
Location: arch/x86/include/asm/pgtable.h:1344
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e5aa8)
Location: arch/x86/include/asm/pgtable.h:1344
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff810aae7b)
Location: arch/x86/include/asm/pgtable.h:1378
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8133a5c2)
Location: arch/x86/include/asm/pgtable.h:1378
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347d85)
Location: arch/x86/include/asm/pgtable.h:1378
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff810c4b71)
Location: arch/x86/include/asm/pgtable.h:1396
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813b2095)
Location: arch/x86/include/asm/pgtable.h:1396
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c01db)
Location: arch/x86/include/asm/pgtable.h:1396
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff810c6c1e)
Location: arch/x86/include/asm/pgtable.h:1394
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff813e6e35)
Location: arch/x86/include/asm/pgtable.h:1394
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4ece)
Location: arch/x86/include/asm/pgtable.h:1394
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff810cf0b3)
Location: arch/x86/include/asm/pgtable.h:1622
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81411ab5)
Location: arch/x86/include/asm/pgtable.h:1622
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81421564)
Location: arch/x86/include/asm/pgtable.h:1622
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fb87)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff81251956)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b7da)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8106ebea)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124482b)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124dda4)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff8107fb37)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8124f6f6)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125957a)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff81081c2f)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In mm/gup.c (ffffffff8125f066)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268f84)
Location: arch/x86/include/asm/pgtable.h:1410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
