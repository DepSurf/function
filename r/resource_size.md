# Function: <code>resource_size</code>

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
In arch/x86/kernel/probe_roms.c (ffffffff81033f13)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In kernel/resource.c (ffffffff8108678c)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff8110d599)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In kernel/memremap.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff818199d5)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/vsprintf.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In lib/devres.c (ffffffff8140305b)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81438c01)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/setup-res.c (ffffffff8143d77e)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8143f3d5)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/pci/iov.c (ffffffff81456d5e)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81479c42)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/misc/sram.c (ffffffff8157991f)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8159910a)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8159b9b4)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
```
```
In drivers/nvdimm/label.c (ffffffff8159f6d3)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:165
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81676bf0)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181b7d8)
Location: include/linux/ioport.h:165
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff81f8ef6a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9eea4)
Location: include/linux/ioport.h:193
Inline: True
```
```
In kernel/resource.c (ffffffff8108a65b)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8189453a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/vsprintf.c (ffffffff8143a22a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - lib/vsprintf.c:resource_string
```
```
In lib/devres.c (ffffffff8144ac9b)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146af49)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81475613)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81484a97)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff814895b9)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148a641)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8148e9b8)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (ffffffff814a39cc)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a5499)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814c7356)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff814c81ff)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6c9c)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/pnp/support.c (ffffffff81509961)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8150c143)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510ece)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff815ce9e0)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff815eb06f)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815eed68)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f0548)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3c20)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
```
In drivers/nvdimm/label.c (ffffffff815f679f)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/claim.c (ffffffff815f6d12)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f87ef)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169e1f2)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4f1b)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff820e8554)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175ba61)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff81fca2f9)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda406)
Location: include/linux/ioport.h:193
Inline: True
```
```
In kernel/resource.c (ffffffff8108f5ab)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff818c8c4a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/vsprintf.c (ffffffff8145720a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - lib/vsprintf.c:resource_string
```
```
In lib/devres.c (ffffffff8146965b)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8148a259)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497be3)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff814a5f71)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff814aada9)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814abe31)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff814b01d8)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (ffffffff814c5627)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c7779)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814e948a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff814ea10f)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f9301)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/pnp/support.c (ffffffff8152db81)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81530363)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d64e)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff815fb640)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff81617e7f)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bed8)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161d485)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81622367)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
```
In drivers/nvdimm/label.c (ffffffff8162471a)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/claim.c (ffffffff81624d32)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626a60)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc336)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d301e)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81707c44)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81787fd1)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff820aaa8d)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820baff6)
Location: include/linux/ioport.h:193
Inline: True
```
```
In kernel/resource.c (ffffffff8108c55b)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff8111e4fb)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In kernel/memremap.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff819001aa)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff8146ed4b)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493a8f)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1893)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff814b0076)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff814b50a5)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814b6157)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff814ba9f8)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (ffffffff814cf745)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d38be)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814f5095)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f5e29)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815083f6)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/pnp/support.c (ffffffff81540c19)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81543441)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815512ee)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff8160f39d)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff8162bd3c)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/core.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162ff58)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff8163190e)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636c42)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff81639833)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/claim.c (ffffffff81639d92)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b7df)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc799)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0a63)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e785c)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:193
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d864)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a70e1)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff818f8af2)
Location: include/linux/ioport.h:193
Inline: True
Inline callers:
  - lib/vsprintf.c:resource_string
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
In arch/x86/kernel/probe_roms.c (ffffffff826b1205)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/crash.c (ffffffff81063203)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c19d7)
Location: include/linux/ioport.h:196
Inline: True
```
```
In kernel/resource.c (ffffffff8109329b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff81129c5b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In kernel/memremap.c (ffffffff811c8cba)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/memory_hotplug.c (ffffffff8198a14a)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hmm.c (ffffffff8126de3c)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_add
```
```
In lib/devres.c (ffffffff8149b12b)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cfd1f)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e0263)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff814ef5a6)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff814f460a)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814f830a)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff814fae38)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (ffffffff8150f955)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513c8e)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81535915)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81536769)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154a7e6)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/pnp/support.c (ffffffff815a3d39)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815a6557)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4b12)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff81677c1d)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff8169469c)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81698778)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a267)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e939)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff816a1f12)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff816a2992)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a456b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738d43)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d2f6)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817540ac)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178eae4)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e341)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff8197f5c2)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - lib/vsprintf.c:resource_string
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
In arch/x86/kernel/probe_roms.c (ffffffff826da8c3)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/crash.c (ffffffff81066230)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebc39)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff81096ccb)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff81137bab)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In kernel/memremap.c (ffffffff811e923a)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/memory_hotplug.c (ffffffff819e6a60)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hmm.c (ffffffff812924fc)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
  - mm/hmm.c:hmm_devmem_add
```
```
In lib/devres.c (ffffffff814d03a9)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500f0f)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f603)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff8151f704)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff815246c1)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81528e68)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8152ba48)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8153ddd2)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff81544983)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549678)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8156b3aa)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff8156c3e9)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580e47)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815810c4)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff815db967)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815de39b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ecde2)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff816b368d)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d06ec)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d49f1)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d653b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816db2aa)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff816dda93)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff816deb30)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e0b78)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778da5)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178dc4b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794597)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff817bb306)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d12f9)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818685a9)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff819dcd05)
Location: include/linux/ioport.h:196
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
In arch/x86/kernel/probe_roms.c (ffffffff82890ca5)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/crash.c (ffffffff8106c230)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a283b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff8109efeb)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff811433cb)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In kernel/memremap.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81a21ed0)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hmm.c (ffffffff812a7012)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In lib/devres.c (ffffffff814e4cd9)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815159df)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524cb3)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81535510)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8153a541)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8153ed08)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff81542878)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8155517f)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff8155bd53)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fd28)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560ec9)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81582f2c)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff81584019)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598a3b)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81599264)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff815f5117)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815f7bd4)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816079e2)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff816d494d)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff816f1d1c)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f6731)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f82ee)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fd3ee)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff816ffdf3)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:196
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff81700f00)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81703113)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ecb3)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b4248)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817baae9)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff817e2776)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f8449)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81888629)
Location: include/linux/ioport.h:196
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81a15165)
Location: include/linux/ioport.h:196
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
In arch/x86/kernel/probe_roms.c (ffffffff828a8212)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81070230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ba8b2)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff810a360b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff8114e70c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81a91d26)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812c2c26)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devm_memremap_pages_release
```
```
In lib/devres.c (ffffffff8151157e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543b5f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553371)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81564841)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8156a5bb)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8156e16a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8157218a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81585290)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff8158c005)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158fcd8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81591076)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815b3640)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff815b4c29)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ca1c3)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815ca718)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff81627038)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8162999d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b7d2)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff81710446)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8172b2dc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172fec1)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff817319d8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736d7d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff81739bd8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff8173ad80)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173cd4e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (ffffffff8173fc47)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dd8b7)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f37a7)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa416)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81823016)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81839076)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d2f59)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81a84d16)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff828ab272)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81071230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c0d74)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff810a9c3b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff8115a41c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81ac94b6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812d4ad9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff81531fee)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564a6f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574a0e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81585ac5)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8158b58b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8158f14a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff815937da)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff815a6c70)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff815adbb8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1a48)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815d4880)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff815d5e59)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb42b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb928)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff81648b28)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8164b48d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165dca2)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff81734736)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8174f52c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817540b1)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755b47)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175aa94)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff8175d928)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff8175ea50)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81760b3c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (ffffffff81763e27)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7ef0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180e7da)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818245ca)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b254)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff818544d6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186a9e6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff819052d9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81abbf86)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff82cd04ef)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ad5)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff8107893b)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810b17db)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff8116b1ec)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81bc1b89)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff8130a618)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff815964d4)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In lib/vsprintf.c (ffffffff815f7e1e)
Location: include/linux/ioport.h:207
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606e8c)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff8162c81f)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff81632602)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81634751)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff81641d6a)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8164f979)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff816563b5)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b2cb)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:207
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8167e4c0)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff8167f99e)
Location: include/linux/ioport.h:207
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696e9c)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8169736e)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff82d13afb)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_free_structures
```
```
In drivers/pnp/support.c (ffffffff816f7b63)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff816fa5ab)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/misc/sram.c (ffffffff817f1b77)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8180dc59)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81812e5d)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff818139ff)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a559)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:init_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
```
In drivers/nvdimm/label.c (ffffffff8181d27f)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:207
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182087a)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81823c77)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3735)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818df47a)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f622a)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fd0f4)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:207
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e100)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5474)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb58a1)
Location: include/linux/ioport.h:207
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff82fbc32f)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077105)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff8107894b)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810acf3b)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff8116792c)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81c3ac28)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff815b1f64)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In lib/vsprintf.c (ffffffff8161c4de)
Location: include/linux/ioport.h:211
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b75c)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff8165258f)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff81bf82de)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81659801)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8166814a)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81672e19)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff81676955)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b446)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bb70)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167cdee)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8169d2a0)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff8169e44e)
Location: include/linux/ioport.h:211
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3fec)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b43de)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff830016ea)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_free_structures
```
```
In drivers/pnp/support.c (ffffffff817148b3)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8171705b)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/misc/sram.c (ffffffff818061a7)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8181c989)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818220ad)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822bef)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829679)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:init_dpa_allocation
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
```
In drivers/nvdimm/label.c (ffffffff8182c39d)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f76a)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81834553)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff81834f8d)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b23da)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe_mmaps
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e92da)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fedda)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905a24)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:211
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944f00)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c56a4)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcaa51)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff831c6ada)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077bb5)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff810797dd)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810ae11b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff811686bc)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81c2d257)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff815bcd8a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In lib/vsprintf.c (ffffffff815ffd4e)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f42c)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81635055)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff81bea17d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8163bc71)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8164a61a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81655319)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff81658f75)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165df85)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ea36)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fc6d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81680020)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff816811a0)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696236)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8169660e)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff8320d023)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/pnp/support.c (ffffffff816f5c03)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff816f833d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/misc/sram.c (ffffffff817eacb7)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff817ffd59)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818053bd)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff81805b9f)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c889)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
```
In drivers/nvdimm/label.c (ffffffff8180f6b9)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181288a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81817723)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff8181815d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897d26)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cadbc)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e253b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e9216)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819286f0)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa674)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe391)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff832a7900)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/early-quirks.c (ffffffff832b3ef7)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810853b5)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff8108783d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810bfc9b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff8118e3ec)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81d4bb07)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff8162404a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In lib/vsprintf.c (ffffffff8166dc6e)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e358)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff816a5174)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff81ce4f7a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff816ac6a1)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff816bc241)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff816c71bf)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff816cafe6)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d09f8)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d15d3)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d288d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/osl.c (ffffffff816f6280)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170bfe6)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c3ae)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff832f580c)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/pnp/support.c (ffffffff81770253)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81772add)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/misc/sram.c (ffffffff81877727)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8188a159)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188fa4d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890c61)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896e70)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
```
In drivers/nvdimm/label.c (ffffffff81899c6b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189cf1a)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff818a1d73)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff818a27dc)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81929525)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81964096)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e6bb)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819856c6)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb090)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a580b4)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e2d1)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff83456c9b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/early-quirks.c (ffffffff834656c0)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095765)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff810979e4)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810d7177)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff811bd98b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81f1b3fa)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff816f4479)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In lib/vsprintf.c (ffffffff817882b5)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799f78)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b2825)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pci/pci.c (ffffffff817c76b8)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff81eab9fd)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff817cfafe)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff817e0fdd)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff817ed17b)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff817f15f6)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9944)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa677)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbd15)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/osl.c (ffffffff81822e43)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8183a5f7)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183aa2d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff834adc66)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/pnp/support.c (ffffffff818a56ee)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff818a826e)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/misc/sram.c (ffffffff819bf9e7)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff819d3439)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8e7d)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da961)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819dd3ea)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
```
In drivers/nvdimm/label.c (ffffffff819e3805)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e682c)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff819eb7ad)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff819ebff1)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/dax/hmem/device.c:hmem_register_device
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f558)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abe592)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad9ddc)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae1382)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:212
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2cd30)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7c66)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d2b1)
Location: include/linux/ioport.h:212
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
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
In arch/x86/kernel/probe_roms.c (ffffffff83e753b3)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/early-quirks.c (ffffffff83e88c15)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab365)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff810addd4)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff810f6b97)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff811ff9ca)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff820c336a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffffffff817e6530)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b0604)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cc7a5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pci/pci.c (ffffffff818e4ce2)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff818ecc71)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff818f02ca)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8190417d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819143fb)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff81919b0e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8192553c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819268b5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928fc0)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/acpi/osl.c (ffffffff81953e93)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819622bb)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196fc7e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81970094)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff83ee6d0a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/pnp/support.c (ffffffff819ef56e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff819f26ed)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/reset/reset-simple.c (ffffffff81a477ff)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/misc/sram.c (ffffffff81b35237)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff81b4d8b9)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b53e4d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55d42)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b58bda)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
```
In drivers/nvdimm/label.c (ffffffff81b5f3f6)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62a6c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81b6834d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff81b68bea)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/dax/hmem/device.c:hmem_register_device
  - drivers/dax/hmem/device.c:hmem_register_device
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c47cf7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64f4d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6cc82)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0345)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d7089b)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82016691)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff82045585)
Location: include/linux/ioport.h:219
Inline: True
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
In arch/x86/kernel/probe_roms.c (ffffffff83696e89)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/early-quirks.c (ffffffff836ac135)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aef25)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
```
```
In arch/x86/kernel/crash.c (ffffffff810b0dd4)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff81102fa7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff81214f9e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff8214714a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/pci_iomap.c (ffffffff81825f5e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/pci_iomap.c:pci_iomap
```
```
In lib/devres.c (ffffffff81826cd9)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f35ec)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190f815)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pci/pci.c (ffffffff81928322)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192e294)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:pci_dev_rom_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/rom.c (ffffffff8192fa5f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/setup-res.c (ffffffff81930151)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81933781)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/mmap.c (ffffffff819370e7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/pci/quirks.c (ffffffff8194a6ff)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/pci/quirks.c:quirk_cs5536_vsa
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81957a91)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958cfc)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8195d12e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff8195f734)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819692bf)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196aa85)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d200)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/aperture.c (ffffffff81972e51)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81994a78)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8199630b)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
```
```
In drivers/acpi/osl.c (ffffffff8199a293)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819a86bb)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b623e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b665a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff8370c6ca)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/acpi/ioapic.c (ffffffff81a2443f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
```
In drivers/pnp/support.c (ffffffff81a37d4e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/quirks.c (ffffffff81a39605)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81a3ad8f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a59a79)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5bf81)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
```
In drivers/xen/platform-pci.c (ffffffff81a797f8)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/reset/reset-simple.c (ffffffff81a919af)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad0c48)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad39e5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aef602)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/misc/sram.c (ffffffff81b886f7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff81ba0d29)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba738d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9292)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bac14a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
```
In drivers/nvdimm/label.c (ffffffff81bb2a0e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb604c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81bbb7df)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff81bbc0b0)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c0d011)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_pbar_desc
```
```
In drivers/ata/libata-sff.c (ffffffff81c19132)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c21836)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f571)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caf2d7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbbd7d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc37d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd4292)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d27ca5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff83730775)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dde55b)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82096a41)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff820c3bc2)
Location: include/linux/ioport.h:219
Inline: True
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
In arch/x86/kernel/probe_roms.c (ffffffff838c6ba9)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/early-quirks.c (ffffffff838dc8c5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
```
```
In arch/x86/kernel/crash.c (ffffffff810b7f14)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In kernel/resource.c (ffffffff8110c8d7)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:release_child_resources
```
```
In kernel/kexec_core.c (ffffffff8122cf3e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_get_memory_size
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff822298af)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/pci_iomap.c (ffffffff8187796e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc
  - lib/pci_iomap.c:pci_iomap
```
```
In lib/devres.c (ffffffff818786e9)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193ae1c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81957676)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pci/pci.c (ffffffff81970ae8)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_ioremap_wc_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976c11)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:pci_dev_rom_attr_is_visible
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/pci-sysfs.c:pci_mmap_fits
```
```
In drivers/pci/rom.c (ffffffff819783df)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/setup-res.c (ffffffff81978aec)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8197c4f4)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:adjust_bridge_window
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
```
```
In drivers/pci/mmap.c (ffffffff8197ff47)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/pci/quirks.c (ffffffff81993aaf)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_alder_ioapic
  - drivers/pci/quirks.c:quirk_cs5536_vsa
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff819a1001)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a226c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff819a6781)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff819a8d95)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2b5f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4245)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b61cc)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/video/aperture.c (ffffffff819bcec1)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff819df138)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_remove
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819e098b)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_remove
```
```
In drivers/acpi/osl.c (ffffffff819e2713)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819f10dd)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_get_range
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81a007b2)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00bda)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f78d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/acpi/ioapic.c (ffffffff81a6f27e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
```
In drivers/pnp/support.c (ffffffff81a8350e)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/quirks.c (ffffffff81a84e32)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81a8664f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaaeb9)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_capability
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aad211)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
```
```
In drivers/xen/platform-pci.c (ffffffff81acbc68)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/reset/reset-simple.c (ffffffff81ae4331)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b230e4)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b24aa8)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b42b47)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/misc/sram.c (ffffffff81bdc5c5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff81bf4e89)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfb63d)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocated_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd5d3)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c0048a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
```
```
In drivers/nvdimm/label.c (ffffffff81c06efe)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a63c)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:size_show
```
```
In drivers/dax/bus.c (ffffffff81c0ff1f)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:adjust_dev_dax_range
  - drivers/dax/bus.c:alloc_dev_dax_range
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:create_store
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:available_size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/hmem/device.c (ffffffff81c10830)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/ata/libata-eh.c (ffffffff81c62061)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_pbar_desc
```
```
In drivers/ata/libata-sff.c (ffffffff81c6e222)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c769f6)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd70a4)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d541c8)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d63f8a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d70aed)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d81275)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d8926a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/ioport.h:219
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dddac5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/firmware/efi/sysfb_efi.c (ffffffff83964cd5)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/firmware/efi/sysfb_efi.c:efifb_set_system
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e9446a)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216deb1)
Location: include/linux/ioport.h:219
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff8219e542)
Location: include/linux/ioport.h:219
Inline: True
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
In arch/arm64/kernel/setup.c (ffff800011433d2c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:reserve_memblock_reserved_regions
```
```
In arch/arm64/mm/mmu.c (ffff8000114382e8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100def80)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
```
```
In kernel/resource.c (ffff800010101ccc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffff8000101c9a80)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffff800010d9d27c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/devres.c (ffff80001063e118)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_of_iomap
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470c20)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic.c (ffff800011471b28)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011471f14)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473a64)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/irqchip/irq-mbigen.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475274)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800011475938)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c108)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
```
```
In drivers/bus/arm-cci.c (ffff80001067eeb0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/bus/hisi_lpc.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/bus/fsl-mc/mc-io.c (ffff80001068191c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-io.c:fsl_mc_portal_allocate
```
```
In drivers/bus/fsl-mc/dprc-driver.c (ffff8000106839e0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692bc4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (ffff800010695e60)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699d00)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cb9c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a6610)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
```
```
In drivers/pinctrl/berlin/berlin-bg4ct.c (ffff8000106a801c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
```
```
In drivers/pinctrl/berlin/pinctrl-as370.c (ffff8000106a8124)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106af7a0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd044)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d657c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
```
```
In drivers/pci/pci.c (ffff8000106ea5d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:devm_pci_unmap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffff8000106f05b4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffff8000106f4488)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffff8000106fa700)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffff800010717b00)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/ecam.c (ffff800010719988)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e380)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f5e0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721518)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff8000107296d0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b848)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c3d8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ed5c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffff8000107307a8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479f64)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (ffff80001147a6c0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff800010737654)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-hisi.c (ffff8000107380a8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_platform_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_init
```
```
In drivers/pci/controller/pci-xgene.c (ffff8000107396fc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c7ac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107606b4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff80001076119c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/pci_root.c (ffff800010775344)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
```
In drivers/acpi/pci_mcfg.c (ffff80001079fc3c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/pci_mcfg.c:pci_mcfg_lookup
```
```
In drivers/pnp/support.c (ffff8000107b5d5c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffff8000107b880c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/amba/bus.c (ffff8000107b90dc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_release_regions
  - drivers/amba/bus.c:amba_request_regions
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/hisilicon/clk.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
```
```
In drivers/clk/hisilicon/clk-hi3660-stub.c (ffff8000107d1bb8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
```
```
In drivers/clk/imx/clk-imx8qxp-lpcg.c (ffff8000107e1580)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
```
```
In drivers/clk/sunxi/clk-simple-gates.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
```
```
In drivers/clk/sunxi/clk-sun4i-pll3.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
```
```
In drivers/clk/sunxi/clk-sun8i-bus-gates.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
```
```
In drivers/clk/sunxi/clk-sun8i-mbus.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/clk/sunxi/clk-sun8i-apb0.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
```
```
In drivers/dma/amba-pl08x.c (ffff800010802660)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807f64)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f43c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f7dc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff800010810294)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810e98)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff800010811470)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826940)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/xen/arm-device.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/reset/reset-simple.c (ffff80001084dd84)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/reset/reset-sunxi.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff80001089172c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e6c4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a17e0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/tty/serial/msm_serial.c:msm_release_port
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6584)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/tty/serial/owl-uart.c:owl_uart_release_port
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d2218)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-v3.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/misc/sram.c (ffff80001092b24c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffff80001094e7a0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/mfd/vexpress-sysreg.c (ffff80001094eda8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/mfd/altera-sysmgr.c (ffff80001094f954)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010954b14)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffff800010956d54)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095869c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffff80001095efc0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffff800010960278)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/dax/bus.c (ffff800010963f40)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/ata/ahci_imx.c (ffff8000109b83b4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e582c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs_len
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f0098)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
```
```
In drivers/net/ethernet/freescale/fman/mac.c (ffff8000109f35f0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/mac.c:set_fman_mac_params
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a47328)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5ec84)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/edac/altera_edac.c (ffff800010b15ae8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
```
```
In drivers/firmware/ti_sci.c (ffff800010b51288)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In drivers/firmware/arm_scmi/driver.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b642f0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b655c4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
```
```
In drivers/of/address.c (ffff800010b73e50)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7aca0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b400)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
```
```
In lib/vsprintf.c (ffff800010d964b0)
Location: include/linux/ioport.h:205
Inline: True
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
In arch/arm/mm/cache-l2x0.c (c150af30)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2x0_of_init
```
```
In arch/arm/mach-mvebu/cpu-reset.c (c150d654)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
  - arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init
```
```
In arch/arm/mach-mvebu/pmsu.c (c150dde8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init
```
```
In arch/arm/mach-mvebu/pm.c (c150e1bc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e538)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
```
```
In arch/arm/mach-imx/pm-imx6.c (c1510190)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6_pm_get_base
```
```
In arch/arm/mach-omap2/dma.c (c1513558)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1513d84)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/arm/mach-omap2/prm_common.c (c15168d0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm_common.c:omap2_prm_base_init
```
```
In arch/arm/mach-omap2/cm_common.c (c1516b04)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm_common.c:omap2_cm_base_init
```
```
In arch/arm/mach-rockchip/platsmp.c (c15194bc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c0349908)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/arm/mach-shmobile/pm-rcar-gen2.c (c151a3a8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
```
```
In kernel/resource.c (c035e088)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
  - kernel/resource.c:__release_child_resources
```
```
In kernel/kexec_core.c (c0410a78)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In fs/pstore/ram.c (c06d6ed4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_probe
```
```
In lib/devres.c (c07e3dec)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_of_iomap
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c1549fe0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-orion.c (c154a520)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
```
```
In drivers/irqchip/irq-gic.c (c154ae9c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_of_init
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b23c)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154c618)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d3b8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f174)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c154df68)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/bus/arm-cci.c (c08238d8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/arm-cci.c:cci_probe_ports
```
```
In drivers/bus/mvebu-mbus.c (c154f404)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
  - drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init
```
```
In drivers/bus/omap_l3_smx.c (c0825bfc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
```
```
In drivers/bus/ti-sysc.c (c0828184)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835470)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (c0835e48)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_map_resource
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083add8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data
```
```
In drivers/pinctrl/pinctrl-single.c (c084027c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0842fb4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_resume
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_suspend
```
```
In drivers/pinctrl/berlin/berlin-bg4ct.c (c0848118)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
```
```
In drivers/pinctrl/berlin/pinctrl-as370.c (c0848204)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084d294)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c0851518)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853174)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/gpio/gpio-mmio.c (c0868204)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
```
```
In drivers/gpio/gpio-htc-egpio.c (c1550804)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/pci/pci.c (c088554c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:devm_pci_unmap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (c088b0f0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (c088ef10)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (c0892bc4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (c08a223c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/ecam.c (c08a3400)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_free
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a757c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a81f4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9ad0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08acbb0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_free
```
```
In drivers/pci/controller/pcie-rcar.c (c08aeca8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0f00)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b44f4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b586c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8214)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (c08b98c4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552134)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (c15528cc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/video/fbdev/amba-clcd.c (c08df2bc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
```
In drivers/video/fbdev/mx3fb.c (c08e3124)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e391c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/amba/bus.c (c08e54ac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_release_regions
  - drivers/amba/bus.c:amba_request_regions
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-npcm7xx.c (c15553d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
```
```
In drivers/clk/hisilicon/clk.c (c08f74d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
```
```
In drivers/clk/hisilicon/clk-hi3660-stub.c (c08f95ec)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090d394)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/dma/amba-pl08x.c (c0921410)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (c0925dbc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c158edf4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/ti/edma.c (c092dbf0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_xbar_event_map
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c1591d60)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse
```
```
In drivers/soc/tegra/fuse/tegra-apbmisc.c (c1592294)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
```
```
In drivers/soc/tegra/flowctrl.c (c1592ea8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_init
```
```
In drivers/soc/tegra/pmc.c (c1592ff8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_early_init
  - drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity
```
```
In drivers/virtio/virtio_mmio.c (c0944ad8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/ti-abb-regulator.c (c0955fd0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
```
```
In drivers/reset/reset-simple.c (c095a12c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098ded0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c098e534)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/meson_uart.c (c0999338)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/msm_serial.c (c099b18c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/tty/serial/msm_serial.c:msm_release_port
```
```
In drivers/tty/serial/owl-uart.c (c09a2ac8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/tty/serial/owl-uart.c:owl_uart_request_port
  - drivers/tty/serial/owl-uart.c:owl_uart_release_port
```
```
In drivers/tty/serial/rda-uart.c (c09a3b30)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_release_port
  - drivers/tty/serial/rda-uart.c:rda_uart_request_port
  - drivers/tty/serial/rda-uart.c:rda_uart_request_port
```
```
In drivers/iommu/tegra-gart.c (c09c76d0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
```
```
In drivers/misc/sram.c (c0a09ff0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/sm501.c (c0a0e0b0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_plat_probe
```
```
In drivers/mfd/asic3.c (c15991f4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
```
```
In drivers/mfd/t7l66xb.c (c0a12764)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
```
```
In drivers/mfd/tc6387xb.c (c0a12cdc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
```
```
In drivers/mfd/tc6393xb.c (c0a139b8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/syscon.c (c0a38a34)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/mfd/vexpress-sysreg.c (c0a38c50)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/dax/bus.c (c0a3ab0c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/ata/sata_highbank.c (c0a890f0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
```
```
In drivers/ata/ahci_imx.c (c0a8ad5c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac8848)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs_len
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfda4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d1b4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/dwc2/hcd.c (c0b19a80)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-orion.c (c0b2ffd4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/usb/host/ehci-exynos.c (c0b305dc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-hcd.c (c0b326a0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
```
```
In drivers/usb/host/ohci-exynos.c (c0b38680)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
```
```
In drivers/usb/host/uhci-hcd.c (c0b3a988)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
```
```
In drivers/rtc/rtc-pl031.c (c0b8db18)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe468)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/opp/ti-opp-supply.c (c0bf7934)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/mmc/host/cqhci.c (c0c2f7f0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_pltfm_init
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37858)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
```
```
In drivers/clocksource/sh_cmt.c (c0c44dfc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_mtu2.c (c0c45514)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c465dc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/timer-qcom.c (c15ac4ac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad4c8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
```
```
In drivers/of/address.c (c0c56590)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (c0c60380)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c6089c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b8b0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c388)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/memory/omap-gpmc.c (c0c71e98)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
```
```
In lib/vsprintf.c (c0e91f28)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/vsprintf.c:resource_string
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
In arch/powerpc/kernel/machine_kexec.c (c000000001352c20)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec.c:reserve_crashkernel
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c00000000135966c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node
```
```
In arch/powerpc/sysdev/xive/native.c (c000000001359da0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_init
```
```
In arch/powerpc/sysdev/xive/spapr.c (c00000000135a30c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000013600b8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fad74)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_block_size
```
```
In kernel/resource.c (c000000000149480)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (c0000000002324e4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (c0000000004301c4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (c00000000046e3c0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (c0000000007e790c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_of_iomap
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f360)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000835198)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/gpio/gpio-mmio.c (c00000000084950c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
```
```
In drivers/pci/pci.c (c0000000008658b4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (c00000000086dc0c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (c000000000872ba0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (c000000000878080)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/iov.c (c00000000088735c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/ecam.c (c00000000088977c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f7ac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008911f8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/video/fbdev/simplefb.c (c0000000008c4c4c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d21ac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093b1b8)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/misc/sram.c (c0000000009cab0c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (c0000000009faf14)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a024f4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (c000000000a04b14)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d778)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (c000000000a11744)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (c000000000a12800)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/claim.c (c000000000a1309c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a16288)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (c000000000a1a730)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab7744)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0bdac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1c194)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
```
```
In drivers/of/address.c (c000000000c507bc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In lib/vsprintf.c (c000000000edc6a4)
Location: include/linux/ioport.h:205
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
In arch/riscv/mm/sifive_l2_cache.c (ffffffe000003ea4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
```
```
In kernel/resource.c (ffffffe0000c8d0a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In lib/devres.c (ffffffe00046b684)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_of_iomap
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049efec)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0cc4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ae228)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
```
```
In drivers/pci/pci.c (ffffffe0004c06ee)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:devm_pci_unmap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffe0004c4156)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffe0004c75ca)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffe0004ca832)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffe0004dba4c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffe0004e0d3c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/ecam.c (ffffffe0004e1592)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5580)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6424)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e9020)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffffffe0004ea690)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000507f7a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d0d6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559c6c)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/misc/sram.c (ffffffe0005a3106)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffe0005bf474)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c420c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5edc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca868)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffe0005ccde0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (ffffffe0005cd838)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:nvdimm_badblocks_populate
```
```
In drivers/nvdimm/claim.c (ffffffe0005cdd4c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/dax/bus.c (ffffffe0005d0fda)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000663dd6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/of/address.c (ffffffe000727832)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
```
```
In lib/vsprintf.c (ffffffe0008c053e)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff82899284)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81070230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828abd4a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff810a355b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff81152a3c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81a68326)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812cd0b9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff8152a5ce)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d05f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a82d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
```
```
In drivers/pci/pci.c (ffffffff81579fe5)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8157f40b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582fca)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8158766a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8159a480)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff815a1385)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5208)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6566)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c85d0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff815c9bb9)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pnp/support.c (ffffffff8160eb88)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff816114ed)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623b42)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff816fa7c6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8170449c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817087a1)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a237)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f184)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff81712018)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff81713140)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8171522c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (ffffffff81718517)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c6bba)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc9aa)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e3634)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff818094e6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d696)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81a69e44)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81a5add6)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff8289157f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81060230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a4011)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff81091f3b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff81145d1c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81a24de6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812bdf29)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff8151a8ae)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155b01e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81568725)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8156e1eb)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81571daa)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8157641a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff81589610)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff81590518)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815943a8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595706)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/osl.c (ffffffff815b2c49)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5e4b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c6348)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/nfit/core.c (ffffffff815f6b89)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
```
```
In drivers/pnp/support.c (ffffffff816030d8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81605a3d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81618192)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff816ce5d6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff816d7f1c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dc221)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddcb7)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2c04)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff816e5a98)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff816e6bc0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8cac)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/nvdimm/pmem.c (ffffffff816eaf3e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/blk.c (ffffffff816eec2b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/blk.c:to_dev_offset
```
```
In drivers/dax/bus.c (ffffffff816f0a47)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/dax/device.c (ffffffff816f17d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/device.c:dev_dax_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781fa0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/input/serio/i8042.c (ffffffff817d0c86)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4d66)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e19a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_acpi_remove
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8185fe59)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81a17eb6)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff828ac264)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81070230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bec49)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff810a350b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff811508ec)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81ad4736)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812caec9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff8152665e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558d9f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568d3e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81579815)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8157f2db)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582e9a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff8158752a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff8159a9c0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff815a1908)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5798)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6af6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c8b60)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff815ca139)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df70b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dfc08)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff8163c968)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8163f2cd)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651ae2)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff81727bf6)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff817429ec)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81747571)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff81749007)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174df54)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff81750de8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff81751f10)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753ffc)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (ffffffff817572e7)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817ccd70)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180365a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8181944a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818200d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81848666)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185eb76)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f5cf9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81ac71c6)
Location: include/linux/ioport.h:205
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
In arch/x86/kernel/probe_roms.c (ffffffff828ac282)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:pci_biosrom_size
  - arch/x86/kernel/probe_roms.c:pci_map_biosrom
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81072230)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:determine_backup_region
  - arch/x86/kernel/crash.c:memmap_entry_callback
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1d96)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
```
```
In kernel/resource.c (ffffffff810ab5bb)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/resource.c:resource_alignment
```
```
In kernel/kexec_core.c (ffffffff8115d70c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_get_memory_size
```
```
In mm/memory_hotplug.c (ffffffff81ae0c16)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/memremap.c (ffffffff812dbc07)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In lib/devres.c (ffffffff8153ffde)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572c2f)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582c5e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/pci/pci.c (ffffffff81593d4e)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/setup-res.c (ffffffff8159978b)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8159d34a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
```
In drivers/pci/quirks.c (ffffffff815a19da)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
```
```
In drivers/pci/hotplug/shpchp_sysfs.c (ffffffff815b4e00)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
```
In drivers/pci/iov.c (ffffffff815bbd08)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815bfb98)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815e29c0)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/osl.c (ffffffff815e3f99)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f95cb)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f9ac8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/pnp/support.c (ffffffff81656cb8)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8165961d)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c172)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/misc/sram.c (ffffffff81743036)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/syscon.c (ffffffff8175de2c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817629b1)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764487)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff817693d4)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:resource_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/label.c (ffffffff8176c268)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/linux/ioport.h:205
Inline: True
```
```
In drivers/nvdimm/claim.c (ffffffff8176d390)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_disable
  - drivers/nvdimm/claim.c:devm_nsio_enable
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f46c)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/bus.c (ffffffff81772787)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:size_show
  - drivers/dax/bus.c:region_size_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e7010)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181d76a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8183343a)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8183a044)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/serio/i8042.c (ffffffff81863886)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81879a86)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81916de9)
Location: include/linux/ioport.h:205
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_for_each_region
  - arch/x86/pci/mmconfig-shared.c:is_mmconf_reserved
```
```
In lib/vsprintf.c (ffffffff81ad36a6)
Location: include/linux/ioport.h:205
Inline: True
```
</details>
</li>
</ul>

## Differences
