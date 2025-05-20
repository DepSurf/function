# Function: <code>rdpkru</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f629)
Location: arch/x86/include/asm/special_insns.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe1b)
Location: arch/x86/include/asm/special_insns.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107fbdc)
Location: arch/x86/include/asm/special_insns.h:91
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dbfa)
Location: arch/x86/include/asm/special_insns.h:91
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124b028)
Location: arch/x86/include/asm/special_insns.h:91
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81254bc8)
Location: arch/x86/include/asm/special_insns.h:91
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
In arch/x86/kernel/process_64.c (ffffffff8102ff89)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104053b)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81080c6c)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e85a)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81259518)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81263199)
Location: arch/x86/include/asm/special_insns.h:77
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
In arch/x86/kernel/process_64.c (ffffffff81032829)
Location: arch/x86/include/asm/special_insns.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810438dc)
Location: arch/x86/include/asm/special_insns.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81087c0c)
Location: arch/x86/include/asm/special_insns.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810949dd)
Location: arch/x86/include/asm/special_insns.h:78
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8128abbc)
Location: arch/x86/include/asm/special_insns.h:78
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81294f04)
Location: arch/x86/include/asm/special_insns.h:78
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
In arch/x86/kernel/process_64.c (ffffffff8103347d)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104398c)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810883bc)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff81093dcd)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8129487c)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129f7f7)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff81034f75)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810451d0)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81088efd)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8109478d)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8129a2c6)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a47fa)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff8103a253)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81047d0a)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b6a9)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8109822f)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810a454e)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff812daa55)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e5aad)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff810412b0)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81050f90)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056380)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810aae80)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810b8d90)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8133a5c7)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81347d8a)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff8104aa00)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff8105e560)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106402b)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810c4b76)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d4672)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813b209a)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813c01e0)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff8104b240)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff8105fc3e)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106597b)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810c6c23)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810d7bb2)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff813e6e3a)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4ed3)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff810524b0)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/process.c (ffffffff81066d4b)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106cddb)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff810cf0b8)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff810e0432)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81411aba)
Location: arch/x86/include/asm/special_insns.h:80
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff81421569)
Location: arch/x86/include/asm/special_insns.h:80
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
In arch/x86/kernel/process_64.c (ffffffff810300e9)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810406bb)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107fc6c)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d81a)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81251b68)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b7e9)
Location: arch/x86/include/asm/special_insns.h:77
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
In arch/x86/kernel/process_64.c (ffffffff8101fb5e)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fe9b)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8106eccf)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c34a)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff81244a65)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124ddb3)
Location: arch/x86/include/asm/special_insns.h:77
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
In arch/x86/kernel/process_64.c (ffffffff8102ff49)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810404fb)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff8107fc1c)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7ca)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8124f908)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81259589)
Location: arch/x86/include/asm/special_insns.h:77
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
In arch/x86/kernel/process_64.c (ffffffff81030d99)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810418cb)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/fault.c (ffffffff81081d17)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb91)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In mm/gup.c (ffffffff8125f2a5)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268f93)
Location: arch/x86/include/asm/special_insns.h:77
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
</details>
</li>
</ul>

## Differences
