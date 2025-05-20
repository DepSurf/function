# Function: <code>histb_pcie_dbi_r_mode</code>

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
void histb_pcie_dbi_r_mode(struct pcie_port *pp, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010737168)
Location: drivers/pci/controller/dwc/pcie-histb.c:91
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
```
**Symbols:**

```
ffff800010737168-ffff8000107371d4: histb_pcie_dbi_r_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void histb_pcie_dbi_r_mode(struct pcie_port *pp, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-histb.c (c08be66c)
Location: drivers/pci/controller/dwc/pcie-histb.c:91
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
```
**Symbols:**

```
c08be66c-c08be6b4: histb_pcie_dbi_r_mode (STB_LOCAL)
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
