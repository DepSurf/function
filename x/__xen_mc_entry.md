# Function: <code>__xen_mc_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101d9d0)
Location: arch/x86/xen/multicalls.c:132
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
**Symbols:**

```
ffffffff8101d9d0-ffffffff8101db2f: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101cd80)
Location: arch/x86/xen/multicalls.c:132
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
**Symbols:**

```
ffffffff8101cd80-ffffffff8101cecc: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101d4a0)
Location: arch/x86/xen/multicalls.c:132
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
**Symbols:**

```
ffffffff8101d4a0-ffffffff8101d5ec: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81019ff0)
Location: arch/x86/xen/multicalls.c:132
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
```
**Symbols:**

```
ffffffff81019ff0-ffffffff8101a135: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101a890)
Location: arch/x86/xen/multicalls.c:133
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8101a890-ffffffff8101a9db: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8101b290)
Location: arch/x86/xen/multicalls.c:133
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff8101b290-ffffffff8101b3df: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81026350)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81026350-ffffffff8102649f: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028050)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028050-ffffffff810281a1: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028950)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028950-ffffffff81028aa1: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102a8b0)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102a8b0-ffffffff8102aa05: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102b1b0)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102b1b0-ffffffff8102b2d7: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8102bd70)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8102bd70-ffffffff8102be96: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81030520)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff81030520-ffffffff810306ae: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81035af0)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff81035af0-ffffffff81035cd4: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103d890)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8103d890-ffffffff8103da76: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff8103d740)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff8103d740-ffffffff8103d926: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81043c00)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
**Symbols:**

```
ffffffff81043c00-ffffffff81043de6: __xen_mc_entry (STB_GLOBAL)
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
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028ab0)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028ab0-ffffffff81028c01: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81028910)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81028910-ffffffff81028a61: __xen_mc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct multicall_space __xen_mc_entry(size_t args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/multicalls.c (ffffffff81029620)
Location: arch/x86/xen/multicalls.c:138
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
**Symbols:**

```
ffffffff81029620-ffffffff810297c1: __xen_mc_entry (STB_GLOBAL)
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
