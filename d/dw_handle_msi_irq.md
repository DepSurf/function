# Function: <code>dw_handle_msi_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a5270)
Location: drivers/pci/host/pcie-designware.c:184
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_msi_irq_handler
```
**Symbols:**

```
ffffffff814a5270-ffffffff814a532f: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c7540)
Location: drivers/pci/host/pcie-designware.c:258
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_msi_irq_handler
```
**Symbols:**

```
ffffffff814c7540-ffffffff814c75ff: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d3740)
Location: drivers/pci/dwc/pcie-designware-host.c:57
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_msi_irq_handler
```
**Symbols:**

```
ffffffff814d3740-ffffffff814d3801: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513b20)
Location: drivers/pci/dwc/pcie-designware-host.c:57
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_msi_irq_handler
```
**Symbols:**

```
ffffffff81513b20-ffffffff81513bd9: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815492d0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff815492d0-ffffffff815493f0: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fa00)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff8155fa00-ffffffff8155faeb: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81590300)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff81590300-ffffffff815903eb: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b2030)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff815b2030-ffffffff815b211f: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b9c0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:79
Inline: False
```
**Symbols:**

```
ffffffff8165b9c0-ffffffff8165bad4: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bd70)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff8167bd70-ffffffff8167be57: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ec40)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff8165ec40-ffffffff8165ed19: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1800)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff816d1800-ffffffff816d18cf: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa8c0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:56
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff817fa8c0-ffffffff817fa99e: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81927090)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:55
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff81927090-ffffffff81927171: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b260)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:55
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff8196b260-ffffffff8196b345: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4d40)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffff819b4d40-ffffffff819b4e25: dw_handle_msi_irq (STB_GLOBAL)
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
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ea08)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffff80001072ea08-ffff80001072eb24: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7f10)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
```
**Symbols:**

```
c08b7f10-c08b8008: dw_handle_msi_irq (STB_GLOBAL)
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
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8d7e)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
**Symbols:**

```
ffffffe0004e8d7e-ffffffe0004e8e42: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a57f0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff815a57f0-ffffffff815a58df: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594990)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff81594990-ffffffff81594a7f: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5d80)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff815a5d80-ffffffff815a5e6f: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t dw_handle_msi_irq(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0180)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:78
Inline: False
```
**Symbols:**

```
ffffffff815c0180-ffffffff815c026f: dw_handle_msi_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct pcie_port *pp</code> ➡️ <code>struct dw_pcie_rp *pp</code>
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
