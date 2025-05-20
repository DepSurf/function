# Function: <code>dw_pcie_readl_rc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a5538)
Location: drivers/pci/host/pcie-designware.c:118
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 dw_pcie_readl_rc(struct pcie_port *pp, u32 reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c7810)
Location: drivers/pci/host/pcie-designware.c:144
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff814c74e0-ffffffff814c7505: dw_pcie_readl_rc (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
