# Function: <code>dw_pcie_read_dbi</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f2e9)
Location: drivers/pci/controller/dwc/pcie-designware.c:57
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8158fb4b-ffffffff8158fb60: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff8158f290-ffffffff8158f30b: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0f09)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815b18b3-ffffffff815b18c8: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff815b0eb0-ffffffff815b0f2b: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a53c)
Location: drivers/pci/controller/dwc/pcie-designware.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_n_fts
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8165b13c-ffffffff8165b152: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff8165a510-ffffffff8165a577: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167aa1c)
Location: drivers/pci/controller/dwc/pcie-designware.c:139
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81bfddea-ffffffff81bfde00: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff8167a9f0-ffffffff8167aa57: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d421)
Location: drivers/pci/controller/dwc/pcie-designware.c:139
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81befd04-ffffffff81befd1a: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff8165d3f0-ffffffff8165d45f: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfe91)
Location: drivers/pci/controller/dwc/pcie-designware.c:139
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81ceb359-ffffffff81ceb36f: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff816cfe60-ffffffff816cfecf: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:139
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81eb2774-ffffffff81eb278a: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff817f8c30-ffffffff817f8cd9: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924870)
Location: drivers/pci/controller/dwc/pcie-designware.c:311
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81924870-ffffffff81924933: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819685c0)
Location: drivers/pci/controller/dwc/pcie-designware.c:324
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_find_capability
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff819685c0-ffffffff81968683: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b1e00)
Location: drivers/pci/controller/dwc/pcie-designware.c:324
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff819b1e00-ffffffff819b1ec3: dw_pcie_read_dbi (STB_GLOBAL)
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
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072ced0)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_link_up
  - drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_dis
  - drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_en
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_link_up_hip06
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_read
```
**Symbols:**

```
ffff80001072ced0-ffff80001072cf84: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b66c8)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_resume
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_suspend
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_poll_ack
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up
```
**Symbols:**

```
c08b66c8-c08b6778: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e76dc)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_get_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffe0004e76dc-ffffffe0004e7762: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a46c9)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815a5073-ffffffff815a5088: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff815a4670-ffffffff815a46eb: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593869)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81594213-ffffffff81594228: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff81593810-ffffffff8159388b: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4c59)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815a5603-ffffffff815a5618: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff815a4c00-ffffffff815a4c7b: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf059)
Location: drivers/pci/controller/dwc/pcie-designware.c:137
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815bfa03-ffffffff815bfa18: dw_pcie_read_dbi.cold (STB_LOCAL)
ffffffff815bf000-ffffffff815bf07b: dw_pcie_read_dbi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
