# Function: <code>ioremap</code>

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
In arch/x86/events/intel/uncore_snb.c (ffffffff81019161)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81033f43)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e3a3)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7abb8)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff81f7b287)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In kernel/memremap.c (ffffffff8118b759)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - kernel/memremap.c:ioremap_cache
```
```
In lib/pci_iomap.c (ffffffff81402bc7)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff81402d44)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8143d075)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81444569)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81476272)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814771a3)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81477e9f)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487e01)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/apei/erst.c (ffffffff814b3e2e)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff814c5485)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4dc8)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff596)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff81519158)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8152189d)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/iommu/dmar.c (ffffffff8181b5bf)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb4f66)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/dmi_scan.c:dmi_walk
```
```
In drivers/firmware/efi/esrt.c (ffffffff81fb6c42)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
```
In arch/x86/pci/common.c (ffffffff816fa730)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101848c)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81033121)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e1c3)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa34b0)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff81fa3db4)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In kernel/memremap.c (ffffffff8119e359)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - kernel/memremap.c:ioremap_cache
```
```
In lib/pci_iomap.c (ffffffff8144a86d)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (0)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/pci/rom.c (ffffffff81488fe1)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff8149043c)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814c47b2)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c56dd)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c63e9)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6caf)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/apei/erst.c (ffffffff815037a5)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81516725)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd1399)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815501fa)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff8156bebd)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815747c6)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/iommu/dmar.c (ffffffff818957b6)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff815ec1a6)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/firmware/efi/esrt.c (ffffffff81fe472a)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
```
In arch/x86/pci/common.c (ffffffff8175f540)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101865c)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81032da1)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103da73)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdede9)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff81fdf67c)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In kernel/memremap.c (ffffffff811add89)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - kernel/memremap.c:ioremap_cache
```
```
In lib/pci_iomap.c (ffffffff8146922d)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (0)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/pci/rom.c (ffffffff814aa7b1)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff814b1c8c)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814e67a2)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e76cd)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e8449)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f9314)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525924)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff81527995)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81542b95)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ed34)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c82a)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff8159862d)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a0e46)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/iommu/dmar.c (ffffffff818ca006)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81618d9a)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff820232c8)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In arch/x86/pci/common.c (ffffffff8178ba70)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81016b24)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81030f41)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103bb03)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820bfcc4)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff820c041b)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In kernel/memremap.c (ffffffff811b5249)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - kernel/memremap.c:ioremap_cache
```
```
In lib/pci_iomap.c (ffffffff8146e90b)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff8146eab4)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff814b4b01)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff814bc0de)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff814d2d1c)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814f2431)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814f3311)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f4035)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814f4d17)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81508409)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8153850e)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff8153a8e5)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81556a56)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f07f7)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815908e4)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff815ac6fd)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b5687)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff820f402f)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff81901586)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:192
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8162cebb)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82106008)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
  - drivers/firmware/efi/apple-properties.c:map_properties
```
```
In arch/x86/pci/common.c (ffffffff817aa9e4)
Location: arch/x86/include/asm/io.h:192
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/events/intel/uncore_snb.c (ffffffff810173a4)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81033151)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e523)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c7e2e)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff826c85fa)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In lib/pci_iomap.c (ffffffff8149aceb)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff8149ae94)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff814f4321)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff814fc54e)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8151315e)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81532af1)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815339d1)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81534715)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8153555c)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154a7f9)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81599d2b)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff8159d445)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff815bac26)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826fa001)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f55c4)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff816130bd)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c6d4)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624fb8)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff8198b5b6)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8169558a)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8270f6f4)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff82710009)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81017d70)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff8103448a)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff8103fab2)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f1f3c)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff826f26c6)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - arch/x86/platform/efi/early_printk.c:early_efi_map_fb
```
```
In lib/pci_iomap.c (ffffffff814cff9b)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff814d015e)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff815243e1)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff8152d233)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153ed14)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81548569)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81568561)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8156948d)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8156a615)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8156aef6)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580aea)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d159b)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff815d518a)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff815f28c5)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8272436d)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e850)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff8164cd6a)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81656310)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165f264)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff819e7ec9)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:210
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff816d164a)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dce91)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8273a295)
Location: arch/x86/include/asm/io.h:210
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81018570)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff8103566a)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff810410b2)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828a0d45)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a8ced)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/efi/early_printk.c (ffffffff828a94b3)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - arch/x86/platform/efi/early_printk.c:early_efi_map_fb
```
```
In lib/pci_iomap.c (ffffffff814e48b4)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff814e4a8e)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8153a195)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81544083)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81556144)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8155ec29)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8157ffc4)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81580eed)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8158207d)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81582a30)
Location: arch/x86/include/asm/io.h:211
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598759)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eabb1)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff815ee93a)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff8160deb5)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc546)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164ca90)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff8166aeea)
Location: arch/x86/include/asm/io.h:211
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81674193)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d720)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff81a23339)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:211
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff816f2cda)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff828f4209)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81019b30)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c29f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff810377ea)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81043782)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828b8f97)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c14ad)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In lib/pci_iomap.c (ffffffff8151127d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff81511438)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff81569c15)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff815736c0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81586568)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8158f0b9)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815b0605)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815b155f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b2743)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815b30cd)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ca07d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c94b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff816206da)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81640c35)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6e23)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816815cf)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff816a0a86)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a9110)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b4058)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff816c3857)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8172c2ac)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd96c)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a4b0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cc1f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81037fba)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81043ed2)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828bf485)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c792c)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810983d4)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
```
```
In lib/pci_iomap.c (ffffffff81531ced)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff81531ea8)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8158abe5)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81594d10)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a7f48)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815b0cd9)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815d1585)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815d24df)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d36c3)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815d4054)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb29d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e3eb)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff816421ba)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff816635f5)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffe7a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3c7f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff816c3826)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cbe50)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d6d38)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff816e67a7)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff817504fc)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f0486)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088950)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:efi_ioremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81088950-ffffffff8108896c: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088b90)
Location: arch/x86/mm/ioremap.c:324
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81088b90-ffffffff81088bac: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81089830)
Location: arch/x86/mm/ioremap.c:326
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81089830-ffffffff8108984c: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81098cd0)
Location: arch/x86/mm/ioremap.c:326
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff81098cd0-ffffffff81098cec: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810aba90)
Location: arch/x86/mm/ioremap.c:331
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map
```
**Symbols:**

```
ffffffff810aba90-ffffffff810ababb: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5490)
Location: arch/x86/mm/ioremap.c:338
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810c5490-ffffffff810c54bb: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c8c20)
Location: arch/x86/mm/ioremap.c:343
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/platform/x86/intel/pmc/core.c:get_primary_reg_base
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810c8c20-ffffffff810c8c4b: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ioremap(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d1320)
Location: arch/x86/mm/ioremap.c:343
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
  - arch/x86/kernel/quirks.c:ich_force_enable_hpet
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/eisa.c:eisa_bus_probe
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - lib/pci_iomap.c:pci_iomap
  - lib/devres.c:devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/hpet.c:hpet_resources
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
```
**Symbols:**

```
ffffffff810d1320-ffffffff810d134b: ioremap (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ioremap(resource_size_t res_cookie, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/ioremap.c (c031f20c)
Location: arch/arm/mm/ioremap.c:377
Inline: False
Direct callers:
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
  - arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus
  - arch/arm/mach-exynos/platsmp.c:exynos_scu_enable
  - arch/arm/mach-highbank/highbank.c:highbank_init_irq
  - arch/arm/mach-hisi/platmcpm.c:hip04_smp_init
  - arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary
  - arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_setup_boot_addr_wa
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_get_base
  - arch/arm/mach-imx/mach-imx51.c:imx51_dt_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init_module
  - arch/arm/mach-omap2/omap4-common.c:omap4_sar_ram_init
  - arch/arm/mach-omap2/omap4-common.c:omap_l2_cache_init
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus
  - arch/arm/mach-omap2/prm_common.c:omap2_prm_base_init
  - arch/arm/mach-omap2/cm_common.c:omap2_cm_base_init
  - arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus
  - fs/pstore/ram_core.c:persistent_ram_new
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/bus/arm-cci.c:cci_probe_ports
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_prepare_cpus
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/mfd/sm501.c:sm501_plat_probe
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/timer-imx-gpt.c:mxc_timer_init
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
**Symbols:**

```
c031f20c-c031f23c: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ioremap(phys_addr_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/ioremap.c (c000000000089410)
Location: arch/powerpc/mm/ioremap.c:11
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
  - arch/powerpc/kernel/eeh.c:eeh_dev_break_write
  - arch/powerpc/kernel/legacy_serial.c:serial_dev_init
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
  - arch/powerpc/sysdev/xive/native.c:xive_native_populate_irq_data
  - arch/powerpc/sysdev/xive/native.c:xive_native_populate_irq_data
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_populate_irq_data
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_populate_irq_data
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/vas-window.c:map_mmio_region
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_map_xsl_regs
  - kernel/iomem.c:memremap
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_init_fb
  - drivers/video/fbdev/offb.c:offb_map_reg
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
**Symbols:**

```
c000000000089410-c000000000089454: ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ioremap(phys_addr_t offset, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/ioremap.c (ffffffe0000b9f5c)
Location: arch/riscv/mm/ioremap.c:66
Inline: False
Direct callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:ioremap_cache
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_range
  - lib/devres.c:__devm_ioremap
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
**Symbols:**

```
ffffffe0000b9f5c-ffffffe0000b9fe8: ioremap (STB_GLOBAL)
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a4b0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cc1f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff8103811a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81044052)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828aa45b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b28c4)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In lib/pci_iomap.c (ffffffff8152a2cd)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff8152a488)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8157ea65)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81588ba0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b758)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4499)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c5595)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c64ef)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c76d3)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c8060)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81609e1b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/xen/grant-table.c (ffffffff81629465)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e7697)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816696df)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff81689276)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816918a0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c788)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff816ac287)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81704bec)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvme/host/pci.c (ffffffff8174d216)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remap_bar
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818917b6)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81019a70)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c30f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81027afa)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81033672)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828a2727)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaa36)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In lib/pci_iomap.c (ffffffff8151a5ad)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff8151a768)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8156d845)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81577950)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158a8e8)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81593639)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5cbd)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fba5b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff815fe5ca)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/char/hpet.c (ffffffff81666d06)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166f290)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167a178)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff81689be7)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff816d866c)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvme/host/pci.c (ffffffff8172d0b6)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remap_bar
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184a9c6)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a470)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cbdf)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81037f7a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81043e92)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828bd35a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c57c3)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In lib/pci_iomap.c (ffffffff8152635d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff81526518)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff8157e935)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81588a60)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159bc98)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4a29)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c5b25)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c6a7f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7c63)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c85f0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df57d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163222b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff81635ffa)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81657435)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb19d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697abf)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff816b74e6)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bfb10)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca9f8)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff816da467)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff817439bc)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e52b6)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a6b0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d04f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
```
```
In arch/x86/kernel/probe_roms.c (ffffffff81038f7a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/tboot.c (ffffffff81045292)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
```
```
In arch/x86/kernel/eisa.c (ffffffff828c04a7)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/eisa.c:eisa_bus_probe
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8969)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_ioremap
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810998a4)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
  - arch/x86/platform/uv/bios_uv.c:uv_bios_init
```
```
In lib/pci_iomap.c (ffffffff8153fcdd)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffffffff8153fe98)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
```
```
In drivers/pci/rom.c (ffffffff81598de5)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff815a2f10)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b60c8)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815bee29)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815df6c5)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815e061f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e1803)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815e2194)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f943d)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164c55b)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffffffff8165030a)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/xen/grant-table.c (ffffffff81671a35)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900ece)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1f1f)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/char/hpet.c (ffffffff816d1ec6)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da0e0)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i830_setup
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4ec8)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/dmar.c (ffffffff816f4a17)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/mfd/syscon.c (0)
Location: arch/x86/include/asm/io.h:208
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8175ee0c)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901f16)
Location: arch/x86/include/asm/io.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
