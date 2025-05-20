# Function: <code>dw_pcie_ep_set_msix</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:305
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:305
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:283
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167d060)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:385
Inline: False
```
**Symbols:**

```
ffffffff8167d060-ffffffff8167d1dd: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fee0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:385
Inline: False
```
**Symbols:**

```
ffffffff8165fee0-ffffffff8166005d: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2b00)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:385
Inline: False
```
**Symbols:**

```
ffffffff816d2b00-ffffffff816d2c7e: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbff0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:386
Inline: False
```
**Symbols:**

```
ffffffff817fbff0-ffffffff817fc19a: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928920)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:392
Inline: False
```
**Symbols:**

```
ffffffff81928920-ffffffff81928aca: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196cb60)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:392
Inline: False
```
**Symbols:**

```
ffffffff8196cb60-ffffffff8196cd0a: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b6700)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:356
Inline: False
```
**Symbols:**

```
ffffffff819b6700-ffffffff819b68de: dw_pcie_ep_set_msix (STB_LOCAL)
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
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f6f0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
Inline: False
```
**Symbols:**

```
ffff80001072f6f0-ffff80001072f7b4: dw_pcie_ep_set_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b8a98)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
Inline: False
```
**Symbols:**

```
c08b8a98-c08b8b4c: dw_pcie_ep_set_msix (STB_LOCAL)
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
int dw_pcie_ep_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e97a4)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
Inline: False
```
**Symbols:**

```
ffffffe0004e97a4-ffffffe0004e9864: dw_pcie_ep_set_msix (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:272
Inline: False
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
<code>epc, func_no, interrupts, bir, offset</code> ➡️ <code>epc, func_no, vfunc_no, interrupts, bir, offset</code>
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
