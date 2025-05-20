# Function: <code>dw_pcie_ep_raise_irq</code>

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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:244
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:325
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:325
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:314
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167c3f0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:421
Inline: False
```
**Symbols:**

```
ffffffff8167c3f0-ffffffff8167c41e: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165f250)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:421
Inline: False
```
**Symbols:**

```
ffffffff8165f250-ffffffff8165f27e: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d1e10)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:421
Inline: False
```
**Symbols:**

```
ffffffff816d1e10-ffffffff816d1e41: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817faf50)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:422
Inline: False
```
**Symbols:**

```
ffffffff817faf50-ffffffff817faf9f: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81927a70)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:428
Inline: False
```
**Symbols:**

```
ffffffff81927a70-ffffffff81927abf: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196bc70)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:428
Inline: False
```
**Symbols:**

```
ffffffff8196bc70-ffffffff8196bcbf: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, unsigned int type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b5770)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:389
Inline: False
```
**Symbols:**

```
ffffffff819b5770-ffffffff819b57bf: dw_pcie_ep_raise_irq (STB_LOCAL)
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
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f3a0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
Inline: False
```
**Symbols:**

```
ffff80001072f3a0-ffff80001072f400: dw_pcie_ep_raise_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b87f8)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
Inline: False
```
**Symbols:**

```
c08b87f8-c08b8830: dw_pcie_ep_raise_irq (STB_LOCAL)
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
int dw_pcie_ep_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e94ca)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
Inline: False
```
**Symbols:**

```
ffffffe0004e94ca-ffffffe0004e9510: dw_pcie_ep_raise_irq (STB_LOCAL)
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:292
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
<code>epc, func_no, type, interrupt_num</code> ➡️ <code>epc, func_no, vfunc_no, type, interrupt_num</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum pci_epc_irq_type type</code> ➡️ <code>unsigned int type</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
