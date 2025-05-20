# Function: <code>pci_bus_to_host</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/dma-iommu.c (c0000000000508a8)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_get_required_mask
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_dma_supported
```
```
In arch/powerpc/kernel/pci_64.c (c000000000069a18)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_64.c:pcibus_to_node
  - arch/powerpc/kernel/pci_64.c:pcibios_map_io_space
  - arch/powerpc/kernel/pci_64.c:pcibios_unmap_io_space
```
```
In arch/powerpc/kernel/pci-hotplug.c (c00000000006b300)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_add_devices
  - arch/powerpc/kernel/pci-hotplug.c:pcibios_release_device
```
```
In arch/powerpc/kernel/isa-bridge.c (c00000000006ba7c)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_notify
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006e480)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_disable_device
  - arch/powerpc/kernel/pci-common.c:pcibios_enable_device
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pci_proc_domain
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
  - arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range
  - arch/powerpc/kernel/pci-common.c:pci_legacy_write
  - arch/powerpc/kernel/pci-common.c:pci_legacy_read
  - arch/powerpc/kernel/pci-common.c:pci_iobar_pfn
  - arch/powerpc/kernel/pci-common.c:pcibios_reset_secondary_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bridge
  - arch/powerpc/kernel/pci-common.c:pcibios_window_alignment
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006fcc0)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
```
```
In arch/powerpc/kernel/msi.c (c000000000070150)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/kernel/msi.c:arch_teardown_msi_irqs
  - arch/powerpc/kernel/msi.c:arch_setup_msi_irqs
```
```
In arch/powerpc/sysdev/mpic_u3msi.c (c0000000000b71e4)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic_u3msi.c:find_u4_magic_addr
```
```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0138)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_set_tunnel_bar
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_get_phb_node
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_dma_dev_setup
  - arch/powerpc/platforms/powernv/pci.c:pnv_teardown_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d2430)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_npu2_opencapi_cfg_size_fixup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_release_device
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_iov_resource_alignment
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_setup_bridge
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_window_alignment
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_fixup_iov_resources
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_release_m64
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_dev_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_get_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_reserve_m64_pe
```
```
In arch/powerpc/platforms/powernv/npu-dma.c (c0000000000da43c)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_unmap_lpar_dev
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu2_map_lpar_dev
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_try_setup_npu_table_group
```
```
In arch/powerpc/platforms/powernv/pci-cxl.c (c0000000000dc108)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_ioda_msi_setup
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_get_irq_count
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_alloc_hwirq_ranges
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_release_hwirq_ranges
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_release_hwirqs
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_alloc_hwirqs
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_phb_to_cxl_mode
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000df4e0)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_pci_reset_secondary_bus
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
```
```
In arch/powerpc/platforms/powernv/ocxl.c (c0000000000e6284)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_spa_setup
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_set_tl_conf
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag
```
```
In arch/powerpc/platforms/pseries/pci.c (c0000000000f53dc)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/pci.c:pseries_root_bridge_prepare
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abee88)
Location: arch/powerpc/include/asm/pci-bridge.h:164
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
