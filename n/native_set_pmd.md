# Function: <code>native_set_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064660)
Location: arch/x86/include/asm/pgtable_64.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pmd_at
```
**Symbols:**

```
ffffffff81064660-ffffffff81064669: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810642f1)
Location: arch/x86/include/asm/pgtable_64.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pmd_at
```
**Symbols:**

```
ffffffff810642b0-ffffffff810642b9: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810677c1)
Location: arch/x86/include/asm/pgtable_64.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pmd_at
```
**Symbols:**

```
ffffffff81067780-ffffffff81067789: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066a81)
Location: arch/x86/include/asm/pgtable_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pmd_at
```
**Symbols:**

```
ffffffff81066a40-ffffffff81066a49: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106ac00)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: False
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5d21)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
```
```
In mm/memory.c (ffffffff8120d05c)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
```
```
In mm/migrate.c (ffffffff8124e9cc)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255cc4)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259cf2)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable_64.h:74
Inline: True
```
**Symbols:**

```
ffffffff8106ac00-ffffffff8106ac09: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d8c0)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0385)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff8122dc25)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/rmap.c (ffffffff8123dc55)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/migrate.c (ffffffff81272802)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279b88)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c656)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f86b9)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81319411)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8106d8c0-ffffffff8106d8c4: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073a60)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a7095)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff81073a60-ffffffff81073a64: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775c0)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf751)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff810775c0-ffffffff810775c4: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078630)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5bd5)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff81078630-ffffffff81078634: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fa30)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8e45)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff8107fa30-ffffffff8107fa34: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f660)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd68cb)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff8107f660-ffffffff8107f664: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080760)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1315)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff81080760-ffffffff81080764: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f680)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4b9f)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff8108f680-ffffffff8108f684: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0400)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834775d9)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff810a0400-ffffffff810a040c: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b7f70)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c98)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff810b7f70-ffffffff810b7f7c: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb120)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4da8)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff810bb120-ffffffff810bb12c: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2570)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f59a8)
Location: arch/x86/include/asm/pgtable_64.h:81
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c257c: native_set_pmd (STB_LOCAL)
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
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077630)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b6d)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff81077630-ffffffff81077634: native_set_pmd (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b61d)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81028323)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f1b8)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27b4f)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a60de)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810709e8)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81075c73)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff81078bd0)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff8107c87f)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8cf2)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff8124c600)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/mremap.c (ffffffff8125a811)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8125d233)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8125d587)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126fc7f)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a595)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8129c681)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a39ca)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6b25)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81330747)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135a295)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e19)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8186544d)
Location: arch/x86/include/asm/pgtable_64.h:75
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
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775e0)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a6c)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff810775e0-ffffffff810775e4: native_set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079680)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6c12)
Location: arch/x86/include/asm/pgtable_64.h:75
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff81079680-ffffffff81079684: native_set_pmd (STB_LOCAL)
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
