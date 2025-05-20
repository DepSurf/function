# Function: <code>__set_phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81025200)
Location: arch/x86/xen/p2m.c:658
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81025200-ffffffff81025350: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810245d0)
Location: arch/x86/xen/p2m.c:658
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff810245d0-ffffffff81024738: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024d00)
Location: arch/x86/xen/p2m.c:658
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81024d00-ffffffff81024e68: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101dee0)
Location: arch/x86/xen/p2m.c:658
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8101dee0-ffffffff8101e048: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101ebf0)
Location: arch/x86/xen/p2m.c:645
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8101ebf0-ffffffff8101ed69: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101f690)
Location: arch/x86/xen/p2m.c:645
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8101f690-ffffffff8101f81b: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101ef50)
Location: arch/x86/xen/p2m.c:647
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
```
**Symbols:**

```
ffffffff8101ef50-ffffffff8101f0d3: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020ab0)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81020ab0-ffffffff81020c33: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021410)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81021410-ffffffff81021593: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023be0)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81023be0-ffffffff81023d63: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810241b0)
Location: arch/x86/xen/p2m.c:650
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff810241b0-ffffffff8102432a: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810263d0)
Location: arch/x86/xen/p2m.c:650
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff810263d0-ffffffff81026548: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102a8e0)
Location: arch/x86/xen/p2m.c:650
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff8102a8e0-ffffffff8102aa58: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102f320)
Location: arch/x86/xen/p2m.c:650
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff8102f320-ffffffff8102f4a5: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81036690)
Location: arch/x86/xen/p2m.c:645
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81036690-ffffffff81036818: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81036600)
Location: arch/x86/xen/p2m.c:645
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81036600-ffffffff81036788: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103c800)
Location: arch/x86/xen/p2m.c:645
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff8103c800-ffffffff8103c988: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/xen/p2m.c (ffff8000100f0898)
Location: arch/arm/xen/p2m.c:169
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/arm/xen/p2m.c:set_foreign_p2m_mapping
```
**Symbols:**

```
ffff8000100f07c0-ffff8000100f07f8: __set_phys_to_machine (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021570)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81021570-ffffffff810216f3: __set_phys_to_machine (STB_GLOBAL)
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810213d0)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff810213d0-ffffffff81021553: __set_phys_to_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021620)
Location: arch/x86/xen/p2m.c:654
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset
```
**Symbols:**

```
ffffffff81021620-ffffffff810217a3: __set_phys_to_machine (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
