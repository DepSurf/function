# Function: <code>find_first_zero_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff813fdf00)
Location: lib/find_bit.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:topology_update_package_map
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-mq-tag.c:blk_mq_has_free_tags
  - lib/idr.c:idr_mark_full
  - lib/idr.c:idr_get_empty_slot
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff813fdf00-ffffffff813fdf58: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81445560)
Location: lib/find_bit.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-mq-tag.c:blk_mq_has_free_tags
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_mark_full
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81445560-ffffffff814455b1: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81463d50)
Location: lib/find_bit.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/lightnvm/sysblk.c:nvm_dev_factory
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81463d50-ffffffff81463da1: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468df0)
Location: lib/find_bit.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff81468df0-ffffffff81468e41: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814950b0)
Location: lib/find_bit.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/hmm.c:hmm_device_new
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff814950b0-ffffffff81495102: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca460)
Location: lib/find_bit.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/hmm.c:hmm_device_new
  - block/blk-tag.c:blk_queue_start_tag
  - block/blk-tag.c:blk_queue_start_tag
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff814ca460-ffffffff814ca4b1: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df180)
Location: lib/find_bit.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/hmm.c:hmm_device_new
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff814df180-ffffffff814df1d1: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150afa0)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:domain_attach_iommu
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
  - drivers/scsi/sr.c:sr_probe
  - drivers/soundwire/bus.c:sdw_handle_slave_status
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8150afa0-ffffffff8150afd6: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528dc0)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81528dc0-ffffffff81528df6: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c690)
Location: lib/find_bit.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - kernel/events/uprobes.c:xol_take_insn_slot
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff8158c690-ffffffff8158c6c8: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a9100)
Location: lib/find_bit.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - kernel/events/uprobes.c:xol_take_insn_slot
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - lib/idr.c:ida_alloc_range
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:__dev_alloc_name
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
**Symbols:**

```
ffffffff815a9100-ffffffff815a9138: find_first_zero_bit (STB_GLOBAL)
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810669d5)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073443)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/events/uprobes.c (ffffffff81256db9)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff813c3209)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff815f1f30)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8161bf74)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165ba93)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165f7d1)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff816e69d5)
Location: include/asm-generic/bitops/find.h:129
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81767cd5)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (ffffffff81771e21)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff81778595)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178922f)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d6fc)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81791e95)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/scsi/sr.c (ffffffff8183e127)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In net/core/sock.c (ffffffff819cac7b)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff819e9c18)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81a6dc31)
Location: include/asm-generic/bitops/find.h:129
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070c55)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f8d5)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/events/uprobes.c (ffffffff81292b49)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff81412b87)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/idr.c (ffffffff8165f0ae)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b455)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce1b0)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816ced78)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d23c1)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff8175fe82)
Location: include/asm-generic/bitops/find.h:132
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec71c)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (ffffffff817f7bc1)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff817fe445)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180f0af)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff81814f7c)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81819c55)
Location: include/asm-generic/bitops/find.h:132
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff818cabef)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a32f)
Location: include/asm-generic/bitops/find.h:132
Inline: True
```
```
In net/core/sock.c (ffffffff81a7a2ab)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff81a9a8e8)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81b272b1)
Location: include/asm-generic/bitops/find.h:132
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ebf5)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ed61)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/events/uprobes.c (ffffffff812e8569)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff8148900a)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/sbitmap.c (ffffffff81773864)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In lib/idr.c (ffffffff8177891a)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8886)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6e67)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f79d5)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fb59b)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff81893820)
Location: include/linux/find.h:163
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8192b344)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (ffffffff81935ee3)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_register
```
```
In drivers/char/agp/generic.c (ffffffff8193c915)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194df30)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956176)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195d5b3)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
```
```
In drivers/scsi/sr.c (ffffffff81a17c24)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f657)
Location: include/linux/find.h:163
Inline: True
```
```
In net/core/sock.c (ffffffff81bed074)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff81c1405f)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81cb0241)
Location: include/linux/find.h:163
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e112f1)
Location: include/linux/find.h:163
Inline: True
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090465)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a35a8)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/events/uprobes.c (ffffffff81352209)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff8151cc84)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/sbitmap.c (ffffffff818a41fb)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/gpio/gpiolib.c (ffffffff818c1212)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81923217)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923f43)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819282ab)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff819db300)
Location: include/linux/find.h:293
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89be1)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (ffffffff81a9d435)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1eb6)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac1eef)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/scsi/sr.c (ffffffff81b98b3e)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c02477)
Location: include/linux/find.h:293
Inline: True
```
```
In net/core/sock.c (ffffffff81d997b2)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff81dc470f)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81e6dff1)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe7c91)
Location: include/linux/find.h:293
Inline: True
```
```
In lib/idr.c (ffffffff820216b5)
Location: include/linux/find.h:293
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093395)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a653b)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/sched/core.c (ffffffff81143008)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/trace/trace.c (ffffffff8127b1b2)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135dad0)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_full
  - kernel/bpf/cpumask.c:bpf_cpumask_first_zero
```
```
In kernel/events/uprobes.c (ffffffff81383419)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff81554e53)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In lib/sbitmap.c (ffffffff818e668b)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/gpio/gpiolib.c (ffffffff819041b7)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966ef7)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967b53)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c4ec)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff81a22fb0)
Location: include/linux/find.h:358
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad53c9)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (ffffffff81ae8d95)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdf66)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0eb85)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/scsi/sr.c (ffffffff81bef0de)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c679e0)
Location: include/linux/find.h:358
Inline: True
```
```
In net/core/sock.c (ffffffff81e07ad2)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff81e3476f)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81eca111)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff82063f11)
Location: include/linux/find.h:358
Inline: True
```
```
In lib/idr.c (ffffffff820a16fb)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a805)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad59b)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In kernel/sched/core.c (ffffffff8114e4d8)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/trace/trace.c (ffffffff81295d92)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff81386870)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_full
  - kernel/bpf/cpumask.c:bpf_cpumask_first_zero
```
```
In kernel/events/uprobes.c (ffffffff813ac833)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In fs/iomap/buffered-io.c (ffffffff8158aff4)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
```
```
In lib/sbitmap.c (ffffffff8192d6ab)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bbdb)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0627)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b12b3)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b5abc)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
```
In drivers/acpi/numa/srat.c (ffffffff81a6da94)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_map_pxm_to_node
```
```
In drivers/tty/serial/max310x.c (ffffffff81b2870f)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/agp/generic.c (ffffffff81b3c225)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_get_key
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b5741e)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b66535)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/scsi/sr.c (ffffffff81c4487d)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In net/core/sock.c (ffffffff81ec4512)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (ffffffff81eeabd7)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
```
```
In net/netlink/genetlink.c (ffffffff81f8dfd1)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
```
```
In net/ncsi/ncsi-manage.c (ffffffff82137051)
Location: include/linux/find.h:358
Inline: True
```
```
In lib/idr.c (ffffffff82179724)
Location: include/linux/find.h:358
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815213a0)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff815213a0-ffffffff815213d6: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81511690)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81511690-ffffffff815116c6: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d430)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff8151d430-ffffffff8151d466: find_first_zero_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536ca0)
Location: lib/find_bit.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/char/agp/generic.c:agp_get_key
  - drivers/iommu/amd_iommu.c:domain_id_alloc
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/scsi/sr.c:sr_probe
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffff81536ca0-ffffffff81536cd6: find_first_zero_bit (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
