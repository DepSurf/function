# Function: <code>histb_pcie_dbi_w_mode</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void histb_pcie_dbi_w_mode(struct pcie_port *pp, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010737020)
Location: drivers/pci/controller/dwc/pcie-histb.c:77
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
```
**Symbols:**

```
ffff800010737020-ffff800010737084: histb_pcie_dbi_w_mode (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-histb.c (c08be6c8)
Location: drivers/pci/controller/dwc/pcie-histb.c:77
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
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
<b>Arch</b>
<ul>
</ul>
