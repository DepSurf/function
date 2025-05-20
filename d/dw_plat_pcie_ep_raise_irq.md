# Function: <code>dw_plat_pcie_ep_raise_irq</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:79
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:83
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:57
Inline: False
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:57
Inline: False
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:57
Inline: False
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:57
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:44
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:44
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:44
Inline: False
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
int dw_plat_pcie_ep_raise_irq(struct dw_pcie_ep *ep, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffff8000107308c0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
```
**Symbols:**

```
ffff8000107308c0-ffff800010730978: dw_plat_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_plat_pcie_ep_raise_irq(struct dw_pcie_ep *ep, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (c08b9a04)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
```
**Symbols:**

```
c08b9a04-c08b9a6c: dw_plat_pcie_ep_raise_irq (STB_LOCAL)
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
int dw_plat_pcie_ep_raise_irq(struct dw_pcie_ep *ep, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffffffe0004ea788)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
```
**Symbols:**

```
ffffffe0004ea788-ffffffe0004ea82e: dw_plat_pcie_ep_raise_irq (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-plat.c:77
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
