# Function: <code>xilinx_pcie_clear_err_interrupts</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xilinx_pcie_clear_err_interrupts(struct xilinx_pcie_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723e0c)
Location: drivers/pci/controller/pcie-xilinx.c:140
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
**Symbols:**

```
ffff800010723e0c-ffff800010723e8c: xilinx_pcie_clear_err_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xilinx_pcie_clear_err_interrupts(struct xilinx_pcie_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c08b08dc)
Location: drivers/pci/controller/pcie-xilinx.c:140
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
**Symbols:**

```
c08b08dc-c08b0948: xilinx_pcie_clear_err_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xilinx_pcie_clear_err_interrupts(struct xilinx_pcie_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c000000000892abc)
Location: drivers/pci/controller/pcie-xilinx.c:140
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
**Symbols:**

```
c000000000892abc-c000000000892b50: xilinx_pcie_clear_err_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xilinx_pcie_clear_err_interrupts(struct xilinx_pcie_port *port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e7510)
Location: drivers/pci/controller/pcie-xilinx.c:140
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
```
**Symbols:**

```
ffffffe0004e7510-ffffffe0004e75a0: xilinx_pcie_clear_err_interrupts (STB_LOCAL)
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
