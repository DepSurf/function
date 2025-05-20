# Function: <code>set_phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81025350)
Location: arch/x86/xen/p2m.c:692
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81025350-ffffffff81025393: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024740)
Location: arch/x86/xen/p2m.c:692
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81024740-ffffffff81024784: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024e70)
Location: arch/x86/xen/p2m.c:692
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81024e70-ffffffff81024eb4: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101e050)
Location: arch/x86/xen/p2m.c:692
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8101e050-ffffffff8101e094: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101ed70)
Location: arch/x86/xen/p2m.c:675
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8101ed70-ffffffff8101edb4: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101f820)
Location: arch/x86/xen/p2m.c:675
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8101f820-ffffffff8101f864: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101f0e0)
Location: arch/x86/xen/p2m.c:676
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff8101f0e0-ffffffff8101f123: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020c40)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff81020c40-ffffffff81020c88: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810215a0)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff810215a0-ffffffff810215e8: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023dd9)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff81024210-ffffffff81024258: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024417)
Location: arch/x86/xen/p2m.c:678
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810249c0-ffffffff81024a08: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81026b47)
Location: arch/x86/xen/p2m.c:678
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81026550-ffffffff81026598: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102b067)
Location: arch/x86/xen/p2m.c:678
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff8102aa60-ffffffff8102aaa8: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102f8ee)
Location: arch/x86/xen/p2m.c:678
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff8102f4b0-ffffffff8102f4fb: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81036cae)
Location: arch/x86/xen/p2m.c:673
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81036830-ffffffff8103687b: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81036c1e)
Location: arch/x86/xen/p2m.c:673
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff810367a0-ffffffff810367eb: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103ce1e)
Location: arch/x86/xen/p2m.c:673
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff8103c9a0-ffffffff8103c9eb: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/xen/p2m.c (ffff8000100f0898)
Location: include/xen/arm/page.h:100
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/arm/xen/p2m.c:set_foreign_p2m_mapping
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021700)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff81021700-ffffffff81021748: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021560)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff81021560-ffffffff810215a8: set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810217b0)
Location: arch/x86/xen/p2m.c:683
Inline: True
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_inv_extra_mem
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
**Symbols:**

```
ffffffff810217b0-ffffffff810217f8: set_phys_to_machine (STB_GLOBAL)
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
