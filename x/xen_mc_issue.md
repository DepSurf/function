# Function: <code>xen_mc_issue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c8d9)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8101e190)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
Direct callers:
  - arch/x86/xen/mmu.c:xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
**Symbols:**

```
ffffffff8101e190-ffffffff8101e202: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c1f0)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8101e90a)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_domain_pte
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_set_pgd_hyper
```
**Symbols:**

```
ffffffff8101d570-ffffffff8101d5db: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c8c0)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/mmu.c (ffffffff8101effa)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_domain_pte
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_set_pgd_hyper
```
**Symbols:**

```
ffffffff8101dc90-ffffffff8101dcfb: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a731)
Location: arch/x86/xen/multicalls.h:42
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f6b1)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021b87)
Location: arch/x86/xen/multicalls.h:42
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff8101ff30-ffffffff8101ff9b: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b001)
Location: arch/x86/xen/multicalls.h:43
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020451)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102267e)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81020ba0-ffffffff81020c0e: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b83c)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102109f)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024eae)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81021690-ffffffff81021708: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102078f)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102251c)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81020f00-ffffffff81020f78: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810222cf)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810234cc)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff810229d0-ffffffff81022a48: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022c0f)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023f8c)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81023310-ffffffff81023388: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102542a)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026939)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff810266d0-ffffffff81026748: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81025b1b)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027148)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81026c80-ffffffff81026ce4: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81027820)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284e0)
Location: arch/x86/xen/multicalls.h:43
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81027820-ffffffff81027887: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff810284e0-ffffffff8102854f: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102be00)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102cbf0)
Location: arch/x86/xen/multicalls.h:43
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8102be00-ffffffff8102be64: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff8102cbf0-ffffffff8102cc5c: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810306a0)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031a00)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff810306a0-ffffffff81030719: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff81031a00-ffffffff81031a7d: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81037cb0)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039270)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81037cb0-ffffffff81037d2d: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff81039270-ffffffff810392f1: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81037c10)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810391b0)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81037c10-ffffffff81037c8d: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff810391b0-ffffffff81039231: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8103df60)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f660)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8103df60-ffffffff8103dfed: xen_mc_issue.constprop.0 (STB_LOCAL)
ffffffff8103f660-ffffffff8103f6e1: xen_mc_issue (STB_LOCAL)
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
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022d6f)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810240ec)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81023470-ffffffff810234e8: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022bcf)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023f4c)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff810232d0-ffffffff81023348: xen_mc_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void xen_mc_issue(unsigned int mode);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022f9f)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024443)
Location: arch/x86/xen/multicalls.h:43
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
```
**Symbols:**

```
ffffffff81023760-ffffffff810237e5: xen_mc_issue (STB_LOCAL)
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
