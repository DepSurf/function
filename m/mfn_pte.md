# Function: <code>mfn_pte</code>

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
In arch/x86/xen/setup.c (ffffffff81f612fe)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101e94c)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff814c6bff)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/setup.c (ffffffff81f88e8f)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101dd6c)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (ffffffff81022fbb)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In drivers/xen/balloon.c (ffffffff81517494)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/setup.c (ffffffff81fc4283)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101e45c)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (ffffffff8102370b)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In drivers/xen/balloon.c (ffffffff815438c6)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/mmu.c (ffffffff8101a97a)
Location: arch/x86/include/asm/xen/page.h:286
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101b3ed)
Location: arch/x86/include/asm/xen/page.h:286
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff820a4105)
Location: arch/x86/include/asm/xen/page.h:286
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021b18)
Location: arch/x86/include/asm/xen/page.h:286
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/balloon.c (ffffffff81557775)
Location: arch/x86/include/asm/xen/page.h:286
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/mmu.c (ffffffff8101b27a)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101c05e)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff826aa7ef)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022619)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/balloon.c (ffffffff815bb8bd)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/mmu.c (ffffffff8101bc37)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101ca5f)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff826d3cc9)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024e46)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/balloon.c (ffffffff815f3e1a)
Location: arch/x86/include/asm/xen/page.h:293
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/xen/grant-table.c (ffffffff8101c2ef)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82889d5c)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021617)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff8160feba)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101de5d)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a1115)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102322f)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81643cf2)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e7dd)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a41d5)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b6f)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff816662a2)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020d67)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82cca74d)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102627f)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff817159eb)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810215e8)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82fb65bb)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026992)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff8173236b)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102397a)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff831c0cae)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028602)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81715e37)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027c1a)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff832a1568)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102cd1b)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81793097)
Location: arch/x86/include/asm/xen/page.h:319
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/grant-table.c (ffffffff8102c07b)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff83450899)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031c5d)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff818cba10)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/grant-table.c (ffffffff81032fab)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff83e6cdc6)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103952d)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81a1cdd0)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/grant-table.c (ffffffff81032f4b)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff8368d8f6)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103946d)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81a65fd0)
Location: arch/x86/include/asm/xen/page.h:311
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
In arch/x86/xen/grant-table.c (ffffffff8103928b)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff838bd4b6)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f91d)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff81ab8810)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e7ed)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828921fb)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023ccf)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff8162bfd2)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e79d)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a51d5)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b2f)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff8165a0e2)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e9ed)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a51a9)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023fbf)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In drivers/xen/mem-reservation.c (ffffffff816746b2)
Location: arch/x86/include/asm/xen/page.h:320
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
</details>
</li>
</ul>

## Differences
