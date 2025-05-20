# Function: <code>dw_pcie_readl_atu</code>

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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f3b9)
Location: drivers/pci/controller/dwc/pcie-designware.h:307
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f98e)
Location: drivers/pci/controller/dwc/pcie-designware.h:319
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b16fe)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165af6e)
Location: drivers/pci/controller/dwc/pcie-designware.h:345
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81bfdd7d)
Location: drivers/pci/controller/dwc/pcie-designware.c:184
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
```
**Symbols:**

```
ffffffff8167a7c0-ffffffff8167a801: dw_pcie_readl_atu (STB_LOCAL)
ffffffff81bfdd7d-ffffffff81bfdd93: dw_pcie_readl_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d308)
Location: drivers/pci/controller/dwc/pcie-designware.c:184
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff8165d2d0-ffffffff8165d31a: dw_pcie_readl_atu (STB_LOCAL)
ffffffff81befcb2-ffffffff81befcc5: dw_pcie_readl_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfd78)
Location: drivers/pci/controller/dwc/pcie-designware.c:184
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff816cfd40-ffffffff816cfd8a: dw_pcie_readl_atu (STB_LOCAL)
ffffffff81ceb307-ffffffff81ceb31a: dw_pcie_readl_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f8ac8)
Location: drivers/pci/controller/dwc/pcie-designware.c:184
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff817f8a80-ffffffff817f8ae6: dw_pcie_readl_atu (STB_LOCAL)
ffffffff81eb2715-ffffffff81eb2728: dw_pcie_readl_atu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 dir, u32 index, u32 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924b80)
Location: drivers/pci/controller/dwc/pcie-designware.c:366
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff81924b80-ffffffff81924c46: dw_pcie_readl_atu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 dir, u32 index, u32 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819688d0)
Location: drivers/pci/controller/dwc/pcie-designware.c:379
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff819688d0-ffffffff81968996: dw_pcie_readl_atu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 dw_pcie_readl_atu(struct dw_pcie *pci, u32 dir, u32 index, u32 reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2110)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff819b2110-ffffffff819b21d6: dw_pcie_readl_atu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d850)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6fa4)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7ee2)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4ebe)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8159405e)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a544e)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf84e)
Location: drivers/pci/controller/dwc/pcie-designware.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
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
<b>Param added. </b>
<code>u32 dir</code>
</li>
<li>
<b>Param added. </b>
<code>u32 index</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, reg</code> ➡️ <code>pci, dir, index, reg</code>
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
