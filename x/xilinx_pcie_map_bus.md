# Function: <code>xilinx_pcie_map_bus</code>

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
void *xilinx_pcie_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723578)
Location: drivers/pci/controller/pcie-xilinx.c:185
Inline: False
```
**Symbols:**

```
ffff800010723578-ffff800010723624: xilinx_pcie_map_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xilinx_pcie_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c08aff30)
Location: drivers/pci/controller/pcie-xilinx.c:185
Inline: False
```
**Symbols:**

```
c08aff30-c08affb8: xilinx_pcie_map_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xilinx_pcie_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (c000000000891e30)
Location: drivers/pci/controller/pcie-xilinx.c:185
Inline: False
```
**Symbols:**

```
c000000000891e30-c000000000891f54: xilinx_pcie_map_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xilinx_pcie_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6ab6)
Location: drivers/pci/controller/pcie-xilinx.c:185
Inline: False
```
**Symbols:**

```
ffffffe0004e6ab6-ffffffe0004e6b3e: xilinx_pcie_map_bus (STB_LOCAL)
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
