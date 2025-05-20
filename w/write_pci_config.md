# Function: <code>write_pci_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816fa900)
Location: arch/x86/pci/early.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff816fa900-ffffffff816fa93d: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175f780)
Location: arch/x86/pci/early.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8175f780-ffffffff8175f7bd: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178bcc0)
Location: arch/x86/pci/early.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8178bcc0-ffffffff8178bcfd: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aac80)
Location: arch/x86/pci/early.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff817aac80-ffffffff817aacbd: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81822170)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81822170-ffffffff818221ad: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c440)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8186c440-ffffffff8186c47e: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c520)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8188c520-ffffffff8188c55e: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d6e60)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff818d6e60-ffffffff818d6e9e: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff819091e0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff819091e0-ffffffff8190921e: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9ac0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
```
**Symbols:**

```
ffffffff81bb9ac0-ffffffff81bb9afe: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce3c0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:pci_enable_pci_io_ecs
```
**Symbols:**

```
ffffffff81bce3c0-ffffffff81bce3fe: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1d80)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81bc1d80-ffffffff81bc1dbe: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c92390)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81c92390-ffffffff81c923ce: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41a40)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81e41a40-ffffffff81e41a8f: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201c100)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8201c100-ffffffff8201c14f: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209c7a0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8209c7a0-ffffffff8209c7ef: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff82173f80)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:early_pci_serial_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff82173f80-ffffffff82173fcf: write_pci_config (STB_GLOBAL)
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
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a85a0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff818a85a0-ffffffff818a85de: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81862fb0)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81862fb0-ffffffff81862fee: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9c00)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff818f9c00-ffffffff818f9c3e: write_pci_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void write_pci_config(u8 bus, u8 slot, u8 func, u8 offset, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191ad60)
Location: arch/x86/pci/early.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:ati_bugs
  - arch/x86/kernel/early-quirks.c:fix_hypertransport_config
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - drivers/usb/early/ehci-dbgp.c:nvidia_set_debug_port
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8191ad60-ffffffff8191ad9e: write_pci_config (STB_GLOBAL)
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
