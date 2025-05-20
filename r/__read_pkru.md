# Function: <code>__read_pkru</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102c3e1)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b368)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106b52f)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81071ab1)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (ffffffff810778e2)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
```
```
In mm/gup.c (ffffffff811d5ecf)
Location: arch/x86/include/asm/special_insns.h:102
Inline: True
Inline callers:
  - mm/gup.c:vma_permits_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dad04)
Location: arch/x86/include/asm/special_insns.h:102
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
In arch/x86/kernel/process_64.c (ffffffff8102c3a1)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac36)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106f111)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/gup.c (ffffffff81075631)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/pkeys.c (ffffffff8107b76e)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811e47b1)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ea8c9)
Location: arch/x86/include/asm/special_insns.h:94
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
In arch/x86/kernel/process_64.c (ffffffff8102a591)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a9e)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106e8f1)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81079f2e)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff811f0b1f)
Location: arch/x86/include/asm/special_insns.h:94
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f67a6)
Location: arch/x86/include/asm/special_insns.h:94
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
In arch/x86/kernel/process_64.c (ffffffff8102b2f2)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac0e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107399b)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108019e)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8120568c)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120ec4b)
Location: arch/x86/include/asm/special_insns.h:95
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
In arch/x86/kernel/process_64.c (ffffffff8102d0d1)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c0ea)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81076313)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810832a0)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81226d73)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123038f)
Location: arch/x86/include/asm/special_insns.h:95
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
In arch/x86/kernel/process_64.c (ffffffff8102e325)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d56a)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107c5da)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81089e50)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81239df8)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81242d3f)
Location: arch/x86/include/asm/special_insns.h:95
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
