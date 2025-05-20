# Function: <code>phys_to_virt</code>

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
In arch/x86/kernel/head.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff8101f8b7)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81033db9)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f70536)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f7642e)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b9d7)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In kernel/kexec_core.c (ffffffff8110c69a)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/nobootmem.c (ffffffff81f8ac05)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff81f8b2ba)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In lib/swiotlb.c (ffffffff814124e2)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
```
In drivers/pci/rom.c (ffffffff8143ce32)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff8145d64d)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814782fe)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/virtio/virtio_ring.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152ef5f)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535b35)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fb61d8)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81012cf9)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu.c (ffffffff8101ecdb)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81f8ee9f)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051f0e)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f98c7d)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bf92)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9eb7b)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b8b7)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In kernel/kexec_core.c (ffffffff81113fcd)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In mm/nobootmem.c (ffffffff81fb4849)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff81fb4eef)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a225)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_print_info
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/rom.c (ffffffff81488d62)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff814ab855)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c684e)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582055)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158fde0)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fe36d7)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81012de9)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu.c (ffffffff8101f3cb)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81fca22e)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054859)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (ffffffff81fd4146)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef01)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda0fe)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f4d7)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In kernel/kexec_core.c (ffffffff8111b6e8)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In mm/nobootmem.c (ffffffff81ff1235)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff81ff18d6)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In lib/swiotlb.c (ffffffff81478c80)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_print_info
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/rom.c (ffffffff814aa532)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff814cd962)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e88ae)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ae865)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bd641)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff820214a6)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81011399)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810225ba)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff820aa9c2)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff810541ad)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (ffffffff820b4e2e)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb07c)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106ec27)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In kernel/kexec_core.c (ffffffff8111d48b)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/nobootmem.c (ffffffff820d3672)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff820d3d3d)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In lib/swiotlb.c (ffffffff81481f62)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_bounce
  - lib/swiotlb.c:swiotlb_print_info
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/rom.c (ffffffff814b48a2)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff814d988e)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f43ad)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:136
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4466)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d3242)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a0d5)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8210404c)
Location: arch/x86/include/asm/io.h:136
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (0)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81011ad9)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102309a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff826b113a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057f48)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (0)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1a5d)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810740c2)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81128bdb)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/nobootmem.c (ffffffff826dc092)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff826dc75a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In lib/swiotlb.c (ffffffff814bded3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_bounce
  - lib/swiotlb.c:swiotlb_print_info
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_update_mem_attributes
  - lib/swiotlb.c:swiotlb_update_mem_attributes
```
```
In drivers/pci/rom.c (ffffffff814f40c2)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff81519a74)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81534a8d)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162b011)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639f42)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817dffb5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8270d72d)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff826cc58d)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810124a9)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810254f3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff826da7f8)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105ab54)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (ffffffff826e5da3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810653c1)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826eb93b)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81076aea)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8110e4b5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_print_info
  - kernel/dma/swiotlb.c:swiotlb_print_info
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff81136c66)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/nobootmem.c (ffffffff8270657f)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/nobootmem.c:__alloc_memory_core_early
```
```
In mm/memblock.c (ffffffff82706c52)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff81524184)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff8154f57b)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8156a253)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81665bee)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816750cc)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818287f6)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff827379d4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff82882598)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff81012ba9)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810236c3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff82890bda)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff810607d4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289c8e4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b031)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a253d)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff8107d17a)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff81118fb5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff811422c6)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828bde03)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff81539fc4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff81566deb)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81581cb3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168465e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692a3c)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169476b)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854886)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f1900)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff82899526)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff81013f49)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810242b1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828a8147)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063f87)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b46ba)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eb11)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bab49)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81080a1b)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811239a5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8114e07e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828d71fe)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff81569a14)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff81597627)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b25f3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a93249)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bbbb3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c6861)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cd09c)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897336)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8290cf55)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff8289c526)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810146f9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028321)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828ab1a9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064625)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b7b13)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810700c1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c100b)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81081adb)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8112f935)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff81159d8e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828df66f)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff8158a9e4)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff815b89b7)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d3573)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acaa23)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816dea43)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e97d1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f08fc)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9346)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82916928)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff82cc25fb)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff8101652f)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a231)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff82cd0426)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b007)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff82cdcc4d)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810774e1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/mm/ioremap.c (ffffffff81088ade)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113e735)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8116b004)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff82cfcba4)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff81662847)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167d136)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81bc2f19)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff817951c3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a0627)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a83b5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199c750)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82d28d37)
Location: arch/x86/include/asm/io.h:148
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff82fae66e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810169cf)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ac11)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff82fbc266)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106cc77)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff82fc8fe1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077b11)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/mm/ioremap.c (ffffffff81088d1e)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff81139da5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff81167744)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff82fe95cd)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff816834c7)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81bff8af)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81c3be72)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3583)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b1760)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b4265)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be780)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199f7e0)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8301744f)
Location: arch/x86/include/asm/io.h:148
Inline: True
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
In arch/x86/kernel/ebda.c (ffffffff831b866e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff81017caf)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b801)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff831c6a11)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d711)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff831d3923)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810785a1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/mm/ioremap.c (ffffffff8108995b)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113afd3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff811684d4)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff831f3c76)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff816662cb)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81bf13e9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd/iommu.c (ffffffff81786333)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c972)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
```
```
In drivers/iommu/intel/iommu.c (ffffffff817942ef)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179732a)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1fa6)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81984220)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8322235b)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff83298744)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff8101aa36)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ff61)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff832a7837)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078e6f)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff832b6487)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/mm/ioremap.c (ffffffff81098dfb)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8115df18)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8118e214)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff832d9fbc)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff816d93ab)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81cedbff)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180d195)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81814032)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181c20f)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f340)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b097)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2d890)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8330bfd5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff834467e3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d23e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035584)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff83456ce9)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087c66)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff83467ed5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/mm/ioremap.c (ffffffff810abc2a)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811880c5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff811bd774)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff8348efdf)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff8180448b)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81eb516e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194d8e1)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954e04)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195d8eb)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f210)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196b796)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b991e0)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff834c590e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In net/bpf/test_run.c (ffffffff81cb37b5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In arch/x86/kernel/ebda.c (ffffffff83e5fa1f)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff8102162e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d1e4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff83e75207)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109b5f6)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff83e8c1ab)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/mm/ioremap.c (ffffffff810c569a)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811c3f15)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff811ff784)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff83ec13d2)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff81932ceb)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81950da5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1e01)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81abacc0)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb2c2)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac52b0)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:dma_pte_clear_range
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6d7a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5d46)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a0e0)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83f0656a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In net/bpf/test_run.c (ffffffff81e71a05)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In arch/x86/events/intel/pt.c (ffffffff8102137e)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d0c4)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/ebda.c (ffffffff83694bef)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/probe_roms.c (ffffffff83696ce3)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c57f)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff836af9bb)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8e2a)
Location: arch/x86/include/asm/io.h:150
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d6ac5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/kexec_core.c (ffffffff81214b80)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff836e6be2)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff81977132)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8199730f)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdeb2)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b073b7)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b0786a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:fetch_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b11d20)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1390a)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b244c6)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da4b70)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In net/bpf/test_run.c (ffffffff81ecd5d5)
Location: arch/x86/include/asm/io.h:150
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
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
In arch/x86/events/intel/pt.c (ffffffff8102750e)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043584)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/ebda.c (ffffffff838c4adf)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/kernel/probe_roms.c (ffffffff838c6a03)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3b09)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff838dff2b)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/mm/ioremap.c (ffffffff810d152a)
Location: arch/x86/include/asm/io.h:147
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ed2c3)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_init_io_tlb_pool
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/kexec_core.c (ffffffff8122cb20)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff83919192)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/video/console/vgacon.c (ffffffff819c11b6)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b51622)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5b39c)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5b89a)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:fetch_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b6759f)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:domain_setup_first_level
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b68538)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b061)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cb00)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In net/bpf/test_run.c (ffffffff81f90e05)
Location: arch/x86/include/asm/io.h:147
Inline: True
Inline callers:
  - net/bpf/test_run.c:xdp_test_run_init_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9c10)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
  - arch/arm64/kernel/machine_kexec.c:kexec_segment_flush
```
```
In arch/arm64/kernel/crash_dump.c (ffff8000100aba9c)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_dump.c:elfcorehdr_read
```
```
In arch/arm64/mm/dma-mapping.c (ffff8000100acafc)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - arch/arm64/mm/dma-mapping.c:arch_sync_dma_for_cpu
  - arch/arm64/mm/dma-mapping.c:arch_sync_dma_for_device
```
```
In arch/arm64/kvm/va_layout.c (ffff8000100cf83c)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:compute_layout
```
```
In kernel/dma/swiotlb.c (ffff8000101960d0)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffff8000101c94a0)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffff80001145862c)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffff8000106ef508)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/xen/swiotlb-xen.c (ffff800010d9e108)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d80d8)
Location: arch/arm64/include/asm/memory.h:296
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c15048bc)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/atags_parse.c (c1505450)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/kernel/atags_parse.c:setup_machine_tags
```
```
In arch/arm/kernel/devtree.c (c1506488)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:setup_machine_fdt
```
```
In arch/arm/mm/fault.c (c0e9fc64)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_translation_fault
```
```
In arch/arm/mach-hisi/platsmp.c (c032f8fc)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
```
```
In arch/arm/mach-hisi/hotplug.c (c032fdf8)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_cpu_die
```
```
In arch/arm/mach-mvebu/pm.c (c033162c)
Location: arch/arm/include/asm/memory.h:286
Inline: True
```
```
In arch/arm/mach-mediatek/platsmp.c (c1510b64)
Location: arch/arm/include/asm/memory.h:286
Inline: True
```
```
In kernel/kexec_core.c (c040f9a8)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (c15325cc)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (c088a20c)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/iommu/omap-iommu.c (c09c2f84)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_iova_to_phys
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c66b4)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
```
In drivers/iommu/exynos-iommu.c (c09c8ed8)
Location: arch/arm/include/asm/memory.h:286
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_iova_to_phys
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000023324)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:show_regs
```
```
In arch/powerpc/mm/hugetlbpage.c (c000000001358064)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:pseries_alloc_bootmem_huge_page
```
```
In arch/powerpc/platforms/powernv/opal-msglog.c (c0000000000cc344)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-msglog.c:memcons_init
  - arch/powerpc/platforms/powernv/opal-msglog.c:memcons_copy
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000e02a4)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
```
```
In kernel/dma/swiotlb.c (c0000000001f616c)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (c0000000002311f4)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (c000000001381e98)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (c00000000086c4bc)
Location: arch/powerpc/include/asm/io.h:792
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe00012869e)
Location: include/asm-generic/io.h:916
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In mm/memblock.c (ffffffe000016d2c)
Location: include/asm-generic/io.h:916
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffe0004c34d0)
Location: include/asm-generic/io.h:916
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffe0004f1112)
Location: include/asm-generic/io.h:916
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
</details>
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
In arch/x86/kernel/ebda.c (ffffffff8288a526)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810146f9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028481)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828991bb)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064115)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828a5b1a)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f061)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828abfe1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81080adb)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811280e5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff811523ae)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828c8523)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff8157e864)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff815acb07)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7583)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a69893)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a4493)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816af2b1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b60ec)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186da66)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828fbe7c)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff828884ca)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff81014e05)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828914b6)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054415)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff8289dc5c)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f43e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a42a8)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff8106fa2b)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8111a975)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8114568e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828c0c48)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff8156d644)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff8159bca7)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/iommu/amd_iommu.c (ffffffff81681e83)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168cc01)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693d2c)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818370a3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f3718)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ebda.c (ffffffff8289d526)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810146b9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810282e1)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828ac19b)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff810645c5)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b8a2a)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f511)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828beee0)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81080a8b)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff81125e05)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8115025e)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828db2a3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff8157e734)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff815ad097)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7b13)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81ad5ca3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d2703)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dd491)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e45bc)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818be7f6)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82910f5d)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
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
In arch/x86/kernel/ebda.c (ffffffff8289d526)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/ebda.c:reserve_bios_regions
```
```
In arch/x86/events/intel/pt.c (ffffffff810148f9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_read_offset
  - arch/x86/events/intel/pt.c:pt_handle_status
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028f71)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
```
In arch/x86/kernel/probe_roms.c (ffffffff828ac1b9)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065b85)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/mpparse.c (ffffffff828b8b2b)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:default_find_smp_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071791)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c202d)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
```
```
In arch/x86/mm/ioremap.c (ffffffff81082bab)
Location: arch/x86/include/asm/io.h:148
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff81132445)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_update_mem_attributes
```
```
In kernel/kexec_core.c (ffffffff8115d0ae)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In mm/memblock.c (ffffffff828e06c4)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In drivers/pci/rom.c (ffffffff81598be4)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/video/console/vgacon.c (ffffffff815c6b47)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e16b3)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81ae2163)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ecd43)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f7991)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_clear_range
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fec7c)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818dab06)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8291798a)
Location: arch/x86/include/asm/io.h:148
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
</details>
</li>
</ul>

## Differences
