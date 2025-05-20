# Function: <code>HYPERVISOR_memory_op</code>

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
In arch/x86/xen/enlighten.c (ffffffff818180ed)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff81f6159d)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101e0d3)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exchange_memory
  - arch/x86/xen/mmu.c:xen_setup_machphys_mapping
```
```
In drivers/xen/grant-table.c (ffffffff814c4d59)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff814c6721)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d6eb5)
Location: arch/x86/include/asm/xen/hypercall.h:340
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff81891be7)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff81f89c7d)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101d4c3)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exchange_memory
  - arch/x86/xen/mmu.c:xen_setup_machphys_mapping
```
```
In drivers/xen/grant-table.c (ffffffff815154fa)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff8151744a)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527c55)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff818c64f7)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff81fc5077)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101dbe3)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exchange_memory
  - arch/x86/xen/mmu.c:xen_setup_machphys_mapping
```
```
In drivers/xen/grant-table.c (ffffffff8154198a)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff81543828)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/xlate_mmu.c (ffffffff815541d5)
Location: arch/x86/include/asm/xen/hypercall.h:341
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101b9a6)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff820a4e97)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8101fe83)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a76db)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff815557da)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff815576da)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568d45)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff826a9aa2)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c696)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826ab599)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020ae3)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826ade8b)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff815b942a)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff815bb815)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/xlate_mmu.c (ffffffff815ccef5)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff826d2c2c)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:arch_xen_balloon_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101d0f8)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826d4736)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810215d3)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7213)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff815f2b3f)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/balloon.c (ffffffff815f3d3b)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/xlate_mmu.c (ffffffff8160560d)
Location: arch/x86/include/asm/xen/hypercall.h:346
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c7d8)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82889b65)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020e43)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d2d8)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8160d30f)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff8160fe18)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff816206ed)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101e308)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a0f09)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022916)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4770)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81640d4d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81643c49)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81653bfd)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ec88)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a3fd5)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023256)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a7800)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8166370d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff816661f9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff8167619d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81021248)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82cca59b)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025b06)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdbd9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8171238d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81715939)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726c6d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81021aa8)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82fb6409)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026226)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9a09)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8172f11d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff817322b9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff817431cd)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81023e38)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff831c09a3)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028146)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c40c9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81712b6d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81715d89)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726bbd)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81028198)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff832a1235)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102c79f)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4c51)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8178f62d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81792fe9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a5bed)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8102c719)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff8345024d)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103155f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453e46)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff818c7ad8)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff818cb958)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff818dfb0a)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b5ce)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/setup.c (ffffffff83e6c40f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038d1f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71612)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81a186c5)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81a1cd08)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a33f3a)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c06e)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/setup.c (ffffffff8368cedf)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038c4f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff836924f2)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81a61745)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81a65f08)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7d95a)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbc2e)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/setup.c (ffffffff838bca9f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_release_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f05f)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c2002)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81ab3f75)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81ab8749)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81acfdfa)
Location: arch/x86/include/asm/xen/hypercall.h:414
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
  - drivers/xen/arm-device.c:xen_map_device_mmio
  - drivers/xen/arm-device.c:xen_unmap_device_mmio
  - drivers/xen/xlate_mmu.c:xen_xlate_unmap_gfn_range
  - drivers/xen/xlate_mmu.c:remap_pte_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffff8000100f0d38-ffff8000100f0d44: HYPERVISOR_memory_op (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend.c (ffffffff8101ea72)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101edb8)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82891ffb)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810233b6)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895810)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8162957d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff8162bf29)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163be8d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ec48)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a4fd5)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023216)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8800)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff8165754d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff8165a039)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff81669fdd)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ee98)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a4fa9)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023696)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exchange_memory
  - arch/x86/xen/mmu_pv.c:xen_setup_machphys_mapping
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8810)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:mem_map_via_hcall
```
```
In drivers/xen/grant-table.c (ffffffff81671b4d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
```
```
In drivers/xen/mem-reservation.c (ffffffff81674609)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:xenmem_reservation_decrease
  - drivers/xen/mem-reservation.c:xenmem_reservation_increase
```
```
In drivers/xen/xlate_mmu.c (ffffffff8168459d)
Location: arch/x86/include/asm/xen/hypercall.h:332
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:unmap_gfn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
</details>
</li>
</ul>

## Differences
