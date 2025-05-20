# Function: <code>dw_pcie_write_dbi</code>

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
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158fb60)
Location: drivers/pci/controller/dwc/pcie-designware.c:73
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8158fb60-ffffffff8158fb74: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff8158f360-ffffffff8158f3c4: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b18c8)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815b18c8-ffffffff815b18dc: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff815b10d0-ffffffff815b1134: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a932)
Location: drivers/pci/controller/dwc/pcie-designware.c:154
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_n_fts
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8165b128-ffffffff8165b13c: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff8165a4a0-ffffffff8165a504: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167af72)
Location: drivers/pci/controller/dwc/pcie-designware.c:155
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect_regions
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81bfde00-ffffffff81bfde14: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff8167ab10-ffffffff8167ab74: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d9c7)
Location: drivers/pci/controller/dwc/pcie-designware.c:155
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81befd1a-ffffffff81befd2e: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff8165d510-ffffffff8165d57c: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0437)
Location: drivers/pci/controller/dwc/pcie-designware.c:155
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81ceb36f-ffffffff81ceb383: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff816cff80-ffffffff816cffec: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9295)
Location: drivers/pci/controller/dwc/pcie-designware.c:155
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81eb278a-ffffffff81eb279e: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff817f8da0-ffffffff817f8e5a: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924a90)
Location: drivers/pci/controller/dwc/pcie-designware.c:327
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81924a90-ffffffff81924b67: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819687e0)
Location: drivers/pci/controller/dwc/pcie-designware.c:340
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff819687e0-ffffffff819688b7: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2020)
Location: drivers/pci/controller/dwc/pcie-designware.c:340
Inline: True
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq_doorbell
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff819b2020-ffffffff819b20f7: dw_pcie_write_dbi (STB_GLOBAL)
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
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d060)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_ep_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_v3_65_scan_bus
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
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
```
**Symbols:**

```
ffff80001072d060-ffff80001072d0e8: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b681c)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_resume
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_suspend
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_write
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_wait_ack
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
```
**Symbols:**

```
c08b681c-c08b6898: dw_pcie_write_dbi (STB_GLOBAL)
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
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e781a)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffe0004e781a-ffffffe0004e788e: dw_pcie_write_dbi (STB_GLOBAL)
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
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a5088)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815a5088-ffffffff815a509c: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff815a4890-ffffffff815a48f4: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81594228)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81594228-ffffffff8159423c: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff81593a30-ffffffff81593a94: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a5618)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815a5618-ffffffff815a562c: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff815a4e20-ffffffff815a4e84: dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dw_pcie_write_dbi(struct dw_pcie *pci, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bfa18)
Location: drivers/pci/controller/dwc/pcie-designware.c:153
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff815bfa18-ffffffff815bfa2c: dw_pcie_write_dbi.cold (STB_LOCAL)
ffffffff815bf220-ffffffff815bf284: dw_pcie_write_dbi (STB_GLOBAL)
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
