# Function: <code>pci_irqd_intx_xlate</code>

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
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain *d, struct device_node *node, const u32 *intspec, unsigned int intsize, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107232a8)
Location: include/linux/pci.h:1523
Inline: False
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010723e98)
Location: include/linux/pci.h:1523
Inline: False
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107269a0)
Location: include/linux/pci.h:1523
Inline: False
```
**Symbols:**

```
ffff8000107232a8-ffff8000107232d0: pci_irqd_intx_xlate (STB_LOCAL)
ffff800010723e98-ffff800010723ec0: pci_irqd_intx_xlate (STB_LOCAL)
ffff8000107269a0-ffff8000107269c8: pci_irqd_intx_xlate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain *d, struct device_node *node, const u32 *intspec, unsigned int intsize, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c08aff04)
Location: include/linux/pci.h:1523
Inline: False
```
```
In drivers/pci/controller/pcie-altera.c (c08b1ac0)
Location: include/linux/pci.h:1523
Inline: False
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c08b9a6c)
Location: include/linux/pci.h:1523
Inline: False
```
**Symbols:**

```
c08aff04-c08aff30: pci_irqd_intx_xlate (STB_LOCAL)
c08b1ac0-c08b1aec: pci_irqd_intx_xlate (STB_LOCAL)
c08b9a6c-c08b9a98: pci_irqd_intx_xlate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain *d, struct device_node *node, const u32 *intspec, unsigned int intsize, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c000000000891a30)
Location: include/linux/pci.h:1523
Inline: False
```
**Symbols:**

```
c000000000891a30-c000000000891a58: pci_irqd_intx_xlate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_irqd_intx_xlate(struct irq_domain *d, struct device_node *node, const u32 *intspec, unsigned int intsize, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6a90)
Location: include/linux/pci.h:1523
Inline: False
```
**Symbols:**

```
ffffffe0004e6a90-ffffffe0004e6ab6: pci_irqd_intx_xlate (STB_LOCAL)
```
</details>
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
