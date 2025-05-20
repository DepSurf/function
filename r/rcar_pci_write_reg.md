# Function: <code>rcar_pci_write_reg</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-rcar.c (ffff800010722740)
Location: drivers/pci/controller/pcie-rcar.c:160
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_rmw32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-rcar.c (c08ae11c)
Location: drivers/pci/controller/pcie-rcar.c:160
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_resume_noirq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_phy_init_gen2
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_config_access
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
