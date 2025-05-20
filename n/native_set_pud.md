# Function: <code>native_set_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064670)
Location: arch/x86/include/asm/pgtable_64.h:99
Inline: False
```
**Symbols:**

```
ffffffff81064670-ffffffff81064679: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810642c0)
Location: arch/x86/include/asm/pgtable_64.h:99
Inline: False
```
**Symbols:**

```
ffffffff810642c0-ffffffff810642c9: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067790)
Location: arch/x86/include/asm/pgtable_64.h:99
Inline: False
```
**Symbols:**

```
ffffffff81067790-ffffffff81067799: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066a91)
Location: arch/x86/include/asm/pgtable_64.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pud_at
```
**Symbols:**

```
ffffffff81066a50-ffffffff81066a59: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106ac10)
Location: arch/x86/include/asm/pgtable_64.h:110
Inline: False
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable_64.h:110
Inline: True
```
```
In mm/huge_memory.c (ffffffff8124f738)
Location: arch/x86/include/asm/pgtable_64.h:110
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff8106ac10-ffffffff8106ac19: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d8d0)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f01b4)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff81275240)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff8106d8d0-ffffffff8106d8d4: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073a70)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6ebc)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff8128a1ad)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81073a70-ffffffff81073a74: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775d0)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf572)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812a4dce)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff810775d0-ffffffff810775d4: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078640)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59ed)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812b628e)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81078640-ffffffff81078644: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fa40)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8ccd)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812eb3ae)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff8107fa40-ffffffff8107fa44: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f670)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6753)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff812ab099)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7dfd)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff8107f670-ffffffff8107f674: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080770)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e11a5)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff812b0599)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe3ec)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff81080770-ffffffff81080774: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f690)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4a2d)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff812f28c0)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81347f8c)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff8108f690-ffffffff8108f694: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0410)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477456)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff81356663)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff813bc8ba)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810a0410-ffffffff810a041c: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b7f90)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea093b)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff813d0c86)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff8143ee7d)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810b7f90-ffffffff810b7f9c: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb140)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4b01)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff814056bf)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81474643)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810bb140-ffffffff810bb14c: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2590)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5701)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/mremap.c (ffffffff81431be0)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff814a3c26)
Location: arch/x86/include/asm/pgtable_64.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
```
**Symbols:**

```
ffffffff810c2590-ffffffff810c259c: native_set_pud (STB_LOCAL)
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
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077640)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0985)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812ae86e)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81077640-ffffffff81077644: native_set_pud (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b5e4)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8102822e)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f030)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27566)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81070d13)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81075b9d)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8107c534)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8b0a)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/memory.c (ffffffff8124d1b3)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8125d1fe)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8127eff1)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a613)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8129fdf8)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e57)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8186545a)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775f0)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3884)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812ac67e)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff810775f0-ffffffff810775f4: native_set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079690)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6a2a)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/huge_memory.c (ffffffff812bc9fb)
Location: arch/x86/include/asm/pgtable_64.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
**Symbols:**

```
ffffffff81079690-ffffffff81079694: native_set_pud (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
