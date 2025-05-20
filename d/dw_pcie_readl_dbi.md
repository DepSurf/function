# Function: <code>dw_pcie_readl_dbi</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3686)
Location: drivers/pci/dwc/pcie-designware.h:247
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d3983)
Location: drivers/pci/dwc/pcie-designware.h:247
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
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
In drivers/pci/dwc/pcie-designware.c (ffffffff81513a66)
Location: drivers/pci/dwc/pcie-designware.h:252
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513d53)
Location: drivers/pci/dwc/pcie-designware.h:252
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548e45)
Location: drivers/pci/controller/dwc/pcie-designware.h:263
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549787)
Location: drivers/pci/controller/dwc/pcie-designware.h:263
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549b51)
Location: drivers/pci/controller/dwc/pcie-designware.h:263
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f525)
Location: drivers/pci/controller/dwc/pcie-designware.h:267
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fe62)
Location: drivers/pci/controller/dwc/pcie-designware.h:267
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815604d5)
Location: drivers/pci/controller/dwc/pcie-designware.h:267
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158faca)
Location: drivers/pci/controller/dwc/pcie-designware.h:279
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81590001)
Location: drivers/pci/controller/dwc/pcie-designware.h:279
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815908b7)
Location: drivers/pci/controller/dwc/pcie-designware.h:279
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b188d)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1c69)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b25e7)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165b07e)
Location: drivers/pci/controller/dwc/pcie-designware.h:305
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_n_fts
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b629)
Location: drivers/pci/controller/dwc/pcie-designware.h:305
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165bde9)
Location: drivers/pci/controller/dwc/pcie-designware.h:305
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81bfdfb8)
Location: drivers/pci/controller/dwc/pcie-designware.h:313
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b932)
Location: drivers/pci/controller/dwc/pcie-designware.h:313
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167cc86)
Location: drivers/pci/controller/dwc/pcie-designware.h:313
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165e1fe)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e7b2)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fafa)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0c83)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1332)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d271a)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9bef)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa3d3)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbb8a)
Location: drivers/pci/controller/dwc/pcie-designware.h:316
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81926054)
Location: drivers/pci/controller/dwc/pcie-designware.h:417
Inline: True
Inline callers:
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926b13)
Location: drivers/pci/controller/dwc/pcie-designware.h:417
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928d34)
Location: drivers/pci/controller/dwc/pcie-designware.h:417
Inline: True
Inline callers:
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
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8196a1f0)
Location: drivers/pci/controller/dwc/pcie-designware.h:438
Inline: True
Inline callers:
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196ace3)
Location: drivers/pci/controller/dwc/pcie-designware.h:438
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196cf74)
Location: drivers/pci/controller/dwc/pcie-designware.h:438
Inline: True
Inline callers:
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
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b3a19)
Location: drivers/pci/controller/dwc/pcie-designware.h:459
Inline: True
Inline callers:
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
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_version_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b67)
Location: drivers/pci/controller/dwc/pcie-designware.h:459
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b5f44)
Location: drivers/pci/controller/dwc/pcie-designware.h:459
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072da80)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072df20)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff800010730334)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff8000107314bc)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479d30)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_link_up
  - drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_dis
  - drivers/pci/controller/dwc/pci-keystone.c:dw_pcie_dbi_ro_wr_en
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001073352c)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff8000107358ec)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up
```
```
In drivers/pci/controller/dwc/pcie-hisi.c (ffff800010737df8)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_link_up_hip06
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_write
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_cfg_read
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
In drivers/pci/controller/dwc/pcie-designware.c (c08b71b0)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7a0c)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b953c)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c08ba4e4)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_resume
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_suspend
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb264)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_read
  - drivers/pci/controller/dwc/pci-imx6.c:pcie_phy_poll_ack
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08bdf20)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_irq_handler
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_link_up
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e80c6)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8940)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea2b0)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msix
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_msi
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_write_header
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:__dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a504d)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5429)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5da7)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815941ed)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815945c9)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594f47)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a55dd)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a59b9)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6337)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf9dd)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_ext_capability
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815bfdb9)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0737)
Location: drivers/pci/controller/dwc/pcie-designware.h:291
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
</ul>

## Differences
