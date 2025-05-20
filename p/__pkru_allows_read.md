# Function: <code>__pkru_allows_read</code>

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
In arch/x86/mm/fault.c (ffffffff8106b534)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81071ab7)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (0)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
```
```
In mm/gup.c (ffffffff811d5ee0)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dad17)
Location: arch/x86/include/asm/pgtable.h:957
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
In arch/x86/mm/fault.c (ffffffff8106f116)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81075637)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b64a)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811e47b4)
Location: arch/x86/include/asm/pgtable.h:957
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea8dc)
Location: arch/x86/include/asm/pgtable.h:957
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
In arch/x86/mm/fault.c (ffffffff8106e900)
Location: arch/x86/include/asm/pgtable.h:1167
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81079e05)
Location: arch/x86/include/asm/pgtable.h:1167
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811f0b2b)
Location: arch/x86/include/asm/pgtable.h:1167
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f67b7)
Location: arch/x86/include/asm/pgtable.h:1167
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
In arch/x86/mm/fault.c (ffffffff810739aa)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81080075)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81205698)
Location: arch/x86/include/asm/pgtable.h:1203
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120ec5c)
Location: arch/x86/include/asm/pgtable.h:1203
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
In arch/x86/mm/fault.c (ffffffff810762a2)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81083188)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81226d78)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81230392)
Location: arch/x86/include/asm/pgtable.h:1269
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
In arch/x86/mm/fault.c (ffffffff8107c566)
Location: arch/x86/include/asm/pgtable.h:1358
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81089d38)
Location: arch/x86/include/asm/pgtable.h:1358
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81239dfd)
Location: arch/x86/include/asm/pgtable.h:1358
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242d42)
Location: arch/x86/include/asm/pgtable.h:1358
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
In arch/x86/mm/fault.c (ffffffff8107faff)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108da97)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124b02d)
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
In mm/memory.c (ffffffff81254bcb)
Location: arch/x86/include/asm/pgtable.h:1384
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
In arch/x86/mm/fault.c (ffffffff81080b8f)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e6f7)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8125951d)
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
In mm/memory.c (ffffffff8126319c)
Location: arch/x86/include/asm/pgtable.h:1384
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
In arch/x86/mm/fault.c (ffffffff81087b67)
Location: arch/x86/include/asm/pgtable.h:1377
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81094867)
Location: arch/x86/include/asm/pgtable.h:1377
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8128abc1)
Location: arch/x86/include/asm/pgtable.h:1377
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294f07)
Location: arch/x86/include/asm/pgtable.h:1377
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
In arch/x86/mm/fault.c (ffffffff81088275)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81093c57)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81294881)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f7fa)
Location: arch/x86/include/asm/pgtable.h:1373
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
In arch/x86/mm/fault.c (ffffffff81088da0)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81094617)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8129a2cb)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a47fd)
Location: arch/x86/include/asm/pgtable.h:1373
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
In arch/x86/mm/fault.c (ffffffff810981ce)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810a455f)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff812daa5a)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e5ab2)
Location: arch/x86/include/asm/pkru.h:19
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
In arch/x86/mm/fault.c (ffffffff810aae34)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810b8d95)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8133a5cc)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347d8f)
Location: arch/x86/include/asm/pkru.h:19
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
In arch/x86/mm/fault.c (ffffffff810c4b17)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d4677)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813b209f)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c01e5)
Location: arch/x86/include/asm/pkru.h:19
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
In arch/x86/mm/fault.c (ffffffff810c6c2e)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d7bb7)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813e6e3f)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4ed8)
Location: arch/x86/include/asm/pkru.h:19
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
In arch/x86/mm/fault.c (ffffffff810cf0c3)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810e0437)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81411abf)
Location: arch/x86/include/asm/pkru.h:19
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff8142156e)
Location: arch/x86/include/asm/pkru.h:19
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
In arch/x86/mm/fault.c (ffffffff8107fb8f)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d6b7)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81251b6d)
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
In mm/memory.c (ffffffff8125b7ec)
Location: arch/x86/include/asm/pgtable.h:1384
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
In arch/x86/mm/fault.c (ffffffff8106ebf2)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c1e7)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81244a6a)
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
In mm/memory.c (ffffffff8124ddb6)
Location: arch/x86/include/asm/pgtable.h:1384
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
In arch/x86/mm/fault.c (ffffffff8107fb3f)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d667)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124f90d)
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
In mm/memory.c (ffffffff8125958c)
Location: arch/x86/include/asm/pgtable.h:1384
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
In arch/x86/mm/fault.c (ffffffff81081c37)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fa27)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8125f2aa)
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
In mm/memory.c (ffffffff81268f96)
Location: arch/x86/include/asm/pgtable.h:1384
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
