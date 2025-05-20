# Function: <code>native_set_p4d</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066a60)
Location: arch/x86/include/asm/pgtable_64.h:133
Inline: False
```
**Symbols:**

```
ffffffff81066a60-ffffffff81066a69: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b0e0)
Location: arch/x86/include/asm/pgtable_64.h:219
Inline: False
```
**Symbols:**

```
ffffffff8106b0e0-ffffffff8106b104: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106dd70)
Location: arch/x86/include/asm/pgtable_64.h:220
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0157)
Location: arch/x86/include/asm/pgtable_64.h:220
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8106dd70-ffffffff8106dd8e: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073c70)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e5f)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81073c70-ffffffff81073c8e: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810777e0)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf516)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810777e0-ffffffff810777fe: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078850)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5991)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81078850-ffffffff8107886e: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fc50)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c6c)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8107fc50-ffffffff8107fc7f: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f870)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd66f2)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8107f870-ffffffff8107f89f: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810808e0)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1146)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810808e0-ffffffff81080916: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f830)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c49cd)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108f830-ffffffff8108f866: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0550)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834773fa)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810a0550-ffffffff810a0593: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b8180)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0a05)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810b8180-ffffffff810b81c0: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb310)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a84)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810bb310-ffffffff810bb350: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2720)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5684)
Location: arch/x86/include/asm/pgtable_64.h:142
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810c2720-ffffffff810c2760: native_set_p4d (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077850)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0929)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81077850-ffffffff8107786e: native_set_p4d (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b59f)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/ldt.c (ffffffff81026692)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82891789)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f0ac)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a278f9)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dbb4)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070bcf)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81076561)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d9e)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c4c9)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8aae)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aab2c)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8124d0c3)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8125d1ba)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a672)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e8b)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077800)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3828)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81077800-ffffffff8107781e: native_set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810798a0)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69ce)
Location: arch/x86/include/asm/pgtable_64.h:136
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810798a0-ffffffff810798be: native_set_p4d (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
