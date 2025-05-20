# Function: <code>read_pci_config_16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816fa8b0)
Location: arch/x86/pci/early.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:intel_graphics_stolen
  - arch/x86/kernel/early-quirks.c:intel_graphics_stolen
  - arch/x86/kernel/early-quirks.c:intel_graphics_stolen
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff816fa8b0-ffffffff816fa8f3: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175f730)
Location: arch/x86/pci/early.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff8175f730-ffffffff8175f772: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178bc70)
Location: arch/x86/pci/early.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff8178bc70-ffffffff8178bcb2: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aac30)
Location: arch/x86/pci/early.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff817aac30-ffffffff817aac72: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81822120)
Location: arch/x86/pci/early.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff81822120-ffffffff81822162: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c3f0)
Location: arch/x86/pci/early.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8186c3f0-ffffffff8186c433: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c605)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8188c4d0-ffffffff8188c513: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d6f45)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff818d6e10-ffffffff818d6e53: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff819092c5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81909190-ffffffff819091d3: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9ba5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81bb9a80-ffffffff81bb9ac0: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce4a5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81bce380-ffffffff81bce3c0: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1e55)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81bc1d40-ffffffff81bc1d7e: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c92465)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81c92350-ffffffff81c9238e: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41b55)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81e419f0-ffffffff81e41a3c: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201c245)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8201c0a0-ffffffff8201c0ec: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209c8e5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8209c740-ffffffff8209c78c: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff821740c5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:check_dev_quirk
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:read_agp
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff82173f20-ffffffff82173f6c: read_pci_config_16 (STB_GLOBAL)
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
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a8685)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff818a8550-ffffffff818a8593: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81863095)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff81862f60-ffffffff81862fa3: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9ce5)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff818f9bb0-ffffffff818f9bf3: read_pci_config_16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u16 read_pci_config_16(u8 bus, u8 slot, u8 func, u8 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191ae45)
Location: arch/x86/pci/early.c:27
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:early_pci_scan_bus
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/kernel/early-quirks.c:gen9_stolen_size
  - arch/x86/kernel/early-quirks.c:chv_stolen_size
  - arch/x86/kernel/early-quirks.c:gen8_stolen_size
  - arch/x86/kernel/early-quirks.c:gen6_stolen_size
  - arch/x86/kernel/early-quirks.c:gen3_stolen_size
  - arch/x86/kernel/early-quirks.c:i830_stolen_size
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:intel_remapping_check
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/early-quirks.c:early_pci_clear_msi
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8191ad10-ffffffff8191ad53: read_pci_config_16 (STB_GLOBAL)
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
