# Function: <code>pci_host_bridge_from_priv</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-rcar.c (ffff800010722174)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010726c0c)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a888)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
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
In drivers/pci/controller/pci-tegra.c (c08aabf0)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08aeb34)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
```
```
In drivers/pci/controller/pcie-altera.c (c08b20d0)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5a68)
Location: include/linux/pci.h:530
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
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
