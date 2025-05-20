# Function: <code>phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f6083e)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff8101e997)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f884b0)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff8101ddb9)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
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
In arch/x86/xen/enlighten.c (ffffffff81fc389e)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff8101e4a9)
Location: arch/x86/include/asm/xen/page.h:179
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
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
In arch/x86/xen/mmu.c (ffffffff8101a9bf)
Location: arch/x86/include/asm/xen/page.h:205
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5af7)
Location: arch/x86/include/asm/xen/page.h:205
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810249e9)
Location: arch/x86/include/asm/xen/page.h:205
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
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
In arch/x86/xen/mmu.c (ffffffff8101b2bf)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac1c5)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025589)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff8101bc7f)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5209)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810262e3)
Location: arch/x86/include/asm/xen/page.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff8101b93e)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b1e9)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025e93)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d47e)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2631)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027b93)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81023150-ffffffff810231f0: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de1e)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a56e5)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810284d3)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81023a90-ffffffff81023b30: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810201de)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbbbb)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a3e3)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff810260b0-ffffffff81026156: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020c0e)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7a1b)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102adc3)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff810267c0-ffffffff81026866: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022fae)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1f7e)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b9b3)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81bc4ea5-ffffffff81bc4f0e: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102711e)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a29cc)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81030113)
Location: arch/x86/include/asm/xen/page.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81c97713-ffffffff81c9777c: phys_to_machine (STB_LOCAL)
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
In arch/x86/xen/mmu.c (ffffffff8102b2f3)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451dae)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035769)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff81032013)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ea34)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d3d9)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff81032013)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f3b4)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d2a9)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu.c (ffffffff81038303)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bee24)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043769)
Location: arch/x86/include/asm/xen/page.h:230
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de1e)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828936ee)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028633)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81023bf0-ffffffff81023c90: phys_to_machine (STB_LOCAL)
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
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101ddde)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a66e5)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028493)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81023a50-ffffffff81023af0: phys_to_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
xmaddr_t phys_to_machine(xpaddr_t phys);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e02e)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a66b9)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029123)
Location: arch/x86/include/asm/xen/page.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
**Symbols:**

```
ffffffff81023f00-ffffffff81023fa0: phys_to_machine (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
