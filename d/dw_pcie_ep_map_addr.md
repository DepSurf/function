# Function: <code>dw_pcie_ep_map_addr</code>

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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549bd1)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81560576)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:230
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81590952)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:230
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b2682)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165c168)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:208
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:295
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff8167c920-ffffffff8167c9bd: dw_pcie_ep_map_addr (STB_LOCAL)
ffffffff81bfe2d9-ffffffff81bfe30b: dw_pcie_ep_map_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:295
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff8165f790-ffffffff8165f82d: dw_pcie_ep_map_addr (STB_LOCAL)
ffffffff81befebc-ffffffff81befeee: dw_pcie_ep_map_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:295
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff816d2380-ffffffff816d241d: dw_pcie_ep_map_addr (STB_LOCAL)
ffffffff81ceb526-ffffffff81ceb558: dw_pcie_ep_map_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:296
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff817fb570-ffffffff817fb614: dw_pcie_ep_map_addr (STB_LOCAL)
ffffffff81eb2941-ffffffff81eb2971: dw_pcie_ep_map_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928280)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:302
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff81928280-ffffffff81928380: dw_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c4b0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:302
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff8196c4b0-ffffffff8196c5a8: dw_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, u8 vfunc_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b5a80)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff819b5a80-ffffffff819b5b78: dw_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f568)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffff80001072f568-ffff80001072f648: dw_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b8970)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
c08b8970-c08b8a24: dw_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dw_pcie_ep_map_addr(struct pci_epc *epc, u8 func_no, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9634)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffe0004e9634-ffffffe0004e9714: dw_pcie_ep_map_addr (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5e42)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594fe2)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a63d2)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c07d2)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:197
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, addr, pci_addr, size</code> ➡️ <code>epc, func_no, vfunc_no, addr, pci_addr, size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
