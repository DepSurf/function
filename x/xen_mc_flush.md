# Function: <code>xen_mc_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101d820)
Location: arch/x86/xen/multicalls.c:55
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_end_context_switch
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_leave_lazy_mmu
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
```
**Symbols:**

```
ffffffff8101d820-ffffffff8101d9c9: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101cbd0)
Location: arch/x86/xen/multicalls.c:55
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_end_context_switch
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu.c:xen_cleanhighmap
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
```
**Symbols:**

```
ffffffff8101cbd0-ffffffff8101cd72: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101d2f0)
Location: arch/x86/xen/multicalls.c:55
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_end_context_switch
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu.c:xen_cleanhighmap
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
```
**Symbols:**

```
ffffffff8101d2f0-ffffffff8101d492: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81019e50)
Location: arch/x86/xen/multicalls.c:55
Inline: False
Direct callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
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
```
**Symbols:**

```
ffffffff81019e50-ffffffff81019fe6: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101a6e0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8101a6e0-ffffffff8101a881: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101b0e0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8101b0e0-ffffffff8101b289: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81026710-ffffffff81026727: xen_mc_flush.cold.3 (STB_LOCAL)
ffffffff81026160-ffffffff8102634f: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81028426-ffffffff8102845f: xen_mc_flush.cold (STB_LOCAL)
ffffffff81027e70-ffffffff8102804b: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81028d26-ffffffff81028d5f: xen_mc_flush.cold (STB_LOCAL)
ffffffff81028780-ffffffff81028948: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff8102ac86-ffffffff8102acbf: xen_mc_flush.cold (STB_LOCAL)
ffffffff8102a6e0-ffffffff8102a8ad: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81bd2c89-ffffffff81bd2cc2: xen_mc_flush.cold (STB_LOCAL)
ffffffff8102b000-ffffffff8102b1a2: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81bc4fd6-ffffffff81bc5011: xen_mc_flush.cold (STB_LOCAL)
ffffffff8102bbb0-ffffffff8102bd63: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81c97a58-ffffffff81c97b04: xen_mc_flush.cold (STB_LOCAL)
ffffffff81030320-ffffffff81030514: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81e46e06-ffffffff81e46eb2: xen_mc_flush.cold (STB_LOCAL)
ffffffff810358b0-ffffffff81035ae9: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103d550)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff8103d550-ffffffff8103d872: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103d3f0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff8103d3f0-ffffffff8103d72f: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff810438b0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff810438b0-ffffffff81043bef: xen_mc_flush (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81028e86-ffffffff81028ebf: xen_mc_flush.cold (STB_LOCAL)
ffffffff810288e0-ffffffff81028aa8: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81028ce6-ffffffff81028d1f: xen_mc_flush.cold (STB_LOCAL)
ffffffff81028740-ffffffff81028908: xen_mc_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_mc_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/multicalls.c (0)
Location: arch/x86/xen/multicalls.c:56
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
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
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:__xen_mc_entry
```
**Symbols:**

```
ffffffff81029ad7-ffffffff81029b10: xen_mc_flush.cold (STB_LOCAL)
ffffffff81029410-ffffffff81029613: xen_mc_flush (STB_GLOBAL)
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
