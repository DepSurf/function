# Function: <code>dw_pcie_ep_raise_msix_irq</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815604a0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:426
Inline: False
```
**Symbols:**

```
ffffffff815604a0-ffffffff81560613: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:441
Inline: False
```
**Symbols:**

```
ffffffff81590a94-ffffffff81590aac: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff81590890-ffffffff815909f5: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffff815b27c4-ffffffff815b27dc: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff815b25c0-ffffffff815b2725: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:430
Inline: False
```
**Symbols:**

```
ffffffff8165c2e6-ffffffff8165c2fe: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff8165c0e0-ffffffff8165c1d3: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167d650)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:561
Inline: False
```
**Symbols:**

```
ffffffff8167d650-ffffffff8167d7b7: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816604d0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:559
Inline: False
```
**Symbols:**

```
ffffffff816604d0-ffffffff81660636: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d30f0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:559
Inline: False
```
**Symbols:**

```
ffffffff816d30f0-ffffffff816d3257: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fc460)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:562
Inline: False
```
**Symbols:**

```
ffffffff817fc460-ffffffff817fc5d4: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81929310)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:564
Inline: False
```
**Symbols:**

```
ffffffff81929310-ffffffff81929484: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d550)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:564
Inline: False
```
**Symbols:**

```
ffffffff8196d550-ffffffff8196d6ef: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b7470)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:522
Inline: False
```
**Symbols:**

```
ffffffff819b7470-ffffffff819b7642: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072fea8)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffff80001072fea8-ffff80001073010c: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b915c)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
c08b915c-c08b92f4: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e9f14)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffe0004e9f14-ffffffe0004ea0b4: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
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
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffff815a5f84-ffffffff815a5f9c: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff815a5d80-ffffffff815a5ee5: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffff81595124-ffffffff8159513c: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff81594f20-ffffffff81595085: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffff815a6514-ffffffff815a652c: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff815a6310-ffffffff815a6475: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dw_pcie_ep_raise_msix_irq(struct dw_pcie_ep *ep, u8 func_no, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:408
Inline: False
```
**Symbols:**

```
ffffffff815c0914-ffffffff815c092c: dw_pcie_ep_raise_msix_irq.cold (STB_LOCAL)
ffffffff815c0710-ffffffff815c0875: dw_pcie_ep_raise_msix_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
