# Function: <code>dw_pcie_ep_raise_msi_irq</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549b00)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:290
Inline: False
```
**Symbols:**

```
ffffffff81549b00-ffffffff81549ce4: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81560350)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:383
Inline: False
```
**Symbols:**

```
ffffffff81560350-ffffffff81560499: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:395
Inline: False
```
**Symbols:**

```
ffffffff81590a76-ffffffff81590a94: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff81590750-ffffffff81590881: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffff815b27a6-ffffffff815b27c4: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff815b2480-ffffffff815b25b1: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:384
Inline: False
```
**Symbols:**

```
ffffffff8165c2c8-ffffffff8165c2e6: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff8165bfa0-ffffffff8165c0d1: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167d440)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:491
Inline: False
```
**Symbols:**

```
ffffffff8167d440-ffffffff8167d5e0: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816602b0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:489
Inline: False
```
**Symbols:**

```
ffffffff816602b0-ffffffff81660453: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2ed0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:489
Inline: False
```
**Symbols:**

```
ffffffff816d2ed0-ffffffff816d3078: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fb620)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:491
Inline: False
```
**Symbols:**

```
ffffffff817fb620-ffffffff817fb7fa: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928390)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:493
Inline: False
```
**Symbols:**

```
ffffffff81928390-ffffffff8192856a: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c5c0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:493
Inline: False
```
**Symbols:**

```
ffffffff8196c5c0-ffffffff8196c797: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b68f0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:454
Inline: False
```
**Symbols:**

```
ffffffff819b68f0-ffffffff819b6b16: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072fd50)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
```
**Symbols:**

```
ffff80001072fd50-ffff80001072fea4: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9028)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
c08b9028-c08b915c: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
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
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9dc4)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffe0004e9dc4-ffffffe0004e9f14: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffff815a5f66-ffffffff815a5f84: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff815a5c40-ffffffff815a5d71: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffff81595106-ffffffff81595124: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff81594de0-ffffffff81594f11: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffff815a64f6-ffffffff815a6514: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff815a61d0-ffffffff815a6301: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msi_irq(struct dw_pcie_ep *ep, u8 func_no, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:362
Inline: False
```
**Symbols:**

```
ffffffff815c08f6-ffffffff815c0914: dw_pcie_ep_raise_msi_irq.cold (STB_LOCAL)
ffffffff815c05d0-ffffffff815c0701: dw_pcie_ep_raise_msi_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
