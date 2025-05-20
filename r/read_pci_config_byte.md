# Function: <code>read_pci_config_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816fa870)
Location: arch/x86/pci/early.c:18
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff816fa870-ffffffff816fa8af: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175fa10)
Location: arch/x86/pci/early.c:18
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff8175f6f0-ffffffff8175f72e: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178bf50)
Location: arch/x86/pci/early.c:18
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff8178bc30-ffffffff8178bc6e: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aaeee)
Location: arch/x86/pci/early.c:18
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff817aabf0-ffffffff817aac2e: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818223de)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
```
**Symbols:**

```
ffffffff818220e0-ffffffff8182211e: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c6de)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8186c3b0-ffffffff8186c3ef: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c670)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8188c490-ffffffff8188c4cf: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d6fbb)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff818d6dd0-ffffffff818d6e0f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8190933b)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81909150-ffffffff8190918f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9c18)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_mem_size
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel/irq_remapping.c:ir_parse_one_ioapic_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_one_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff81bb9a40-ffffffff81bb9a7f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce518)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_mem_size
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel/irq_remapping.c:ir_parse_one_ioapic_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_one_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff81bce340-ffffffff81bce37f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1eca)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_mem_size
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff81bc1d00-ffffffff81bc1d3d: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c924da)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_mem_size
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff81c92310-ffffffff81c9234d: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41bc6)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_mem_size
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff81e419a0-ffffffff81e419eb: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201c2b6)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff8201c040-ffffffff8201c08b: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209c956)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff8209c6e0-ffffffff8209c72b: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff82174136)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel/irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
**Symbols:**

```
ffffffff82173ec0-ffffffff82173f0b: read_pci_config_byte (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a86fb)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff818a8510-ffffffff818a854f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186310b)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff81862f20-ffffffff81862f5f: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9d5b)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff818f9b70-ffffffff818f9baf: read_pci_config_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u8 read_pci_config_byte(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191aebb)
Location: arch/x86/pci/early.c:19
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i85x_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_tseg_size
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/iommu/intel_irq_remapping.c:ir_parse_ioapic_hpet_scope
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8191acd0-ffffffff8191ad0f: read_pci_config_byte (STB_GLOBAL)
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
