# Function: <code>__pti_set_user_pgtbl</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108a1f0)
Location: arch/x86/mm/pti.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108a1f0-ffffffff8108a22d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108df60)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108df60-ffffffff8108df9d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108ec10)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108ec10-ffffffff8108ec4d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81095050)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
**Symbols:**

```
ffffffff81095050-ffffffff8109508d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094410)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
**Symbols:**

```
ffffffff81094410-ffffffff8109444d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff81094cf0)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
**Symbols:**

```
ffffffff81094cf0-ffffffff81094d2d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810a4c70)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
**Symbols:**

```
ffffffff810a4c70-ffffffff810a4cad: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810b9540)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
**Symbols:**

```
ffffffff810b9540-ffffffff810b9591: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810d50a0)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810d50a0-ffffffff810d50f1: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810d85a0)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810d85a0-ffffffff810d85f0: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff810e0e20)
Location: arch/x86/mm/pti.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810e0e20-ffffffff810e0e70: __pti_set_user_pgtbl (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108dbd0)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108dbd0-ffffffff8108dc0d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8107c4ce)
Location: arch/x86/mm/pti.c:125
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107c6f0-ffffffff8107c72d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108db80)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108db80-ffffffff8108dbbd: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pgd_t __pti_set_user_pgtbl(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108ff60)
Location: arch/x86/mm/pti.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108ff60-ffffffff8108ff9d: __pti_set_user_pgtbl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
