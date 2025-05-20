# Function: <code>pti_set_user_pgtbl</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073c70)
Location: arch/x86/include/asm/pgtable.h:674
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e5f)
Location: arch/x86/include/asm/pgtable.h:674
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff810777e0)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf516)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff81078850)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5991)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107ff30)
Location: arch/x86/include/asm/pgtable.h:727
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff810952aa)
Location: arch/x86/include/asm/pgtable.h:727
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810952aa-ffffffff810952c0: pti_set_user_pgtbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fb58)
Location: arch/x86/include/asm/pgtable.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda319)
Location: arch/x86/include/asm/pgtable.h:726
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81bda319-ffffffff81bda32f: pti_set_user_pgtbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080c78)
Location: arch/x86/include/asm/pgtable.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc441)
Location: arch/x86/include/asm/pgtable.h:726
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81bcc441-ffffffff81bcc457: pti_set_user_pgtbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108fbe8)
Location: arch/x86/include/asm/pgtable.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca2557)
Location: arch/x86/include/asm/pgtable.h:697
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81ca2557-ffffffff81ca256d: pti_set_user_pgtbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0a28)
Location: arch/x86/include/asm/pgtable.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51d96)
Location: arch/x86/include/asm/pgtable.h:695
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81e51d96-ffffffff81e51dbc: pti_set_user_pgtbl (STB_LOCAL)
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
In arch/x86/kernel/paravirt.c (ffffffff810b8720)
Location: arch/x86/include/asm/pgtable.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0998)
Location: arch/x86/include/asm/pgtable.h:712
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff810bb8f0)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a88)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff810c2d00)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5688)
Location: arch/x86/include/asm/pgtable.h:920
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff81077850)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0929)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b59f)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/ldt.c (ffffffff81026692)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82891789)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f0ac)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27927)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/fault.c (ffffffff8106dbb4)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070bcf)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81076561)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d9e)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c4c9)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8aae)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aab2c)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8124d0c3)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8125d1ba)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a672)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e8b)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable.h:691
Inline: False
```
**Symbols:**

```
ffffffff8106c5b0-ffffffff8106c5c4: pti_set_user_pgtbl (STB_LOCAL)
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
In arch/x86/kernel/paravirt.c (ffffffff81077800)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3828)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/paravirt.c (ffffffff810798a0)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69ce)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>
