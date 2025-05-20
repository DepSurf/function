# Function: <code>read_pkru</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102c3d4)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b336)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106b448)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81071aa3)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (ffffffff810778d7)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
```
```
In mm/gup.c (ffffffff811d5ec3)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dacf5)
Location: arch/x86/include/asm/pgtable.h:103
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
In arch/x86/kernel/process_64.c (ffffffff8102c394)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac07)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106f0f5)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81075623)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b763)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811e479f)
Location: arch/x86/include/asm/pgtable.h:103
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea8ba)
Location: arch/x86/include/asm/pgtable.h:103
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
In arch/x86/kernel/process_64.c (ffffffff8102a584)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a79)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106e8e2)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81079f23)
Location: arch/x86/include/asm/pgtable.h:115
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811f0b14)
Location: arch/x86/include/asm/pgtable.h:115
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
Location: arch/x86/include/asm/pgtable.h:115
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
In arch/x86/kernel/process_64.c (ffffffff8102b2e5)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103abe9)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107398c)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81080193)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81205681)
Location: arch/x86/include/asm/pgtable.h:125
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
Location: arch/x86/include/asm/pgtable.h:125
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
In arch/x86/kernel/process_64.c (ffffffff8102d081)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c0e3)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107629e)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81083293)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81226ae5)
Location: arch/x86/include/asm/pgtable.h:125
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
Location: arch/x86/include/asm/pgtable.h:125
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
In arch/x86/kernel/process_64.c (ffffffff8102e2d5)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d563)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107c562)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81089e43)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81239be6)
Location: arch/x86/include/asm/pgtable.h:127
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
Location: arch/x86/include/asm/pgtable.h:127
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
In arch/x86/kernel/process_64.c (ffffffff81030052)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe17)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107faf7)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108da66)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124ae16)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/process_64.c (ffffffff810309b2)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040537)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81080b87)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e6c6)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81259306)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/process_64.c (ffffffff81032fc8)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810438d8)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81087b5f)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81094836)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8128a9b0)
Location: arch/x86/include/asm/pgtable.h:131
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
Location: arch/x86/include/asm/pgtable.h:131
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
In arch/x86/kernel/process_64.c (ffffffff81bd31f7)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043988)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8108826d)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81093c26)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81294670)
Location: arch/x86/include/asm/pgtable.h:130
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
Location: arch/x86/include/asm/pgtable.h:130
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
In arch/x86/kernel/process_64.c (ffffffff81bc55e4)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810451cc)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81088d98)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810945e6)
Location: arch/x86/include/asm/pgtable.h:130
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8129a0c0)
Location: arch/x86/include/asm/pgtable.h:130
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
Location: arch/x86/include/asm/pgtable.h:130
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
In arch/x86/kernel/process_64.c (ffffffff81c98201)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81047d05)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b6a4)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8109822a)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810a4549)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff812daa50)
Location: arch/x86/include/asm/pkru.h:35
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
Location: arch/x86/include/asm/pkru.h:35
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
In arch/x86/kernel/process_64.c (ffffffff81e4769b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81050f8b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8105637b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810aae7b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810b8d8b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8133a5c2)
Location: arch/x86/include/asm/pkru.h:35
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
Location: arch/x86/include/asm/pkru.h:35
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
In arch/x86/kernel/process_64.c (ffffffff8104a2d4)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff8105e55b)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064026)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810c4b71)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d466d)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813b2095)
Location: arch/x86/include/asm/pkru.h:35
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
Location: arch/x86/include/asm/pkru.h:35
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
In arch/x86/kernel/process_64.c (ffffffff8104ab14)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff8105fc39)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065976)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810c6c1e)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d7bad)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813e6e35)
Location: arch/x86/include/asm/pkru.h:35
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
Location: arch/x86/include/asm/pkru.h:35
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
In arch/x86/kernel/process_64.c (ffffffff81051d84)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81066d46)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106cdd6)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810cf0b3)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810e042d)
Location: arch/x86/include/asm/pkru.h:35
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81411ab5)
Location: arch/x86/include/asm/pkru.h:35
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
Location: arch/x86/include/asm/pkru.h:35
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
In arch/x86/kernel/process_64.c (ffffffff81030b12)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810406b7)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107fb87)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d686)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81251956)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/process_64.c (ffffffff81020539)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fe97)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106ebea)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c1b6)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124482b)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/process_64.c (ffffffff81030972)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810404f7)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107fb37)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d636)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124f6f6)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/process_64.c (ffffffff81031802)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810418c7)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81081c2f)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108f9f6)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8125f066)
Location: arch/x86/include/asm/pgtable.h:129
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
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
