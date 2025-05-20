# Function: <code>pci_get_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143ac10)
Location: drivers/pci/search.c:323
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8143ac10-ffffffff8143ac72: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486bb9)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81486b30-ffffffff81486b92: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8369)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/platform/atom/pmc_atom.c:pmc_atom_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814a82e0-ffffffff814a8342: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b22f8)
Location: drivers/pci/search.c:331
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/setup-irq.c:pci_fixup_irqs
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814b2280-ffffffff814b22dc: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f19e8)
Location: drivers/pci/search.c:331
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff814f1970-ffffffff814f19cc: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521c92)
Location: drivers/pci/search.c:332
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81521c00-ffffffff81521c5c: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537ac2)
Location: drivers/pci/search.c:332
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81537a30-ffffffff81537a8c: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156745b)
Location: drivers/pci/search.c:328
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff815673d0-ffffffff81567430: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815887ab)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:has_untrusted_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81588720-ffffffff81588780: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f45b)
Location: drivers/pci/search.c:333
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
  - drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8162f300-ffffffff8162f360: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654aeb)
Location: drivers/pci/search.c:333
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:setup_ibs_ctl
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_driver_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/usb/host/pci-quirks.c:amd_chipset_sb_type_init
  - drivers/hwmon/hwmon.c:hwmon_pci_quirks
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81654990-ffffffff816549f0: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81637482)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff816375f0-ffffffff8163768f: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a76f2)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff816a7870-ffffffff816a7917: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca121)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff817ca2d0-ffffffff817ca381: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e7bd1)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818e7da0-ffffffff818e7e51: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b1f3)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8192b3b0-ffffffff8192b461: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81973a73)
Location: drivers/pci/search.c:330
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:spr_update_device_location
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_count_chabox
  - arch/x86/events/intel/uncore_snbep.c:hswep_has_limit_sbox
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_enable_intel_xhci_ports
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81973b60-ffffffff81973c11: pci_get_device (STB_GLOBAL)
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
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ecd50)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffff8000106ecc98-ffff8000106ecd0c: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887fcc)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
c0887f00-c0887f88: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868c10)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
c000000000868b20-c000000000868ba8: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1bb8)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffe0004c1b48-ffffffe0004c1b98: pci_get_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c63b)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:has_untrusted_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8157c5b0-ffffffff8157c610: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b40b)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:has_untrusted_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8156b380-ffffffff8156b3e0: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c4fb)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:has_untrusted_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8157c470-ffffffff8157c4d0: pci_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_get_device(unsigned int vendor, unsigned int device, struct pci_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff815969ab)
Location: drivers/pci/search.c:327
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/amd_nb.c:next_northbridge
  - arch/x86/kernel/sysfb_efi.c:efifb_set_system
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - kernel/trace/trace_mmiotrace.c:mmio_read
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
  - drivers/pci/pci-sysfs.c:pci_sysfs_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_seq_next
  - drivers/pci/proc.c:pci_seq_start
  - drivers/pci/quirks.c:quirk_msi_intx_disable_ati_bug
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_via_cx700_pci_parking_caching
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_vialatency
  - drivers/pci/quirks.c:quirk_passive_release
  - drivers/pci/quirks.c:pci_apply_final_quirks
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/char/agp/generic.c:agp_device_command
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:has_untrusted_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/pata_sis.c:sis_init_one
  - drivers/usb/core/hcd-pci.c:for_each_companion
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/hwmon/hwmon.c:hwmon_init
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
  - drivers/platform/x86/pmc_atom.c:pmc_atom_init
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/acpi.c:pci_acpi_init
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81596920-ffffffff81596980: pci_get_device (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
