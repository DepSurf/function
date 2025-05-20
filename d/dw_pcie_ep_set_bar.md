# Function: <code>dw_pcie_ep_set_bar</code>

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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:163
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:163
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:140
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:220
Inline: False
```
**Symbols:**

```
ffffffff8167c710-ffffffff8167c8b1: dw_pcie_ep_set_bar (STB_LOCAL)
ffffffff81bfe29e-ffffffff81bfe2d9: dw_pcie_ep_set_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:220
Inline: False
```
**Symbols:**

```
ffffffff8165f580-ffffffff8165f721: dw_pcie_ep_set_bar (STB_LOCAL)
ffffffff81befe81-ffffffff81befebc: dw_pcie_ep_set_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:220
Inline: False
```
**Symbols:**

```
ffffffff816d2150-ffffffff816d2313: dw_pcie_ep_set_bar (STB_LOCAL)
ffffffff81ceb4eb-ffffffff81ceb526: dw_pcie_ep_set_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:221
Inline: False
```
**Symbols:**

```
ffffffff817fb390-ffffffff817fb561: dw_pcie_ep_set_bar (STB_LOCAL)
ffffffff81eb2906-ffffffff81eb2941: dw_pcie_ep_set_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81927fa0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:226
Inline: False
```
**Symbols:**

```
ffffffff81927fa0-ffffffff81928265: dw_pcie_ep_set_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c1a0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:226
Inline: False
```
**Symbols:**

```
ffffffff8196c1a0-ffffffff8196c49d: dw_pcie_ep_set_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b7000)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:204
Inline: False
```
**Symbols:**

```
ffffffff819b7000-ffffffff819b736a: dw_pcie_ep_set_bar (STB_LOCAL)
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
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072fb38)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
Inline: False
```
**Symbols:**

```
ffff80001072fb38-ffff80001072fce4: dw_pcie_ep_set_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b8e5c)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
Inline: False
```
**Symbols:**

```
c08b8e5c-c08b8fe8: dw_pcie_ep_set_bar (STB_LOCAL)
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
int dw_pcie_ep_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9bb4)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
Inline: False
```
**Symbols:**

```
ffffffe0004e9bb4-ffffffe0004e9d66: dw_pcie_ep_set_bar (STB_LOCAL)
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:130
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
<code>epc, func_no, epf_bar</code> ➡️ <code>epc, func_no, vfunc_no, epf_bar</code>
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
