# Function: <code>dw_pcie_prog_ep_outbound_atu</code>

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
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b050)
Location: drivers/pci/controller/dwc/pcie-designware.c:322
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff8167b050-ffffffff8167b069: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165dab0)
Location: drivers/pci/controller/dwc/pcie-designware.c:372
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff8165dab0-ffffffff8165dac8: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0520)
Location: drivers/pci/controller/dwc/pcie-designware.c:372
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff816d0520-ffffffff816d0538: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9410)
Location: drivers/pci/controller/dwc/pcie-designware.c:376
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff817f9410-ffffffff817f943c: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925790)
Location: drivers/pci/controller/dwc/pcie-designware.c:522
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff81925790-ffffffff819257b9: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969540)
Location: drivers/pci/controller/dwc/pcie-designware.c:535
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff81969540-ffffffff81969569: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_prog_ep_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2cf0)
Location: drivers/pci/controller/dwc/pcie-designware.c:536
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffff819b2cf0-ffffffff819b2d19: dw_pcie_prog_ep_outbound_atu (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
