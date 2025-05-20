# Function: <code>imx6_pcie_deassert_core_reset</code>

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
void imx6_pcie_deassert_core_reset(struct imx6_pcie *imx6_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731c30)
Location: drivers/pci/controller/dwc/pci-imx6.c:496
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_resume_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
```
**Symbols:**

```
ffff800010731c30-ffff800010732184: imx6_pcie_deassert_core_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void imx6_pcie_deassert_core_reset(struct imx6_pcie *imx6_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb9a8)
Location: drivers/pci/controller/dwc/pci-imx6.c:496
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_resume_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
```
**Symbols:**

```
c08bb9a8-c08bbec8: imx6_pcie_deassert_core_reset (STB_LOCAL)
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
