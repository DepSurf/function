# Function: <code>of_irq_parse_and_map_pci</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:42
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:43
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:46
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:35
Inline: False
```
</details>
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
int of_irq_parse_and_map_pci(const struct pci_dev *dev, u8 slot, u8 pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffff8000106f99d0)
Location: drivers/pci/of.c:469
Inline: False
```
**Symbols:**

```
ffff8000106f99d0-ffff8000106f9b90: of_irq_parse_and_map_pci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_irq_parse_and_map_pci(const struct pci_dev *dev, u8 slot, u8 pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0892018)
Location: drivers/pci/of.c:469
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_map_irq
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_map_irq
```
**Symbols:**

```
c0892018-c0892210: of_irq_parse_and_map_pci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_irq_parse_and_map_pci(const struct pci_dev *dev, u8 slot, u8 pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c000000000877230)
Location: drivers/pci/of.c:469
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
```
**Symbols:**

```
c000000000877230-c00000000087749c: of_irq_parse_and_map_pci (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_irq_parse_and_map_pci(const struct pci_dev *dev, u8 slot, u8 pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004c9cf2)
Location: drivers/pci/of.c:469
Inline: False
```
**Symbols:**

```
ffffffe0004c9cf2-ffffffe0004c9e7a: of_irq_parse_and_map_pci (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/of_pci.h:36
Inline: False
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
