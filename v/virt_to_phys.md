# Function: <code>virt_to_phys</code>

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
In arch/x86/events/intel/pt.c (ffffffff81013356)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e149)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f705b9)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bdbb)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/tce_64.c (ffffffff81068147)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7aee1)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/kexec_core.c (ffffffff8110c96b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In mm/hugetlb.c (ffffffff81f8bba4)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In lib/swiotlb.c (ffffffff81412463)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/virtio/virtio_ring.c (ffffffff814bfacd)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c0c80)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff814c1870)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff814c32ac)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d43fe)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/char/agp/generic.c (ffffffff8151d58a)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f511)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81521e85)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152d6e5)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815328fc)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/dmar.c (ffffffff8153348a)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815360c6)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c65b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c8b0)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fb6282)
Location: arch/x86/include/asm/io.h:118
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
In arch/x86/events/intel/pt.c (ffffffff81012c8b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/kernel/tboot.c (ffffffff8103df76)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f98d0e)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bf0c)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/tce_64.c (ffffffff81067e97)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a779)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In mm/hugetlb.c (ffffffff81fb5872)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In lib/swiotlb.c (ffffffff8145a1b4)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a535d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f3d5)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525067)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff8157030d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8157258e)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81574d0f)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158233d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81587106)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/dmar.c (ffffffff81587a2c)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158fe4c)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff815911e6)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8159146b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff8167b78d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fe379e)
Location: arch/x86/include/asm/io.h:118
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
In arch/x86/events/intel/pt.c (ffffffff81012d7b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bbb8)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d82a)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/mpparse.c (ffffffff81fd41d7)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee8c)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bae7)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e5d3)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In mm/hugetlb.c (ffffffff81ff21f0)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In lib/swiotlb.c (ffffffff81478c14)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c762d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b525)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551527)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff8159c9c7)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159ec2e)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a137f)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815af82b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815b43c6)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff815b50ec)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bd6b2)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff815beab0)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bed2b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff816a906d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8202156d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In lib/dma-noop.c (ffffffff818c5582)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - lib/dma-noop.c:dma_noop_alloc
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
In arch/x86/events/intel/pt.c (ffffffff8101132b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029dfd)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b88c)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In arch/x86/kernel/mpparse.c (ffffffff820b4ebc)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e52c)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106aea7)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107cbe3)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In mm/hugetlb.c (ffffffff820d4854)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In lib/swiotlb.c (ffffffff81481fdb)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d383d)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154ed85)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81565cf7)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff815b0a25)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b2afe)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b4f93)
Location: arch/x86/include/asm/io.h:118
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c59bb)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca5cd)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff815cafa4)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d32b3)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff815d46d0)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d493b)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff816be31a)
Location: arch/x86/include/asm/io.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff821040e6)
Location: arch/x86/include/asm/io.h:118
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
In arch/x86/events/intel/ds.c (ffffffff8100dcf9)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81012cdb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a5e1)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e2ac)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106225c)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106f7a7)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083ac3)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/events/core.c (ffffffff811c036f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff826dd41a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In lib/swiotlb.c (ffffffff814bde56)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513c0d)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2525)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815c9e97)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816175cb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8161972e)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161bc33)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162aa03)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8163100a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff81631d74)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639fbb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b460)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b6cb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81729cea)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8270d7c7)
Location: arch/x86/include/asm/io.h:131
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
In arch/x86/events/intel/ds.c (ffffffff8100e4a5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81013655)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b1ea)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bd07)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103f833)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106534e)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81071199)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107269f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108676e)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/dma/swiotlb.c (ffffffff8110d7ef)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff811e0783)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff82707955)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea9f2)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602a95)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816510c8)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816533e8)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816558e5)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81667955)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bfc0)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8166d0fa)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81675133)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8167697b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676ca5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81768631)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd432)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82737a5b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:131
Inline: True
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
In arch/x86/events/intel/ds.c (ffffffff8100e975)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81013d55)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102bd1f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102ca11)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cdca)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/tboot.c (ffffffff81040e33)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106afbe)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81077208)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff810786ef)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d9fa)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/dma/swiotlb.c (ffffffff811193ef)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff811f0bee)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828bed24)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In drivers/virtio/virtio_ring.c (ffffffff81604cec)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d7b5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff8166f288)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816715e8)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81673ae5)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685e75)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a45a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8168b4cb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e368f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816947c4)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff81695aeb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695d55)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff8178bd91)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f1987)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:131
Inline: True
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
In arch/x86/events/intel/ds.c (ffffffff8100f245)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015245)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ddfe)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102e771)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ea08)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/tboot.c (ffffffff81043523)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea8e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b197)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c266)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810918aa)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/dma/swiotlb.c (ffffffff81123e54)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff812083b0)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828d7ee0)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163760a)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816509e5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816a4deb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a710a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a95d1)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bd5d3)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1e06)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816c2efb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816cc23a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cd0b9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce3eb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce695)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff817ca179)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8290cfd7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a89)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8f5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015a7d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e70e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f081)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f318)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c73)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107003e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c287)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107d356)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092599)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/dma/swiotlb.c (ffffffff8112fde4)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff81215720)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828e0353)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165935b)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672f65)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816c7b1b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816c9e4a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc311)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816de2d5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4d26)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816e5deb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816efafc)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f0919)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816f222b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f24d5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff817facc9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff829169aa)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff829198ad)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3717)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81005b48)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff81010d05)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81016dfc)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030ca7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810316ca)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031838)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff810475f0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107745e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81083425)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810982a9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff8113ebd0)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff81231ef8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In mm/hugetlb.c (ffffffff82cfd8d4)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (ffffffff8137c37f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81709bd7)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817236b5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff8177cbfa)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177eaba)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81780c71)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179519f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/iommu/amd/init.c (ffffffff8179af76)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c6cb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a72ba)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a83eb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa07b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aaa25)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff818cb60b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82d28de6)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82d2bf6a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9272)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
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
In arch/x86/entry/vdso/vma.c (ffffffff81004af8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff81010263)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101729c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031a17)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810323da)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032538)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81046e20)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077a8e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084c23)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097429)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff8113a240)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff8123bb68)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In mm/hugetlb.c (ffffffff82fea32a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (ffffffff8138a54f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81726b47)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81740365)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/char/agp/generic.c (ffffffff81795d4a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81796fea)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81798c21)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a355f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/iommu/amd/init.c (ffffffff817a9206)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa39b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81c0ca1b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b429b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817b651b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b6f85)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff818d66fb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff830174fe)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a98a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8ec2)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
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
In arch/x86/entry/vdso/vma.c (ffffffff81004ae2)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff810111f8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81018e59)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c507c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81032537)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032f3f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810331d8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103397c)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810345b0)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/kernel/tboot.c (ffffffff810487ce)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107851e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81085813)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097c99)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff8113b7f1)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff812401f9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In mm/hugetlb.c (ffffffff831f4c9d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (ffffffff8139160d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a7f7)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724ee2)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff81778a09)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81779cba)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177b7b0)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178630f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff8178aefa)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178be7c)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d13b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81bfe19d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179735f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817997ad)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a265)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff818b9b8b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff832223dd)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff832259b9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819adf92)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81005112)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff81011f78)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a749)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5a64)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810376b7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810380ed)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81038378)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038e0a)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039850)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/kernel/tboot.c (ffffffff8104f117)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085d7e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094974)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7c69)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff8115e92a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff8127ab85)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In mm/hugetlb.c (ffffffff832daf8a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (ffffffff813df420)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff817864fe)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3d7e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff817fe8e7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff817ffc21)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81801850)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180d171)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff818123fa)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8181375c)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8181449b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81cfff03)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f375)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff81821cf6)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818228a5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff8194f81b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fb93)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c452)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81a60fe6)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c734b8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/x86/coco/tdx/tdx.c (ffffffff81003026)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004176)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff81013838)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101cc18)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454aff)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103d8c7)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e381)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e65f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f388)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fbae)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81040723)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/kernel/tboot.c (ffffffff8105a387)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81096116)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6c19)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd11b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff81188bd2)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
```
```
In kernel/events/core.c (ffffffff812cdbaf)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In io_uring/io_uring.c (ffffffff81e90ac3)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd23e)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd6b5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff8193d115)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8193f061)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81940f20)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194d8b9)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff8195331a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954744)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff819552eb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ec8658)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f22f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81961ea6)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962545)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81aaacce)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52a92)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff834c99ca)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc462)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81bd161b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
```
In net/xdp/xsk.c (ffffffff81e1603d)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/x86/coco/tdx/tdx.c (ffffffff81003525)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/events/intel/ds.c (ffffffff81017908)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81020f92)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e726a2)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810466c7)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047245)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047555)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810484c6)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ae7)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810499e9)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/kernel/tboot.c (ffffffff81068137)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abda6)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bfd99)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d872b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff811c4d91)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
```
```
In kernel/events/core.c (ffffffff81339125)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In io_uring/io_uring.c (ffffffff81789c58)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0c08e)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30b95)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff81a9df65)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0421)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa2fe0)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1dd9)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81ab9432)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba594)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb11d)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb8eb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac3aea)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6da9)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81acabf6)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb295)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81c3211e)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceacd3)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b0b5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d765a2)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81d7d09b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
```
In net/xdp/xsk.c (ffffffff81fed08a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/x86/coco/tdx/tdx.c (ffffffff81002c85)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/events/intel/ds.c (ffffffff810172a8)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81020ce2)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff836935c2)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104690c)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810475c5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810478d5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048872)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d59)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c19)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/kernel/tboot.c (ffffffff810699b6)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af966)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3479)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3cbb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff811d7a9e)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
```
```
In kernel/events/core.c (ffffffff8136a728)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In io_uring/io_uring.c (ffffffff817c9b24)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a54fae)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a3a5)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff81ae9903)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aebd41)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee8b0)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afde8a)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81b0589f)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06b89)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07b24)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b081cb)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f5f4)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13939)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17746)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17f05)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81c993f6)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d538e3)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83731350)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de44e2)
Location: arch/x86/include/asm/io.h:131
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81deb48b)
Location: arch/x86/include/asm/io.h:131
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
  - drivers/hv/hv_common.c:hv_kmsg_dump
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
In arch/x86/coco/tdx/tdx.c (ffffffff81002ea5)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/events/intel/ds.c (ffffffff8101cde8)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81026e03)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b3ce)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d11c)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104da23)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104dfc6)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_do_hypercall
  - arch/x86/hyperv/irqdomain.c:hv_do_hypercall
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f155)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_do_hypercall
  - arch/x86/hyperv/ivm.c:hv_do_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104fd13)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050886)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_do_hypercall
  - arch/x86/hyperv/hv_proc.c:hv_do_hypercall
```
```
In arch/x86/kernel/tboot.c (ffffffff81070b50)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b64f6)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cb8b9)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ec4d9)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff811ecdba)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/events/core.c (ffffffff813930b8)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In mm/hugetlb.c (ffffffff8391ae8b)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In io_uring/io_uring.c (ffffffff8180f6a4)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa6075)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81accef5)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/char/agp/generic.c (ffffffff81b3cd93)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f281)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41df0)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b515fa)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81b5969c)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ab69)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb54)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c1eb)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63ee4)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b68dfb)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6cd36)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d845)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81d4e165)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a3bd)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_do_enable
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff839658f0)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a5d2)
Location: arch/x86/include/asm/io.h:128
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81ea1568)
Location: arch/x86/include/asm/io.h:128
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_kmsg_dump
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
In arch/arm64/kernel/setup.c (ffff800011434234)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099f34)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
```
```
In arch/arm64/kernel/smp.c (0)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6ae8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9f28)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/mm/fault.c (ffff8000100ad408)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:show_pte
```
```
In arch/arm64/mm/mmu.c (ffff800011438474)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
```
```
In arch/arm64/mm/context.c (ffff8000100afcb4)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/arm/mmu.c (ffff8000100ccaec)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_mmu_get_httbr
  - virt/kvm/arm/mmu.c:kvm_mmu_get_httbr
  - virt/kvm/arm/mmu.c:kvm_alloc_stage2_pgd
```
```
In arch/arm/xen/enlighten.c (ffff80001143a80c)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
  - arch/arm/xen/enlighten.c:xen_starting_cpu
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In kernel/sched/core.c (ffff800010da16ac)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/dma/swiotlb.c (ffff8000101965d8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffff80001029f714)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/mmu_context.c (ffff8000102dffd0)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/hugetlb.c (ffff800011459530)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/exec.c (ffff80001038ed40)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In fs/io_uring.c (ffff800010400398)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473f58)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001072056c)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_compose_msi_msg
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107220f8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723928)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b7e0)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_compose_msi_msg
```
```
In drivers/virtio/virtio_ring.c (ffff800010821d68)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In drivers/xen/events/events_fifo.c (ffff800010833b54)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff800010834d44)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffff800011491c44)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffff80001083b218)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083e034)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffff80001087b5a8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb8c8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s2
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s1
```
```
In drivers/usb/core/devio.c (ffff800010a2d4bc)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/efi/arm-runtime.c (ffff800010b610c8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f3e8)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (ffff800010d7dfbc)
Location: arch/arm64/include/asm/memory.h:290
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/arm/kernel/setup.c (c1504a48)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/suspend.c (c0311ad0)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:cpu_suspend
```
```
In arch/arm/kernel/hibernate.c (c0311cf8)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/hibernate.c:arch_restore_image
```
```
In arch/arm/kernel/smp.c (c0312a30)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:__cpu_up
  - arch/arm/kernel/smp.c:__cpu_up
```
```
In arch/arm/mm/idmap.c (c031ee64)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:setup_mm_for_reboot
```
```
In arch/arm/mm/mmu.c (c1509620)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
```
```
In arch/arm/mm/context.c (c03223b0)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334cbc)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - arch/arm/mach-milbeaut/platsmp.c:m10v_die
  - arch/arm/mach-milbeaut/platsmp.c:m10v_die
```
```
In kernel/events/core.c (c04cf614)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In fs/io_uring.c (c05d2730)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/irqchip/irq-gic-v3-its.c (c0819b48)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_build_mapd_cmd
```
```
In drivers/pci/controller/pcie-rcar.c (c08af5f4)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b0458)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5830)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_compose_msi_msg
```
```
In drivers/soc/tegra/pmc.c (c093bd2c)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_suspend
```
```
In drivers/virtio/virtio_ring.c (c093f6a4)
Location: arch/arm/include/asm/memory.h:280
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (c09c0458)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s2
  - drivers/iommu/io-pgtable-arm.c:arm_64_lpae_alloc_pgtable_s1
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_sync_pte
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c31c8)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_runtime_resume
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/exynos-iommu.c (c09c8e78)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_iova_to_phys
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/usb/core/devio.c (c0b01ff8)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/qcom_scm-32.c (c0c3670c)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
```
```
In drivers/remoteproc/remoteproc_core.c (c0c62b80)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (c0e78b50)
Location: arch/arm/include/asm/memory.h:280
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/powerpc/platforms/powernv/ocxl.c (c0000000000e62c4)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_spa_setup
```
```
In arch/powerpc/platforms/pseries/eeh_pseries.c (c0000000000f6440)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_log
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_log
```
```
In arch/powerpc/perf/hv-24x7.c (c00000000012da8c)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-24x7.c:make_24x7_request
  - arch/powerpc/perf/hv-24x7.c:make_24x7_request
  - arch/powerpc/perf/hv-24x7.c:catalog_len_show
  - arch/powerpc/perf/hv-24x7.c:catalog_version_show
  - arch/powerpc/perf/hv-24x7.c:catalog_read
```
```
In arch/powerpc/perf/hv-gpci.c (c0000000001301ec)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-gpci.c:single_gpci_request
```
```
In arch/powerpc/perf/hv-common.c (c000000000130d70)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-common.c:hv_perf_caps_get
```
```
In kernel/dma/swiotlb.c (c0000000001f6818)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (0)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
```
```
In mm/hugetlb.c (c000000001383088)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
```
```
In drivers/pci/controller/pcie-xilinx.c (c00000000089233c)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/virtio/virtio_ring.c (c0000000008d0104)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/char/agp/generic.c (c0000000009568ac)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/usb/core/devio.c (c000000000aeb78c)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: arch/powerpc/include/asm/io.h:773
Inline: True
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
In kernel/dma/swiotlb.c (ffffffe000127f60)
Location: include/asm-generic/io.h:908
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (0)
Location: include/asm-generic/io.h:908
Inline: True
```
```
In mm/hugetlb.c (ffffffe000017b10)
Location: include/asm-generic/io.h:908
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/io.h:908
Inline: True
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e7020)
Location: include/asm-generic/io.h:908
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
```
```
In drivers/virtio/virtio_ring.c (ffffffe00051a93e)
Location: include/asm-generic/io.h:908
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/usb/core/devio.c (ffffffe00064db02)
Location: include/asm-generic/io.h:908
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In net/xdp/xsk.c (0)
Location: include/asm-generic/io.h:908
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a89)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8f5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015a7d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e86e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f1e1)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f478)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/tboot.c (ffffffff81043df3)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106efde)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b287)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c356)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091559)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/dma/swiotlb.c (ffffffff81128594)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff8120dd70)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828c9207)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f1fb)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638c55)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff8168d56b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168f89a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81691d61)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a3d25)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa806)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816ab8cb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b52e2)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b6109)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7a1b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7cc5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff817b30a9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828fbefe)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828fea19)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894a47)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81003169)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e655)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81014d4d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101e216)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8101eb5e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ee02)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/tboot.c (ffffffff81033423)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f3bb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a9b7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106ba83)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81080019)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/dma/swiotlb.c (ffffffff8111ae24)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff81200b40)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828c192c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161381b)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166af5b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d28a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166f751)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81681715)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81687ff6)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8168922b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692f2c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693d49)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8169565b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695905)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff817a4ad9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f379a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f654c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e6e5)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/hv/hv.c (ffffffff8184f93f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_post_message
```
```
In drivers/hv/connection.c (ffffffff818501fc)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/connection.c:vmbus_negotiate_version
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a49)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8b5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015a3d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e6ce)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f041)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2d8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c33)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f48e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b237)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c306)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091509)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/dma/swiotlb.c (ffffffff811262b4)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff8120bb10)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828dbf87)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d19b)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666da5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816bb7db)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816bdb0a)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bffd1)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d1f95)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d89e6)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816d9aab)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e37bc)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e45d9)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5eeb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6195)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff817efb49)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82910fdf)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82913c48)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff81004b89)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/events/intel/ds.c (ffffffff8100faa5)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015c7d)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f4be)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fe61)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030118)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/tboot.c (ffffffff81045033)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107170e)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d337)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107e406)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093939)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/dma/swiotlb.c (ffffffff811328f4)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In kernel/events/core.c (ffffffff8121a920)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/hugetlb.c (ffffffff828e13a8)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166782b)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681355)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/agp/generic.c (ffffffff816d5dab)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d80da)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da5a1)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ec595)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2f96)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816f405b)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fde4c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fec99)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff817005eb)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81700895)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/usb/core/devio.c (ffffffff81809d89)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82917a0c)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8291a90f)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819051a7)
Location: arch/x86/include/asm/io.h:129
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In net/xdp/xsk.c (0)
Location: arch/x86/include/asm/io.h:129
Inline: True
```
</details>
</li>
</ul>

## Differences
