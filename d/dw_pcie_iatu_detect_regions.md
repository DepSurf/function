# Function: <code>dw_pcie_iatu_detect_regions</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dw_pcie_iatu_detect_regions(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167ab80)
Location: drivers/pci/controller/dwc/pcie-designware.c:581
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff8167ab80-ffffffff8167ac95: dw_pcie_iatu_detect_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165dd81)
Location: drivers/pci/controller/dwc/pcie-designware.c:631
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d07f1)
Location: drivers/pci/controller/dwc/pcie-designware.c:631
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9741)
Location: drivers/pci/controller/dwc/pcie-designware.c:646
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
```
</details>
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
