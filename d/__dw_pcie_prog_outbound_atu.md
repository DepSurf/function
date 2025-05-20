# Function: <code>__dw_pcie_prog_outbound_atu</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:270
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff8167aca0-ffffffff8167ae14: __dw_pcie_prog_outbound_atu (STB_LOCAL)
ffffffff81bfde14-ffffffff81bfde29: __dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:313
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff8165d580-ffffffff8165d86d: __dw_pcie_prog_outbound_atu (STB_LOCAL)
ffffffff81befd2e-ffffffff81befd56: __dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:313
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff816cfff0-ffffffff816d02dd: __dw_pcie_prog_outbound_atu (STB_LOCAL)
ffffffff81ceb383-ffffffff81ceb3ab: __dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:313
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff817f8e60-ffffffff817f9126: __dw_pcie_prog_outbound_atu (STB_LOCAL)
ffffffff81eb279e-ffffffff81eb27c6: __dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924dc0)
Location: drivers/pci/controller/dwc/pcie-designware.c:454
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff81924dc0-ffffffff81924fee: __dw_pcie_prog_outbound_atu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968b10)
Location: drivers/pci/controller/dwc/pcie-designware.c:467
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff81968b10-ffffffff81968d3e: __dw_pcie_prog_outbound_atu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dw_pcie_prog_outbound_atu(struct dw_pcie *pci, u8 func_no, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2350)
Location: drivers/pci/controller/dwc/pcie-designware.c:468
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff819b2350-ffffffff819b257e: __dw_pcie_prog_outbound_atu (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
